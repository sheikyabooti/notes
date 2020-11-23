


CPU Architecture/Family
------------------------
**Recommendation: Intel i7 or i9.**

The two main vendors of desktop processors (x86_64) are Intel and AMD.  For the sake of simplicity, we will only look at Intel processors.

Intel splits their lineup into market segments, which helps guide CPU selection.  For desktops, from least performant to most

Celeron < i3 < i5 < i7 < i9 < Xeon  

Celeron, i3, and i5 are all used in cost conscious designs, and typically have either lower clockspeed, lower cache memory, or lower memory bandwidth than i7 or i9.  Xeon is typically marketed at server applications, and tends to have very large cache memory and/or high cpu clock, along with correspondingly high price tags.  In searching for a desktop, I will focus on i7 and i9, having good cost/performance.

Selecting your CPU also locks in your chipset and architecture.  Other than the chipset, the main caveat in selecting an i7/i9 is making sure you are looking at current generation architecture.  Intel releases products on a "tick-tock" cadence, which usually means there are two generations of mainline processors available at a given time.  Currently these are Comet Lake and Cascade Lake.

Both of these processors use the LGA 1200 chipset.  This will guide the choice of motherboard, memory, and storage

CPU Processor Selection
------------------------
**Recommendation: Intel i7 10700 or i9 10900.  base, K, KF, KA**

https://www.newegg.com/intel-core-i7-10700k-core-i7-10th-gen/p/N82E16819118183

https://www.newegg.com/intel-core-i9-10850k-core-i9-10th-gen/p/N82E16819118176
$475

after narrowing the choice to i7/i9, we are confronted with the strange naming convention of Intel microprocessors.


https://www.newegg.com/p/pl?N=100007671%20601351801%20601295136%20601300154&Order=1

i7-10700, i7-10700F, i7-10700K, i7-10700KA,i7-10700KF
i9-10850K, i9-10850KA
i9-10900, i9-10900F, i9-10900K, i9-10900KA, i9-10900KF    

no letters: Frequency locked, integrated GPU enabled
F           Frequency locked, integrated GPU disabled
K           Frequency unlocked, integrated GPU enabled
KA          Avenger's themed version of the K processor
KF          Frequncey unlocked, integrated GPU disabled

for now, I will be looking at K and potentially KF or KA processors


Motherboard
-------------------------
**Recommendation: Z490 motherboard**

https://www.newegg.com/p/N82E16813145193?Item=N82E16813145193
$190

LGA 1200 is a microprocessor and chipset, manufactured by Intel.  It is compatible with the Comet Lake and Cascade Lake architecture.  

chipsets
There are a number of chipsets that are compatible with LGA 1200.

roughly from least peforming to best performing
H110 < B460 < H470 < Q470 < W480 < Z490 


Motherboards vary widely in terms of features.  
Things to expect to find on a motherboard
Gigabit ethernet
USB 2.0 and 3.0
Serial ATA
fan headers

Things to look for on a motherboard
WiFi 802.11ax
Bluetooth
USB-C connection
2 m.2 connectors - these are used for the Storage

Questions to ask
Are there any special connection types I need?  Firewire?

https://www.newegg.com/p/pl?N=100007627%20601352138%20600009016%20600567794%20601334148&Order=1
This is a filter for LGA 1200 motherboards with 2 m.2 connectors and built in 802.11ax WiFi

Memory
---------------------------
**Recommendation: 32 or 64 GB or 2900MHz DDR4 DRAM, in a set of 4 matched pairs.**

https://www.newegg.com/g-skill-64gb-288-pin-ddr4-sdram/p/N82E16820232092?Item=N82E16820232092
$220

The LGA 1200 supports DDR memory up to 2933 MHz.
non-overclocked memory
2933 MHz

How much memory is enough?
I would not recommend anyone put less than 16GB into their computers.  I would recommend either 32GB or 64GB if you are feeling like splurging.

Do I want ECC Memory?
ECC memory is memory that has an extra bit for error correction.  These are mostly used for certain mission critical server applications, and are totallly unnecessary for home use.  The infrastructure that supports ECC tends to be more expenstive, and there are no real tangible benefits, the error rates being very low for convetional DDR RAM.

Storage
---------------------------
**Recommendation:1 or 2 TB of m.2 2280**

https://www.newegg.com/samsung-970-evo-plus-2tb/p/N82E16820147744
$249

https://www.newegg.com/samsung-970-evo-plus-1tb/p/N82E16820147743
$149

IDE -> SCSI -> SATA -> NVMe

One thing to be aware is that SATA, and NVMe are protocols, and m.2 is a form factor.  When I bought my last computer, I accidentally bought m.2 SSD SATA drives instead of m.2 SSD NVMe drives.  They look the same, and both would work in my computer, but NVMe is significantly faster than SATA.

How does Intel Optane compare against other NVMe drives?
Intel Optane is a brand of NVMe drives, they are faster, but muc more expensive

Video Card
---------------------------
**Recommendation: RTX 2060, or GTX 1660 if you are not doing video intenstive tasks or video games**

https://www.newegg.com/asus-geforce-rtx-2060-dual-rtx2060-o6g-evo/p/N82E16814126349?Item=N82E16814126349
$330

The two main players in video cards are AMD and Nvidia.  At this point, Nvidia seems to be pretty far in the lead in terms of performance, so we're going to look at those cards.

RTX 3070, 3080, 3090: The newest video cards, released in August of 2020 to great fanfare and very low stock and have been sold out for months.
RTX 2060, 2070, 2080: The previous generation cards,
GTX 1650, 1660      : This represents the low cost, mid range peformance market.

SLI?  What is SLI?  This means using two video cards in one computer, each doing roughly half of the work.  This is really only suitable for people with more money than sense, or for certain very high performance realtime applications.

Case
---------------------------

Here is a link to all of the ATX caes that support 2 5.25" disk drives and have a side-window
https://www.newegg.com/p/pl?N=100007583%20600030551%20600006505

The main criteria of a case
1. Mid sized ATX computer
2. At least one USB-c port
3. At least 2 USb ports in the front
3. space for an optical disk drive (ODD)
4. support for a Liquid cooling system



Power Supply
---------------------------
**Recommendation: 750W Titanium Certified 80+ PSU, either fully or semi-modular**
https://www.newegg.com/enermax-maxtytan-emt750ewt-750w/p/N82E16817194134?Item=N82E16817194134
$289

https://www.newegg.com/thermaltake-toughpower-gf1-tt-premium-edition-ps-tpd-0850fnfaga-1-850w/p/N82E16817153403
$130

Cooling
---------------------------
**Recommendation: All-in-one liquid cooling system**

https://www.newegg.com/cooler-master-masterliquid-ml240l-rgb-liquid-cooling-system/p/2YM-0004-00015?Item=2YM-0004-00015
$75