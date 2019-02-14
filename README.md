A project for maintaining my CV. This project includes a specific version of wkhtmltox (wkhtmltox-0.12.4_linux-generic-amd64.tar.xz) for converting my CV from HTML to pdf.

Steps:

1) clone the repo
2) cd curriculum-vitae/
3) tar xf wkhtmltox-0.12.4_linux-generic-amd64.tar.xz
4) Run the followng command to generate the CV from source:

```
$ ./wkhtmltox/bin/wkhtmltopdf <html_cource_file> <pdf_result_name>
$ ./wkhtmltox/bin/wkhtmltopdf cv/cv.html cv/farkas-istvan.pdf
```

Note: Save the source html with encoding: Western (Windows 1252)