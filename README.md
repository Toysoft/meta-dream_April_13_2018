Dreambox BSP layer for:
```
dm500hd - kernel 3.2.100 driver 20140616 secondstage 84
dm500hdv2 - kernel 3.2.100 driver 20140616 secondstage 89
dm520 - kernel 3.4.113 driver 20171021 secondstage 3
dm800 - kernel 2.6.18 driver 20131228a secondstage 84
dm800se - kernel 3.2.100 driver 20151201 secondstage 84
dm800sev2 - kernel 3.2.100 driver 20151201 secondstage 89
dm820 - kernel 3.4.113 driver 20171115 secondstage 18
dm900 - kernel 3.14.79 driver 20171211 secondstage N/A
dm920 - kernel 3.14.79 driver 20171211 secondstage N/A
dm7020hd - kernel 3.2.100 driver 20161019 secondstage 89
dm7020hdv2 - kernel 3.2.100 driver 20161019 secondstage 89
dm7080 - kernel 3.4.113 driver 20171115 secondstage 14
dm8000 - kernel 3.2.100 driver 20140604a secondstage 84
```
How does it work? Simply with OpenPLi's OE!

Use https://github.com/OpenPLi/openpli-oe-core (rocko branch) with Ubuntu 16.04.3 LTS as your base, Open a terminal inside "openpli-oe-core" folder and enter:
```
wget https://raw.githubusercontent.com/PLi-metas/Dreamer/master/Dreamer-rocko.sh
sh Dreamer-rocko.sh
```
You must run Dreamer-rocko.sh only once!

For latest updates you need to open a terminal inside "meta-dream" folder and enter:
```
git pull origin rocko
```
each time you do "make update" for the OE.

We're independent so if you think you can help you're welcome to send us merge requests.
