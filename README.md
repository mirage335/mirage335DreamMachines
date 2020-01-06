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
https://www.reddit.com/r/oculus/wiki/compatible_hardware
https://en.wikipedia.org/wiki/List_of_Intel_chipsets#LGA_1151
https://en.wikipedia.org/wiki/Socket_AM4
https://us.msi.com/Motherboard/X470-GAMING-M7-AC/Specification

https://www.reddit.com/r/oculus/comments/401xtz/psa_not_all_usb3cards_will_work_with_the_rift/

https://www.gamersnexus.net/guides/2871-amd-vs-intel-vr-cpu-benchmarks-with-vive-and-rift/page-2	[1]

https://www.youtube.com/watch?v=kEjCq_bO4Uc	[2]

https://www.reddit.com/r/Amd/comments/8hurwf/question_2700x_meltdownspectre_impacts/

https://www.tomshardware.com/reviews/samsung-970-evo-ssd-review,5573-2.html

