# VARIABLES

Variables:

| Column               | Type          | Description                                                                                           |
|----------------------|---------------|-------------------------------------------------------------------------------------------------------|
| `rid`                | `INT(5)`      | Arbitrary, auto-incrementing primary key for SQL                                                      |
| `born`               | `INT(4)`      | What year the survey respondent was born                                                              |
| `country`            | `VARCHAR(40)` | What country the survey respondent is from                                                            |
| `country_num`        | `INT(3)`      | A numerically encoded variable for country                                                            |
| `latitude`           | `FLOAT`       | The survey respondent's latitude, by postal code                                                      |
| `longitude`          | `FLOAT`       | The survey respondent's longitude, by postal code                                                     |
| `tag`                | `BOOL`        | Whether the respondent calls the basic game "tag"                                                     |
| `tick`               | `BOOL`        | Whether the respondent calls the basic game "tick"                                                    |
| `tig`                | `BOOL`        | Whether the respondent calls the basic game "tig"                                                     |
| `tug`                | `BOOL`        | Whether the respondent calls the basic game "tug"                                                     |
| `tap`                | `BOOL`        | Whether the respondent calls the basic game "tap"                                                     |
| `had`                | `BOOL`        | Whether the respondent calls the basic game "had"                                                     |
| `it`                 | `BOOL`        | Whether the respondent calls the basic game "it"                                                      |
| `catch`              | `BOOL`        | Whether the respondent calls the basic game "catch"                                                   |
| `chasey`             | `BOOL`        | Whether the respondent calls the basic game "chasey"                                                  |
| `tips`               | `BOOL`        | Whether the respondent calls the basic game "tips"                                                    |
| `cheese`             | `BOOL`        | Whether the respondent calls the basic game "cheese"                                                  |
| `touch`              | `BOOL`        | Whether the respondent calls the basic game "touch"                                                   |
| `dobby`              | `BOOL`        | Whether the respondent calls the basic game "dobby"                                                   |
| `robin`              | `BOOL`        | Whether the respondent included "robin" in their version of "Jingle Bells, Batman Smells"             |
| `flew`               | `BOOL`        | Whether the respondent included "flew" in their version of "Jingle Bells, Batman Smells"              |
| `egg`                | `BOOL`        | Whether the respondent included "egg" in their version of "Jingle Bells, Batman Smells"               |
| `ran` OR `robin_ran` | `BOOL`        | Whether the respondent included "ran" or "ran away" in their version of "Jingle Bells, Batman Smells" |
| `saved`              | `BOOL`        | Whether the respondent included "saved" in their version of "Jingle Bells, Batman Smells"             |
| `batmobile`          | `BOOL`        | Whether the respondent included "batmobile" in their version of "Jingle Bells, Batman Smells"         |
| `broke`              | `BOOL`        | Whether the respondent included "broke" in their version of "Jingle Bells, Batman Smells"             |
| `lost`               | `BOOL`        | Whether the respondent included "lost" in their version of "Jingle Bells, Batman Smells"              |
| `wheel`              | `BOOL`        | Whether the respondent included "wheel" in their version of "Jingle Bells, Batman Smells"             |
| `joker`              | `BOOL`        | Whether the respondent included "joker" in their version of "Jingle Bells, Batman Smells"             |
| `away`               | `BOOL`        | Whether the respondent included "away" in their version of "Jingle Bells, Batman Smells"              |
| `ballet`             | `BOOL`        | Whether the respondent included "ballet" in their version of "Jingle Bells, Batman Smells"            |
| `billy`              | `BOOL`        | Whether the respondent included "billy" in their version of "Jingle Bells, Batman Smells"             |
| `willy`              | `BOOL`        | Whether the respondent included "willy" in their version of "Jingle Bells, Batman Smells"             |
| `motorway`           | `BOOL`        | Whether the respondent included "motorway" in their version of "Jingle Bells, Batman Smells"          |
| `kojak`              | `BOOL`        | Whether the respondent included "kojak" in their version of "Jingle Bells, Batman Smells"             |
| `pants`              | `BOOL`        | Whether the respondent included "pants" in their version of "Jingle Bells, Batman Smells"             |
| `taa`                | `BOOL`        | Whether the respondent included "TAA" in their version of "Jingle Bells, Batman Smells"               |
| `france`             | `BOOL`        | Whether the respondent included "France" in their version of "Jingle Bells, Batman Smells"            |
| `gun`                | `BOOL`        | Whether the respondent included "gun" in their version of "Jingle Bells, Batman Smells"               |
| `shot`               | `BOOL`        | Whether the respondent included "shot" or "shoot" in their version of "Jingle Bells, Batman Smells"   |
| `pitch`              | `BOOL`        | Whether the respondent included "pitch" in their version of "Jingle Bells, Batman Smells"             |
| `hey`                | `BOOL`        | Whether the respondent included "hey" in their version of "Jingle Bells, Batman Smells"               |
| `oi`                 | `BOOL`        | Whether the respondent included "oi" in their version of "Jingle Bells, Batman Smells"                |
| `ski`                | `BOOL`        | Whether the respondent included "ski" or "skiing" in their version of "Jingle Bells, Batman Smells"   |
| `knife`              | `BOOL`        | Whether the respondent included "knife" in their version of "Jingle Bells, Batman Smells"             |

Countries:

| "Code" | "Country"                          |
|--------|------------------------------------|
| 1      | "Afghanistan"                      |
| 2      | "Albania"                          |
| 3      | "Algeria"                          |
| 4      | "Andorra"                          |
| 5      | "Angola"                           |
| 6      | "Antigua and Barbuda"              |
| 7      | "Argentina"                        |
| 8      | "Armenia"                          |
| 9      | "Australia"                        |
| 10     | "Austria"                          |
| 11     | "Azerbaijan"                       |
| 12     | "Bahamas"                          |
| 13     | "Bahrain"                          |
| 14     | "Bangladesh"                       |
| 15     | "Barbados"                         |
| 16     | "Belarus"                          |
| 17     | "Belgium"                          |
| 18     | "Belize"                           |
| 19     | "Benin"                            |
| 20     | "Bhutan"                           |
| 21     | "Bolivia"                          |
| 22     | "Bosnia and Herzegovina"           |
| 23     | "Botswana"                         |
| 24     | "Brazil"                           |
| 25     | "Brunei"                           |
| 26     | "Bulgaria"                         |
| 27     | "Burkina Faso"                     |
| 28     | "Burundi"                          |
| 29     | "Côte d'Ivoire"                    |
| 30     | "Cabo Verde"                       |
| 31     | "Cambodia"                         |
| 32     | "Cameroon"                         |
| 33     | "Canada"                           |
| 34     | "Central African Republic"         |
| 35     | "Chad"                             |
| 36     | "Chile"                            |
| 37     | "China"                            |
| 38     | "Colombia"                         |
| 39     | "Comoros"                          |
| 40     | "Congo (Congo-Brazzaville)"        |
| 41     | "Costa Rica"                       |
| 42     | "Croatia"                          |
| 43     | "Cuba"                             |
| 44     | "Cyprus"                           |
| 45     | "Czechia (Czech Republic)"         |
| 46     | "Democratic Republic of the Congo" |
| 47     | "Denmark"                          |
| 48     | "Djibouti"                         |
| 49     | "Dominica"                         |
| 50     | "Dominican Republic"               |
| 51     | "Ecuador"                          |
| 52     | "Egypt"                            |
| 53     | "El Salvador"                      |
| 54     | "Equatorial Guinea"                |
| 55     | "Eritrea"                          |
| 56     | "Estonia"                          |
| 57     | "Eswatini (fmr. ""Swaziland"")"    |
| 58     | "Ethiopia"                         |
| 59     | "Fiji"                             |
| 60     | "Finland"                          |
| 61     | "France"                           |
| 62     | "Gabon"                            |
| 63     | "Gambia"                           |
| 64     | "Georgia"                          |
| 65     | "Germany"                          |
| 66     | "Ghana"                            |
| 67     | "Greece"                           |
| 68     | "Grenada"                          |
| 69     | "Guatemala"                        |
| 70     | "Guinea"                           |
| 71     | "Guinea-Bissau"                    |
| 72     | "Guyana"                           |
| 73     | "Haiti"                            |
| 74     | "Holy See"                         |
| 75     | "Honduras"                         |
| 76     | "Hungary"                          |
| 77     | "Iceland"                          |
| 78     | "India"                            |
| 79     | "Indonesia"                        |
| 80     | "Iran"                             |
| 81     | "Iraq"                             |
| 82     | "Ireland"                          |
| 83     | "Israel"                           |
| 84     | "Italy"                            |
| 85     | "Jamaica"                          |
| 86     | "Japan"                            |
| 87     | "Jordan"                           |
| 88     | "Kazakhstan"                       |
| 89     | "Kenya"                            |
| 90     | "Kiribati"                         |
| 91     | "Kuwait"                           |
| 92     | "Kyrgyzstan"                       |
| 93     | "Laos"                             |
| 94     | "Latvia"                           |
| 95     | "Lebanon"                          |
| 96     | "Lesotho"                          |
| 97     | "Liberia"                          |
| 98     | "Libya"                            |
| 99     | "Liechtenstein"                    |
| 100    | "Lithuania"                        |
| 101    | "Luxembourg"                       |
| 102    | "Madagascar"                       |
| 103    | "Malawi"                           |
| 104    | "Malaysia"                         |
| 105    | "Maldives"                         |
| 106    | "Mali"                             |
| 107    | "Malta"                            |
| 108    | "Marshall Islands"                 |
| 109    | "Mauritania"                       |
| 110    | "Mauritius"                        |
| 111    | "Mexico"                           |
| 112    | "Micronesia"                       |
| 113    | "Moldova"                          |
| 114    | "Monaco"                           |
| 115    | "Mongolia"                         |
| 116    | "Montenegro"                       |
| 117    | "Morocco"                          |
| 118    | "Mozambique"                       |
| 119    | "Myanmar (formerly Burma)"         |
| 120    | "Namibia"                          |
| 121    | "Nauru"                            |
| 122    | "Nepal"                            |
| 123    | "Netherlands"                      |
| 124    | "New Zealand"                      |
| 125    | "Nicaragua"                        |
| 126    | "Niger"                            |
| 127    | "Nigeria"                          |
| 128    | "North Korea"                      |
| 129    | "North Macedonia"                  |
| 130    | "Norway"                           |
| 131    | "Oman"                             |
| 132    | "Pakistan"                         |
| 133    | "Palau"                            |
| 134    | "Palestine State"                  |
| 135    | "Panama"                           |
| 136    | "Papua New Guinea"                 |
| 137    | "Paraguay"                         |
| 138    | "Peru"                             |
| 139    | "Philippines"                      |
| 140    | "Poland"                           |
| 141    | "Portugal"                         |
| 142    | "Qatar"                            |
| 143    | "Romania"                          |
| 144    | "Russia"                           |
| 145    | "Rwanda"                           |
| 146    | "Saint Kitts and Nevis"            |
| 147    | "Saint Lucia"                      |
| 148    | "Saint Vincent and the Grenadines" |
| 149    | "Samoa"                            |
| 150    | "San Marino"                       |
| 151    | "Sao Tome and Principe"            |
| 152    | "Saudi Arabia"                     |
| 153    | "Senegal"                          |
| 154    | "Serbia"                           |
| 155    | "Seychelles"                       |
| 156    | "Sierra Leone"                     |
| 157    | "Singapore"                        |
| 158    | "Slovakia"                         |
| 159    | "Slovenia"                         |
| 160    | "Solomon Islands"                  |
| 161    | "Somalia"                          |
| 162    | "South Africa"                     |
| 163    | "South Korea"                      |
| 164    | "South Sudan"                      |
| 165    | "Spain"                            |
| 166    | "Sri Lanka"                        |
| 167    | "Sudan"                            |
| 168    | "Suriname"                         |
| 169    | "Sweden"                           |
| 170    | "Switzerland"                      |
| 171    | "Syria"                            |
| 172    | "Tajikistan"                       |
| 173    | "Tanzania"                         |
| 174    | "Thailand"                         |
| 175    | "Timor-Leste"                      |
| 176    | "Togo"                             |
| 177    | "Tonga"                            |
| 178    | "Trinidad and Tobago"              |
| 179    | "Tunisia"                          |
| 180    | "Turkey"                           |
| 181    | "Turkmenistan"                     |
| 182    | "Tuvalu"                           |
| 183    | "Uganda"                           |
| 184    | "Ukraine"                          |
| 185    | "United Arab Emirates"             |
| 186    | "United Kingdom"                   |
| 187    | "United States of America"         |
| 188    | "Uruguay"                          |
| 189    | "Uzbekistan"                       |
| 190    | "Vanuatu"                          |
| 191    | "Venezuela"                        |
| 192    | "Vietnam"                          |
| 193    | "Yemen"                            |
| 194    | "Zambia"                           |
| 195    | "Zimbabwe"                         |
| 196    | "Antarctica"                       |
| 197    | "Hong Kong"                        |
| 198    | "Antarctica"                       |
| 199    | "Puerto Rico"                      |
| 200    | "Bermuda"                          |
| 201    | "Macedonia"                        |
| 202    | "Taiwan"                           |
| 203    | "Greenland"                        |
| 204    | "Isle of Man"                      |
| 205    | "Aruba"                            |
| 206    | "Falkland Islands"                 |
| 207    | "Cayman Islands"                   |
| 208    | "Kosovo"                           |
| 209    | "Others"                           |
