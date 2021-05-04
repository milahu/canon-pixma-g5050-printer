# Canon Pixma G5050 printer

NOTE this is a private project, which is NOT affiliated with the printer manufacturer (Canon) in any way

## Contents

* [How to actually prepare the printer for shipping](#how-to-actually-prepare-the-printer-for-shipping)
* [How to remove air from ink tubes](#how-to-remove-air-from-ink-tubes)
* [How to replace the mainboard](#how-to-replace-the-mainboard)
* [Linux driver](#linux-driver)
* [Printing costs](#printing-costs)

## How to

### How to actually prepare the printer for shipping

#### Preface

This is an obvious PRODUCT DEFECT in the Canon Pixma G5050 printer,  
more precise an instruction defect,  
which in theory makes Canon [liable for damage](http://www.gesetze-im-internet.de/bgb/__823.html) from spilled ink on transport,  
but Canon can get away with this, since a damage of "only" 250 EUR  
is usually not worth the trouble of going to a court of law

This tactic works especially well  
in countries where there are no [class action lawsuits](https://en.wikipedia.org/wiki/Class_action)

When confronted with this obvious product defect,  
Canon will claim that the customer did something wrong,  
and will refuse to admit its own fault,  
and will also refuse to fix this problem for future generations.  
On eBay, there is a constant supply of "defect pixma g5050" with spilled ink ...

Instead, Canon will push you to buy a new printer for "only" 170 EUR,  
and if you dont buy a new printer, you pay 40 EUR  
for Canon's "sorry we cannot repair your printer" [abuse of monopoly](https://www.youtube.com/watch?v=6-3eGt_Oc-s)

#### Prepare the printer for shipping

the printer [manual](https://www.canon.co.uk/support/consumer_products/products/fax__multifunctionals/inkjet/pixma_g_series/pixma-g5050.html?type=manuals) says:

> **Transporting Your Printer**
> 
> When relocating the printer for changing your living place or repairing it, make sure of the following.
> 
> **Important**
> 
> * You cannot take ink out of ink tanks.

actually, yes you can. simply open the four ink tanks,
and rotate the printer, so that gravity can pull the ink outside.
do this in a shower or bathtub, where you can easily clean up all the spilled ink.

but for shipping, it is not necessary to remove all ink from the tanks:

> * Check if the tank cap is completely inserted. If the ink tank cover is not completely closed, insert the
tank cap properly.

actually, this is WRONG.

when we close the two blue tank caps, then we open the small valves for ink and air.
when the air valves are open, and the printer is rotated, the ink will flow outside through the air tubes.
when printing, the air tubes pull air into the ink tanks.

for shipping, the two blue tank caps should be OPEN.
but as long as the tank caps are open, we cannot close the printer.
so for shipping, we must remove the two blue tank caps, with some \*gentle\* force:
pull the tank caps slightly apart, where they are mounted on the white plastic axis.

we can open and close the two small ink valves also without the two blue tank caps,
by rotating the white plastic axis.
for shipping, make sure the tank caps would be in the OPEN position.

> * Prepare for transporting the printer with the print head attached. This allows the printer to automatically
cap the print head, thus preventing it from drying.
> * Do not remove the print head. Ink may leak.

yes. if you must remove the print heads, just let the ink flow back into the tanks.
for this, rotate the printer, so gravity can pull the ink back into the tanks.
then close the big ink valve. (repair-tools symbol)

> * If ink stains the inside of the printer, wipe them using a soft cloth dampened with water.
> * When transporting the printer, pack the printer in a plastic bag so that ink does not leak.
> * Pack the printer in a sturdy box so that it is placed with its bottom facing down, using sufficient
> protective material to ensure safe transport.
> * Do not tilt the printer. Ink may leak.
> * When a shipping agent is handling transport of the printer, have its box marked "THIS SIDE UP" to
> keep the printer with its bottom facing down. Mark also with "FRAGILE" or "HANDLE WITH CARE".
> * Please handle with care and ensure the box remains flat and NOT turned upside down or on its side, as
> the printer may be damaged and ink in the printer may leak.

hah! funny.

the original package has those pretty "this side up" markings, but guess what?
the average "shipping agent" simply does not care what the package says,
and shipping machines will care even less.
especially the shipping machines will throw the package,
and its only a matter of time until the package lands on the wrong side.

when you read the
[packaging tips (sealing and labeling)](https://www.dhlsameday.com/Pages/resources/packaging_tips.aspx)
of your shipping agent, they say something like:

> While DHL cannot always abide by directions indicating the orientation of packages,
> such as “This Side Up,” you can help to ensure that your package remains in the proper orientation during transit
> by placing the waybill and paperwork on the top of the package.

Special Handling Labels like "This Side Up" are only recommendations for the shipping agent,
but you can not force an average shipping agent to ship your package with "this side up".

### How to remove air from ink tubes

[How to remove air from ink tubes in a Canon Pixma G5050 tank printer](howto-remove-air-from-ink-tubes.md)

### How to replace the mainboard

#### Preface

Replacing the mainboard is simple, as long as you ignore the "advice" from canon.

Canon (and its subcontractors) will claim:

1. The mainboard must be calibrated, or even the firmware must be flashed onto the mainboard,
otherwise the printer will not work at all.
2. Only Canon can do this magic trick, so you absolutely must send your printer to a "certified" repair shop.

Both of these claims are false. I lost around 180 EUR only for "repair attempts",
which all were denied on the most ridiculous grounds.

For example Canon will claim:

1. The printer is a "total loss" because some milliliters of ink were spilled on transport,
so just buy a new one.
2. Canon's "safety" guidelines demand: If a customer has opened a device,
Canon must do some ridiculously expensive "security" checks on the device,
so the device is a "total loss" and you should buy a new one.
But of course, to make the "Canon repair experience" more interesting,
Canon will not tell you this up front,
even if you tell them up front, that you have opened the device.

One "repair attempt" usually costs 40 EUR.
In my case, Canon stole my money (worth 50 EUR),
and Canon stole both of my brand-new printheads (worth 80 EUR).

So ... if you have too much money and too much time, go waste it on Canon "service"

Otherwise:

#### Replace the mainboard

1. buy a new mainboard. price is around 80 EUR. you can only buy this from Canon and its subcontractors (same goes for the printheads)
2. ignore Canon's claim of "only we can replace the mainboard"
3. replace the mainboard yourself. I assume you have some experience in repairing electronics ...
    * be careful with the new mainboard,
      these boards are sensitive to ESD shocks (how i broke my mainboard).
      Touch the mainboard only on the edges
    * Put the black plastic frame on the mainboard, and only then connect all the wires.
      The "flexible flat cables" are the hardest to connect, since the sockets require quite some force to close. be careful, dont slip
4. if you want to test the printer before reassembly,
you must trick two sensors: the lid-close sensor and the top paper-feed sensor.
just stick a small piece of cardboard, where the plastic spike would go in
5. before you start the printer, make sure you have
    * inserted both printheads
    * filled all ink tanks
    * opened the large ink valve
    * closed the two blue caps on the tanks (to open the two small ink valves)
    * inserted some paper
    * closed the lid (or tricked the sensor)
6. connect power, start printer.
the printer display will show some japanese text. for example:
    * 印刷品質を向上させる調整を開始しますか? = Do you want to start making adjustments to improve print quality?
        * はい = Yes
        * いいえ = No
    * a second yes/no question will appear, should be safe to hit "yes"
7. now the printer will do some calibration.
if you left the lid open, and are in a dark room, you can see red light inside the printer, just below the printheads.
the printer will print around two pages for the calibration
8. change language:
    1. hit "settings" (button with repair tools symbol)
    2. hit "right" + "ok"
    3. hit "right" four times + "ok"
    4. hit "right" until you see your language + "ok"

## Linux driver

### Bug: temporary files are not deleted

this is a bug in the linux driver. here is a workaround script:

```bash
#!/usr/bin/env bash
# remove canon printer temp files older than x minutes
# run this script as root
minutes=5
# temp_path: folder with the cnij* temporary files
#temp_path=/var/tmp # arch linux
temp_path=/var/tmp/*cups*/tmp # nixos linux
while true
do    
  date    
  find $temp_path -maxdepth 1 -name 'cnij*' -mmin +${minutes} \
    -exec rm -v '{}' \;
  sleep ${minutes}m
done
```

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
