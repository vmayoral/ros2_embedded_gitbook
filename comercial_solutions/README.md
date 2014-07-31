# Commercial solutions


| | [MicroDDS](http://www.icoup-consulting.com/microdds.html) |[CoreDX DDS](http://www.twinoakscomputing.com/coredx/embedded) | [Connext DDS Micro](http://www.rti.com/products/micro.html) | [Vortex Lite](http://www.prismtech.com/vortex/products/vortex-device/vortex-lite) |
|---|----------|-----------|-------------------|-------------|
|Footprint | | | | 200 KB |
| ARM bare-bones support| | Talks about ARM support in `operative systems` | Yes (apparently supports ARM devices without OS) | |
| FPGA support | | Yes | | |
| Open Source License | No | No | No | No |



All this work wouldn't be neccesary if there were any DDS embedded solution satisfying and OSI-license. Let's take a look at the available commercial solutions for embedded systems:

### [MicroDDS](http://www.icoup-consulting.com/microdds.html)
Presented as a tailored middleware for micro-controllers to match the communication needs of the client's applications in small devices with support for:

>- for 8-bit micro-controllers with less than 2KB SRAM and less than 32KByte ROM
>- built with the focus on performance and resource limited hardware
>- compliant to the DDS standard — proven and robust network technology
>- auto-discovery of peer nodes, and integration into the DDS infrastructure
>- simple and easy to use API (4 methods each)
>- enabling fault tolerant and high-available DDS applications for sensors and actuators

>With MicroDDS you opt in to the newest publisher / subscriber network technology for real-time systems on the market.

##### Licenses
No information about them is provided


### [CoreDX DDS [TwinOaks Computing]](http://www.twinoakscomputing.com/coredx/embedded)
CoreDX DDS is self-introduced as the leader in small footprint publish-subscribe middleware. They presume to support:
- Gumstix platforms
- ARM platforms
- MIPS platforms
- FPGAs


##### [Licenses](http://www.twinoakscomputing.com/coredx/licenses)
None of them seem to cover our necessities.

### [Connext DDS Micro (RTI)](http://www.rti.com/products/micro.html)
>RTI Connext DDS Micro provides a small-footprint modular messaging solution for resource-limited devices that have minimal memory, Flash, CPU power or no operating system. Connext DDS Micro simultaneously satisfies demanding real-time performance requirements along with stringent resource constraints. By abstracting out low-level networking and communication details and providing a flexible integration framework, Connext DDS Micro minimizes the amount of device- or application-specific code that has to be created and reduces development costs.

>Features and Benefits:
>- Small memory footprint
- User-configurable feature set through build options
- Support for low-power CPUs
- Scalability from embedded 16-bit microcontrollers to multicore 64-bit CPUs
- Bundled source code
- Pre-built support for Linux (x86), Windows, FreeRTOS (ARM), VxWorks (PowerPC) and devices without OS (ARM)
- Portability to other embedded or real-time operating systems
- Completely decentralized and easy-to-embed architecture with no message brokers or daemon processes
- Standards compliant: based on DDS programming interface and RTPS wire interoperability protocol


----

##### [Licenses](http://www.rti.com/resources/research-programs.html)
They seem to provide a license for research programs but there's also a current conversation with RTI. It might be interesting to include this topic on the discussion.

----

### [Vortex Lite (PrismTech)](http://www.prismtech.com/vortex/products/vortex-device/vortex-lite)

>Vortex Lite offers full DDSI rev2.1 interoperability with enhanced real-time performance. Vortex Lite brings real-time data sharing to resource constrained embedded devices.

>Key Benefits

>- Minimal resource-consumption with regard to CPU- and Memory-usage
- Allows variability on functionalities, transport and support of underlying OS / BSP
- Deterministic data delivery: data urgency / importance based network-scheduling
-Networking efficiency: configurable 'networkPartitions' allowing to partition the physical network
- Ease of use: pluggable ISO-C++ DDS-API

>Key Features

>- Smallest footprint on the market: as low as 200 KB
- Lowest end to end E2E latency, < 50 µsec (GigaBit LAN network)
- Real-time data-priority based network-scheduling
- ISO-C++ API for increased productivity and code quality

----

##### Licenses

----
