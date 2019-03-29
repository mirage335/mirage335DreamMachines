Optimized computer configurations, once at least twice as cost-effective as similarly performant prebuilt machines, and always a guide when selecting systems.

# Net
Fast network router solution.

Documented by spreadsheet.

# Micro
Embedded performant system, >7k Passmark, >1TFLOPS, >6 IO, minimum cost.

Documented by spreadsheet.

# Embedded
Intended for industrial robots. Expected to support RT_PREEMPT. Optimized for machine learning, visualization, and IO.

Current processor sockets support a maximum of 24 PCIe 3.0 lanes, limiting configuration to roughly "Gen3(16,0) (8,8), Gen2(4)".

Documented by spreadsheet.

# Base
Basic 'best performance per dollar' machine optimizes the cost of current hardware and power consumption, somewhat at the expense of upgradability. AMD seems to be a current industry leader in this mid-range market.

Cost-effective as a cryptocurrency mining rig, without wasting the opportunity for intermittent desktop use.

 >2xGPU Support

Documented by spreadsheet.

# Workstation
High-end workstation. VR adapter, hopefully supporting multiple 4k HDMI input encoding simultaneously with intense graphics.

 >3xGPU Support

Documented by spreadsheet.

# Lightweight
Lightweight servers can be served by a "LapRack" approach - a RasPi connected to a USB battery and two OpenWRT routers. Low-power, compact, portable, and reliable.
https://github.com/mirage335/LapRack

CoreAutoSSH allows ad-hoc servers to be accessed by robust, automatic, reverse tunnel.
https://github.com/mirage335/CoreAutoSSH

# Avoid

## Intel and NVIDIA
Intel and NVIDIA products should currently be considered NOT RECOMMENDED FOR NEW DESIGNS.

Poor support commitment to end-users has been demonstrated by both companies. 
* Performance degradation after sale (Intel).
* Probable worst-case latency impacts (Intel).
* Attempting to spin to security flaws (Intel).
* Proprietary drivers (NVIDIA).
* Abuse of driver EULA (NVIDIA).

VR applications in particular may be more likely to encounter persistent framerate degrading bugs due to delays in processing IO requests.

Despite higher per-core performance, Intel CPUs are not showing a clear benefit in VR applications. AMD CPUs, with slightly higher total multithreaded throughput, may perform better for some OpenVR applications [1] .

## ASUS Motherboards
ASUS motherboards have historically been more likely to ship with unusual BIOS modifications, increasing risk of compatibility issues with certain use cases.

## USB3 Controllers
Oculus reports incompatibility with some USB3 controllers. Most likely, these devices are also unsuitable for any realtime industrial applications.

## AMD FX CPUs and Older
VR applications - especially DCS World, Elite Dangerous, and Onward - have apparently shown some performance issues with AMD FX CPUs. Experiments with CPU affinity, process prioritization, overclocking, and simultaneous multithreading, strongly suggest this is due simply to insufficient total mutithreaded throughput. Newer processors (ie. Ryzen/Threadripper) are recommended.

All workstation designs mentioning AMD FX CPUs are to be considered in need of update.

# Details

Hardware acqusition strategies should now shift to less expensive equipment, prioritizing complete replacement rather than upgrades. Increasing support for alternative processor architectures, improved competiton in semiconductor fabrication, and the possibility of a poorly aligned business model, renders the value of a vendor's upgradable components much less certain. Shifting more frequently to lower-power systems is likely to also improve ecological sustainability.

Power supply, fans, and liquid cooling components are a possible exception, as some of these may be useful for multiple generations of new computer systems.

Transparency, down to chip hardware designs, should be considered evidence of lower depreciation risk.

# Reference
https://www.reddit.com/r/oculus/wiki/compatible_hardware
https://en.wikipedia.org/wiki/List_of_Intel_chipsets#LGA_1151
https://en.wikipedia.org/wiki/Socket_AM4
https://us.msi.com/Motherboard/X470-GAMING-M7-AC/Specification

https://www.reddit.com/r/oculus/comments/401xtz/psa_not_all_usb3cards_will_work_with_the_rift/

https://www.gamersnexus.net/guides/2871-amd-vs-intel-vr-cpu-benchmarks-with-vive-and-rift/page-2	[1]

