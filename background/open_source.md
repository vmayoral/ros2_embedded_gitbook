# Open Source

| |  [TinyDDS](https://code.google.com/p/tinydds/) | [Tinq](https://github.com/vmayoral/tinq-core) |
|---- | ------|
|Footprint  | 36 KB | 600 KB (needs to be stripped)|
| ARM bare-bones support| No | Needs work |
| FPGA support | No | No |
| Open Source License | BSD | Clear BSD |



###[TinyDDS](https://code.google.com/p/tinydds/)

Taken from https://code.google.com/p/tinydds/:

>TinyDDS is an open-source and standards-based publish/subscribe middleware for wireless sensor networks. Compliant with the Object Management Group (OMG)’s Data Distribution Service (DDS) specification, TinyDDS is designed and implemented generic enough to aid in developing a wide range of event detection and data collection applications.

>TinyDDS is currently implemented in nesC, a dialect of the C language, for the TinyOS platform as well as in Java for the SunSPOT platform.


###[Tinq](https://github.com/vmayoral/tinq-core)

Tinq (branch of Qeo) includes an open source DDS implementation writen in plain C and licensed as Clear BSD. Although it was coded for general purpose OSs, the code interfaces are nicely separated which might allow to easily port it to embedded platforms.


###Sources
- [TinyDDS: An interoperable and configurable publish/subscribe middleware for wireless sensor networks](http://www.researchgate.net/publication/255969115_TinyDDS_An_Interoperable_and_Configurable_PublishSubscribe_Middleware_for_Wireless_Sensor_Networks/file/e0b49521214aaca660.pdf)
- [Middleware Support for Pluggable Non-functional Properties in Wireless Sensor Networks](file:///home/victor/Downloads/mnpsc08.pdf)

![](http://osrfoundation.org/assets/images/osrf_masthead.png)
