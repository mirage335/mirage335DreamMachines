Optimized computer configurations, sometimes more cost-effective, sometimes more performant.


# Computers

## VR

VR capable computer specifically intended to render the most demanding applications at maximum resolution.


## Base

Less expensive VR capable computer suitable for common applications.


## Net
Fast network router solution.

Documented by spreadsheet.


## Workstation
High-end workstation. Build server. VR to HDMI adapter. VR position tracking provider.

Specifically designed for maximum responsiveness and peripherial bandwidth.

 >3xGPU Support

Documented by spreadsheet.

## Lightweight
Lightweight servers can be served by a "LapRack" approach - a RasPi connected to a USB battery and two OpenWRT routers. Low-power, compact, portable, and reliable.
https://github.com/mirage335/LapRack

CoreAutoSSH allows ad-hoc servers to be accessed by robust, automatic, reverse tunnel.
https://github.com/mirage335/CoreAutoSSH

# Prefer

## USB3 Controllers
Oculus reports incompatibility with some USB3 controllers. Most likely, these devices are also unsuitable for realtime industrial applications.

## Graphics Cards

Factory overclocked graphics cards may be pre-binned, and usually support overclocking ~1.2x beyond manufacturer specificatons.

Maxium power target is an important figure of merit for determining whether a graphics card will be able to remain at boost clock rather than thermal throttling.

## SSD
Be extremely skeptical of advertised SSD performance. Some variants are known to have severe latency issues under common conditions, or specific conditions which may be relevant to workstation workloads.

Samsung SSDs have generally proven reliable.

## RAM

High memory frequency compatibility with overclocked processors may not be guaranteed. Carefully select memory based on reports of quality fabrication.

# Threading

Single-thread and single-GPU performance improvements of a few percent, rather than orders of magnitude, have become significant to achieving higher resolution. This is due to VR applications in particular running consistently enough to render smooth framerates with latency margins of less than 10%.

# Reference
https://www.ebay.com/sch/i.html?_nkw=%28RTX%202080%2C+RTX%202070%2C+P6000%2C+P5000%2C+P5000%2C+M6000%2C+M6000%2C+M4000%2C+M2000%2C+K6000%2C+K5200%2C+K5100%2C+K5000%2C+K4200%2C+K2200%2C+GP100%2C+Titan%2C+GTX%201080%2C+GTX%201070%2C+GTX%201060%2C+GTX%201060%2C+GTX%201050%2C+GTX%20980%2C+GTX%20970%2C+GTX%20965%2C+GTX%20960%2C+GTX%20950%2C+GTX%20880%2C+GTX%20870%2C+GTX%20780%2C+GTX%20775%2C+GTX%20770%2C+GTX%20760%2C+GTX%20750%2C+GTX%20680%2C+GTX%20670%2C+GTX%20660%2C+GTX%20650%2C+GTX%20580%2C+GTX%20570%2C+GTX%20560%2C+GTX%20560%2C+GTX%20560%2C+GTX%20480%2C+GTX%20690%2C+GTX%20590%2C+GTX%20470%2C+RemoteFX%2C+Vega%2C+RX%20580%2C+RX%20570%2C+RX%20560%2C+RX%20550%2C+RX%20480%2C+RX%20470%2C+RX%20460%2C+RX%20560-B%2C+HD%208950%2C+HD%207970M%2C+R9%20Nano%2C+R9%20M290X%2C+R9%20M290%2C+R9%20Fury-X%2C+R9%20Fury%2C+R9%20390X%2C+R9%20390%2C+R9%20380X%2C+R9%20380%2C+R9%20295X2%2C+R9%20290X%2C+R9%20290%2C+R9%20285%2C+R9%20280X%2C+R9%20280%2C+R9%20270X%2C+R9%20270%2C+R7%20370%2C+R7%20360%2C+R7%20265%2C+R7%20260X%2C+HD%207990%2C+HD%207970%2C+HD%207950%2C+HD%207870%2C+HD%207850%2C+HD%207790%2C+HD%206990%2C+HD%206970%2C+HD%206950%2C+HD%205870%2C+W9000%2C+W7000%2C+M6100%29

https://www.reddit.com/r/oculus/wiki/compatible_hardware
https://en.wikipedia.org/wiki/List_of_Intel_chipsets#LGA_1151
https://en.wikipedia.org/wiki/Socket_AM4
https://us.msi.com/Motherboard/X470-GAMING-M7-AC/Specification

https://www.reddit.com/r/oculus/comments/401xtz/psa_not_all_usb3cards_will_work_with_the_rift/

https://www.gamersnexus.net/guides/2871-amd-vs-intel-vr-cpu-benchmarks-with-vive-and-rift/page-2	[1]

https://www.youtube.com/watch?v=kEjCq_bO4Uc	[2]

https://www.reddit.com/r/Amd/comments/8hurwf/question_2700x_meltdownspectre_impacts/

https://www.tomshardware.com/reviews/samsung-970-evo-ssd-review,5573-2.html

