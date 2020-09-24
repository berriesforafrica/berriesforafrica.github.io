---
title: "Booting the Raspberry Pi from SSD"
#permalink: /docs/configuration/
excerpt: "How to make your Raspberry Pi boot from an SSD"
---

## Why booting from SSD?

By default, the Raspberry Pi boots up from a microSD memory card on which the Operating System and all applications and data are stored. But these memory card and the interface through which they are connected have a limited speed. In theory, the interface supports up to 50 MBps but the best memory cards only reach around 35 MBps in sequential writes. 

We have put this on a test and verfied the performance of a [SanDisk Extreme 128GB A2 U3 V30](https://www.amazon.de/-/en/gp/product/B07FCMKK5X) micro SD memory card that is often considered to be one of the best performant memory cards for use on the Raspberry Pi. 



**Info:** What do these numbers `A2`, `U3` and `V30` mean?
- `A2` is the Application Class. Memory cards with `A1` or `A2` Application Classes are created to make applications on mobile phones run faster. They do this by making random reads and writes of small files (eg 4KB) very fast. This is especially good for the Raspberry when it is used as a desktop computer. `A2` is better than `A1` but unfortunately, for the moment, the Raspberry Pi can not make use of the `A2` advantages, so they perform equally well as `A1` cards. However this might change in the future, so if you have to buy these cards now and there is almost no proce difference, `A2` is the preferred choice.
- `V30` is the Video Class and measures how fast the card can supported sustained reads or writes. This is especially useful for video recording and not so important for Raspberry Pi's used as desktop computers. 
- `U3` is the UHS Speed Class. It is etiher U1 or U3. `U1` is for minimum write performance of at least 10 MB/s and `U3` for minimum write performance of 30 MB/s. Again this refers to sustained writes which is especially useful for video recording. But not so important for the Raspberry Pi.
{: .notice--info}

Using the SD Diagnostics application on the Raspberry Pi OS, we obtain the following performance benchmarks:

By comparison, lets look at the figures of the Intenso High series of SSDs. 


So, ...


For more information on the performance of various storage options, see [Raspberry Pi Storage Benchmarks 2019 + Benchmarking Script](https://jamesachambers.com/raspberry-pi-storage-benchmarks-2019-benchmarking-script/)
{: .notice--info}


## Making the Raspberry Pi boot from SSD

To make ...


## Which disks or adapters to consider?

See the article on [Storage Benchmarks](/storage/storage-benchmarks/) for a performance review of several disks and adapters. Based on these performance benchmarks, we have selected the following disks and adapters:

| Ugreen xxxx | see []() |
| Intenso High Performance 120GB | see [Intenso High Performance SSD](/storage/intenso-high-performance-120gb-ssd) |
| Intenso High Performance 240GB | see [Intenso High Performance SSD](/storage/intenso-high-performance-120gb-ssd) |

**Note:** During our performance tests, we have found out that some chipsets used in the SSD adapters are not compatible withh the Raspberry Pi. Specifically, all adapters using a `xxx` chipset are not usable on the Raspberry Pi. This excludes the following adapters for use on the Raspberry Pi:

ccc
ccc





