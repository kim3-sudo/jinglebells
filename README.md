# Jingle Bells, Batman Smells

On June 22, 2020, [Tom Scott](https://www.youtube.com/user/enyay) published a video titled [I asked 64,182 People About "Jingle Bells, Batman Smells". Here's What I Found Out.](https://youtu.be/V5u9JSnAAU4). He's also released the dataset, which he's begun to clean for his purposes. I've further cleaned it, encoded the countries as a numerical variable, and prepared it as a SQL, CSV, and Excel file, for your viewing and data analysis pleasure.

The generic CSV file is the most widely-compatible dataset. It is compatible with base R, Excel, Microsoft SQL Server Management Studio, MySQL and phpMyAdmin, Python pandas (and numpy) and I'm sure many more pieces of analysis software. It's probably (but not guaranteed) to be compatible with SAS, Stata, Matlab, and other software.

Likewise, the JSON file is widely-compatible, but it's probably more useful for developers than for data scientists. If you're experiencing issues with the CSV file, try using the JSON.

The Microsoft SQL file is compatible with Microsoft SQL Server 2016 or later. It might be compatible with earlier versions of Microsoft SQL Server, but compatibility is not guaranteed.

The MySQL file is compatible with MySQL 5 or later. It might be compatible with earlier versions of MySQL, but compatibility is guaranteed. The only official and supported way to import this script is through [phpMyAdmin](https://www.phpmyadmin.com). It is quite large, so you may need to edit your `php.ini` file and increase the `max_filesize` attribute. Be patient while it is uploading!

The Microsoft Excel file is provided only for your convenience, but it is not officially supported. Thus, it is entirely community supported. You may contribute fixes to the file.

An RDS file is also provided if you are using R. To use this, run the following line in your R console or in your R script to load in the data as `jinglebells`.

```R
jinglebells <- readRDS(url('https://github.com/kim3-sudo/jinglebells/blob/master/jinglebells.rds?raw=true'))
```

If you need variable descriptors, please see the [VARIABLES.md](https://github.com/kim3-sudo/jinglebells/blob/master/VARIABLES.md) document. It contains most of the encodings and variables.
