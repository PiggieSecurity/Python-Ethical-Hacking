opdracht


Je bouwt met behulp van Scapy een tool die in staat is tot:
- HOST DISCOVERY: gegeven een bepaalde IP-range het netwerk te doorzoeken naar beschikbare hosts (bvb via ARP)
- SERVICE DISCOVERY: gegeven het IP-adres van één of meerdere hosts (bvb als resultaat van de hierboven beschreven sweep) voer je een poort scan uit (voor alle poorten onder 1024)
- REMOTE OS DETECTIE: je voert een actieve fingerprinting uit op één of meerdere hosts (bvb als resultaat van de hierboven beschreven sweep) en detecteert op basis hiervan het OS van de host
- PCAP ANALYSE: je analyseert één of meerdere hosts op de aanwezigheid van HTTP-verkeer (één of meerdere andere soorten verkeer mogen uiteraard ook: SMTP, POP3, IMAP)
- Je tool werkt interactief in de terminal en via command-line argumenten (argparse)
- Loggen van de bevindingen naar een tekstbestand (html, csv of pdf mogen ook)
- Test enkel in een veilige gecontroleerde setting
