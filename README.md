# DHCP + Apache Webserver Week 2 Lab

## DE: Projektueberblick
Netzwerk- und Webserver-Lab unter Ubuntu: DHCP-Konzept verstehen, Apache konfigurieren und statische Website bereitstellen.

## DE: Inhalt
- `index.html`, `contact.html`: Beispielseiten
- `style.css`: gemeinsames Styling
- Schwerpunkt: lokale Bereitstellung ueber Apache

## DE: Lokal starten
```bash
sudo cp index.html contact.html style.css /var/www/html/
sudo systemctl restart apache2
# Browser: http://localhost
```

## DE: Lernziele
- DHCP-Ablauf (DORA) nachvollziehen
- Apache installieren, konfigurieren, testen
- Linux-Server-Basisbefehle sicher anwenden

## EN: Overview
Ubuntu lab for DHCP fundamentals and Apache deployment of a static website.

## EN: Run Locally
```bash
sudo cp index.html contact.html style.css /var/www/html/
sudo systemctl restart apache2
# Browser: http://localhost
```

## EN: Learning Focus
- DHCP workflow understanding
- Apache webserver operations
- Linux-based deployment basics
