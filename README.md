This Data Package was created at the [Open Food Hackdays](http://food.opendata.ch) 2018 in Basel. The metadata here is provided as "best effort", without any guarantee of correctness. To contribute, please visit the [GitHub repository](https://github.com/foodopendata/foodstats-basel/issues/)

## Data

The Canton of Basel-City publishes a variety of geographic and statistical data on the subject of food. These are open data, but not yet state-of-the-art Open Government Data (OGD), i.e. they have not yet been published in a completely standardized way. A [series of datasets](https://github.com/foodopendata/food-datasets/issues/11) have been recommended for use and improvement at the Open Food Data Hackdays from the [Statistical Portal](http://www.statistik.bs.ch/zahlen/tabellen.html) (statistik.bs.ch)

From these, we focused on the Agriculture (farms, land use, animals) data to create this aggregate dataset, compiled from:

- [T07.1.01](http://www.statistik.bs.ch/dam/jcr:b29e2d0a-97be-43f2-870e-8d6fa8df3a4f/t07-1-01.xlsx) - Agricultural holdings
- [T07.1.02](http://www.statistik.bs.ch/dam/jcr:dcd5b5d6-00e1-42fb-bd5f-136666a9fa5a/t07-1-02.xlsx) - Agricultural land
- [T07.1.03](http://www.statistik.bs.ch/dam/jcr:b279759b-b641-4b9c-81bd-755bafa746aa/t07-1-03.xlsx) - Livestock stock

These topics can also be found in the [Indicators portal](http://www.statistik.bs.ch/zahlen/indikatoren/portal.html) and in the [Basel Atlas](https://www.basleratlas.ch/mobile.php), and from there downloaded/exported as CSV.

## Preparation

LibreOffice Calc was used to collate the years 2011-2016 from the source spreadsheets. Some manual tweaking was required to standardize the rows (there were some years missing in the 2nd spreadsheet), and columns (some of which were defined across rows, etc.)

The Data Package schema was inferred using the [Python library CLI](https://github.com/frictionlessdata/datapackage-py#cli).

## License

This package is licensed by its maintainers under the Public Domain Dedication
and License.

If you intended to use these data in a public or commercial product, please
check the data sources themselves for any specific restrictions.

Data Protection regulations and other [terms of use of statistik.bs.ch](http://www.statistik.bs.ch/system/disclaimer.html) apply.
