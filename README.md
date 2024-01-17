# Galaxy Buds Firmware Archive
An archive of firmware images for the Galaxy Buds family. Flashable with the GalaxyBudsClient application.

> [!CAUTION]
> Do NOT mix up firmware binaries of different models.
>
> For instance, flashing Galaxy Buds 2 Pro firmware onto the Galaxy Buds Pro will permanently brick your earbuds.


### How to read firmware build names
Build names are generally structured like this for all Samsung devices:
```
R175 XX U0 A U B 3
Model     
     Region
        Bootloader
           Reserved
             Year
               Month
                 Revision
```
Let's take `R175XXU0AUB3` as an example:
* `R175` is the model number and corresponds to the Galaxy Buds+ (see model list below)
* `XX` is unused for the Buds family. It would normally contain a region code.
* `U0` is unused for the Buds family. It would normally contain the bootloader version.
* `A` is unused for the Buds family. It would normally refer to the current count of major software upgrades.
* `U` is the year. In this case, `U` refers to 2021.
    * `U` = 2021
    * `V` = 2022
    * `W` = 2023
    * ...
* `B` is the month. In this case, `B` refers to February.
    * `A` = January
    * `B` = February
    * `C` = March
    * ...
* `3` is the revision number. In this case, `3` refers to the third revision.

So, to sum it all up: `R175XXU0AUB3` has been released in February 2021 (revision 3) for the Galaxy Buds+.


Model numbers:
* Samsung Galaxy Buds (SM-R170)
* Samsung Galaxy Buds+ (SM-R175)
* Samsung Galaxy Buds Live (SM-R180)
* Samsung Galaxy Buds Pro (SM-R190)
* Samsung Galaxy Buds 2 (SM-R177)
* Samsung Galaxy Buds 2 Pro (SM-R510)
* Samsung Galaxy Buds FE (SM-R400N)

