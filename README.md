# Canon Pixma G5050 printer

## Note

this is a private project, which is not affiliated with the printer manufacturer (Canon) in any way

## How to

[How to remove air from ink tubes in a Canon Pixma G5050 tank printer](howto-remove-air-from-ink-tubes.md)

## Linux driver

### Arch Linux

cnijfilter2 is available as [aur package](https://aur.archlinux.org/packages/cnijfilter2/)

`yay -S cnijfilter2`

(`yay` is one of many [aur helpers](https://wiki.archlinux.org/index.php/AUR_helpers))

this will install `/usr/share/cups/model/canong5000.ppd` (among others) which will be used by [cups](https://wiki.archlinux.org/index.php/CUPS).

cups will list the printer as `Canon G5000 series`

### Debian, Ubuntu, etc

debian wiki: https://wiki.debian.org/Canon

1. canon-europe.com
2. support
3. drivers
4. [pixma g5050](https://www.canon-europe.com/support/consumer_products/products/fax__multifunctionals/inkjet/pixma_g_series/pixma-g5050.html?type=drivers&language=en)
5. [linux 64 bit](https://www.canon-europe.com/support/consumer_products/products/fax__multifunctionals/inkjet/pixma_g_series/pixma-g5050.html?type=drivers&language=en&os=linux%20(64-bit))
6. IJ Printer Driver Ver. 5.90 for Linux (debian Packagearchive), Release date: 10 September 2019
7. download `cnijfilter2-5.90-1-deb.tar.gz` with 2.8 MB   
[here](https://gdlp01.c-wss.com/gds/2/0100010482/01/cnijfilter2-5.90-1-deb.tar.gz) is a direct link, that may or may not work
8. `tar xvf cnijfilter2-*-1-deb.tar.gz`
9. `cd cnijfilter2-*-1-deb/packages`
10. `apt install ./cnijfilter2_*.deb`

## Printing costs

the printer [currently costs](https://geizhals.eu/canon-pixma-g5050-3112c006-a2036002.html) around 230 Euro

cost per page is listed as 0.3 euro-cent per page by [druckkosten.de](https://www.druckkosten.de/kosten.php?&f%5Btyp_fs%5D=F&f%5Btyp_fn%5D=D&f%5Btyp_te%5D=_T&f%5B_f%5D=%25&f%5B_a%5D=aktuell&f%5B_pb%5D=0&doc=6&set%5Bmonth%5D=36&set%5Btpages%5D=20000&sort=4)  
this is reportedly the lowest cost per page, compared to other color ink printers
