## setup

requires `wkhtmltopdf`. be sure to install the latest version from: <http://wkhtmltopdf.org/downloads.html>

rename `assets/example_template.html` to `assets/template.html` and update it according to your needs

feel free to update the style (`assets/style.css`) too

## usage

create a new invoice (hourly rate):

    ./invoice new

create a new invoice (flat rate)

    ./invoice new -f

regenerate invoices (e.g. if you update your template)

    ./invoice regen

invoices are output to `invoices/`