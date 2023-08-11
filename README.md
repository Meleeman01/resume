# resume
my resume

pandoc resume.md -f markdown -t pdf --pdf-engine=wkhtmltopdf -c resume.css -s -o resume.pdf

in order to make a pdf resume., requires wkhtmltopdf as well. 

install the latest version of pandadoc see here

this command also worked well for me to adjust the margin size

```pandoc resume.md -f markdown -t pdf --pdf-engine=wkhtmltopdf -c resume.css -V margin-top=4 -V margin-left=4 -V margin-right=4 -V margin-bottom=4 -V papersize=letter -s -o resume.pdf```