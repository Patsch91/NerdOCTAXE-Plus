***BOM***

---------------------

Lilygo T-Display S3
-------

The Lilygo T-Display is *not* included in this csv. You will have to order it seperately - If you order the T-Display with the pins already soldered on you can of course delete the male pin header from this BOM. To connect the Board with the Screen I used Dupont Jumpers in 10cm. You just need these when you are building the setup with the case and the backplate.

Fuse
-------

In the "octaxe+DK wFuseHolder" there is - as the name indicates - a FuseHolder with a 10A Fuse. The 10 Amps should be sufficient when properly cooled. My prototype draws between 8,2 - 9,0A (Could be more when you power the Fans up to higher speeds) Maybe you should get some additional 12A Fuses (F2592CT-ND) in case 10A are blowing to early.

Heatsinks
-------

In the actual BOM you could delete the small heatsink too (Partno: "501100B00000G-ND") I have used 9x9x12mm Heatsinks instead, they fit quite nice on the Mosfets. In addition to that, to cool the buckconverter even more I used some 14x14x13mm small heatsinks on the backside of the pcb under the Buck. So with this setup it runs at about 55°C.

For cooling the Asics my first try were two heatsinks in 60x60mm with 39mm in height. These are pretty cheap on amazon, aliexpress etc. They are capable of cooling the 8 Asics but you need to turn the Fans up a bit :) As they are coming without any mounting helpings you will have to drill the holes yourself.
In the "bigger heatsink" branch I am currently trying to implement the heatsink from an Fujitsu RX2540 M1/M2. These ones are cheap aswell but you wont have to drill them by yourself... but this is actually WIP

Fans
-------

I used two Arctic S8038-7K Fans. Tried Noctua 80mm too, but with my heatsink configuration they were not powerful enough to get this miner to an acceptable temperature.

Case
-------

To have everything closed up I used a 80x160mm aluminium pcb junction box. These are widely available on amazon/aliexpress etc. I bought this [Case](https://www.amazon.de/dp/B08BLTBY2Q?ref=ppx_yo2ov_dt_b_fed_asin_title)  in 170mm lenght. For the "bigger heatsink" variant you should at least go for 220mm lenght.

