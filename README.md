


Steps:

clone repo
extract wkhtmltox-0.12.4_linux-generic-amd64.tar.xz

Generate CV from source:

$ ./wkhtmltox/bin/wkhtmltopdf <cource> <result>
$ ./wkhtmltox/bin/wkhtmltopdf cv/cv.html cv/farkas-istvan.pdf

Note: Save the source html with encoding: Western (Windows 1252) 