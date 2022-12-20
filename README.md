# qrcodehelper
A bash script to help automate the process of generating QR codes from the command line. Presently the script will produce QR codes for Bitcoin payments, WiFi Access Points, Custom email messages, Sms messages, Contact information in Vcard format, Website urls and Telephone numbers ie. for both landline and mobile telephones.

## Notes
qrcodehelper uses the console applicaton qrencode as a backend to generate custom qrcodes. Users have the option of using the defaults that generate images of excellent quality, or can enter custom qrencode options; however, this does require the given output file name used with the -o switch contain no spaces. The script has all the advantages and power of qrencode behind it but with the addition of specialized formatting required for the various formats.

## Installation
Place the file "qrcodehelper" in a directory listed anywhere by the $PATH variable. On Debian based systems if qrencode is not installed the script will prompt the user to do so ie. sudo apt-get install qrencode.
