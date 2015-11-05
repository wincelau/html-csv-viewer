# HTML CSV viewer

HTML Standalone CSV file viewer

## Usage

### With the filename

Get the viewer and put it in your CSV folder : 

```bash
curl -s https://raw.githubusercontent.com/wincelau/html-csv-viewer/master/viewer.min.html > path_containing_your_csv_file/yourcsvfile.csv.html
```

### With parameter

Get the viewer and put it in your HTTP folder :

```bash
curl -s https://raw.githubusercontent.com/wincelau/html-csv-viewer/master/viewer.min.html > viewer.html
```
Call the viewer.html and put your CSV file path in the url as parameter preceding by #

```
http://localhost/viewer.html#yourcsvfile.csv
http://localhost/viewer.html#data/yourcsvfile.csv
http://localhost/viewer.html#http://url/yourcsvfile.csv
```
