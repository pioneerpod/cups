# cups
docker run -d -p 631:631 --name cupsd --network host -v c:/var/log/cups:/var/log/cups -v c:/var/spool/cups-pdf/ANONYMOUS:/var/spool/cups-pdf/ANONYMOUS pioneerpod/cups
# call
10.0.75.2:631
