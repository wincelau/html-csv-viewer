# HTML CSV Viewer

HTML Standalone CSV file viewer

## Usage

### By Naming

Get the viewer.html and put it in your CSV folder and named like your CSV file : 

```bash
curl -s https://raw.githubusercontent.com/wincelau/html-csv-viewer/master/viewer.min.html > path_containing_your_csv_file/yourcsvfile.csv.html
```

### By Parameter

Get the viewer.html and put it in your HTTP folder :

```bash
curl -s https://raw.githubusercontent.com/wincelau/html-csv-viewer/master/viewer.min.html > viewer.html
```
Call the viewer.html and put your CSV file path in the url as parameter preceding by #

```
http://localhost/viewer.html#yourcsvfile.csv
http://localhost/viewer.html#data/yourcsvfile.csv
http://localhost/viewer.html#http://url/yourcsvfile.csv
```

## External ressources used :

* Bootstrap (http://getbootstrap.com/)
* PapaParse : CSV parser (https://github.com/mholt/PapaParse)
* Jquery DataTables : DataTables (http://www.datatables.net/)

