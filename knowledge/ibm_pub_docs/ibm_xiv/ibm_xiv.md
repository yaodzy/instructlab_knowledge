The IBM® XIV® Storage System is a next-generation high-end open disk storage system.

An integral part of IBM's broad spectrum of system storage offerings, the XIV system has an innovative grid architecture designed to deliver the highest levels of reliability, performance, scalability and functionality at low overall cost, while eliminating complexity and providing unprecedented ease of management.

Designed for exceptionally low total cost of ownership, the XIV system aims to tackle almost every aspect related to owning, operating and maintaining a storage system, including backup and restore, acquisition, environmentals, administration, and downtime cost factors.

The XIV system is designed to deliver consistently high performance through the elimination of hot spots and full exploitation of all key system resources at all times. Its ground-breaking architecture delivers these performance levels while innovatively leveraging the capacity and cost benefits of Very High Density Slower Rotation (VHDSR) drives.

Outstanding availability and reliability are delivered through a revolutionary redundancy scheme, enabling automated self healing with exceptionally fast rebuild times. Software functionality including snapshotting, thin provisioning and space reclamation, and remote mirroring can help ease provisioning and protect business data from unexpected outages. IBM XIV can help customers deploy an information infrastructure that is reliable, versatile and available while offering improvements in storage management, provisioning and improved asset utilization.

IBM® XIV® is a high-end grid-scale storage system that delivers consistently high performance, high resiliency and management simplicity while offering exceptional data economics, including powerful real-time compression. Industry benchmarks underscore stellar XIV performance and cost benefits.

As a grid-scale offering, every IBM XIV storage system contains multiple modules that are interconnected by integrated InfiniBand switches, forming a scale-out grid fabric that delivers exceptional IOPS performance. In addition, it includes a maintenance module for remote access to the system and an uninterruptible power supply modules to ensure system operation if an external power source fails.

IBM XIV storage system is ideal for cloud environments, offering predictable service levels for dynamic workloads, simplified scale management including in multi-tenant environments, flexible consumption models — and robust cloud automation and orchestration through OpenStack, RESTful API, and VMware. It offers data-at-rest encryption, advanced mirroring and self-healing, and provides investment protection with perpetual licensing that is transferable to all Spectrum Accelerate Family offerings (XIV Gen3, FlashSystem A9000/A9000R and Spectrum Accelerate). 

IBM® XIV® Storage System is characterized by powerful features and functionality.
These features and functionality include:

Performance

        Perfect load balancing
        Cache and disks in every module
        Extremely fast rebuild time in the event of disk failure
        Constant, predictable high performance with zero tuning

Reliability

        Unique data distribution method that eliminates "hot spots"
        Fault tolerance, failure analysis, and self-healing algorithms
        No single-point-of-failure

Scalability

        Support for thin provisioning
        Support for instant space reclamation
        Data migration

Connectivity

        iSCSI and Fibre Channel (FC) interfaces
        Multiple host access

Snapshots

        Innovative snapshot functionality, including support for practically unlimited number of snapshots, snap-of-snap and restore-from-snap

Replication

        Synchronous and asynchronous replication of a volume (as well as a consistency group) to a remote system

Ease of management

        Support for storage pools administrative units
        Remote configuration management
        Non-disruptive maintenance and upgrades
        Management software, including a graphical user interface (GUI) and a command-line interface (CLI)
        Notifications of events through e-mail, SNMP, or SMS messages
        XIV is supported by the following IBM products:
            IBM Power Virtualization Center (PowerVC). This is an advanced virtualization management offering that simplifies creating and managing virtual machines on IBM Power Systems™ servers using PowerVM® or PowerKVM hypervisors.
            IBM Spectrum Protect Snapshot. Formerly Tivoli® Storage FlashCopy® Manager, IBM® Spectrum Protect™ Snapshot delivers high levels of protection for key applications and databases using advanced integrated application snapshot backup and restore capabilities.
            IBM Spectrum Control. Formerly IBM Tivoli Storage Productivity Center, IBM Spectrum Control is integrated data and storage management software that provides monitoring, automation and analytics for organizations with multiple storage systems.

The IBM® XIV® Storage System configuration includes data modules, interface modules, Ethernet switches, and uninterruptible power supply units.

Data modules
    Each data module contains 12 disks DDR3 and 24GB of cache memory. IBM XIV supports all sorts of Near-line (7200RPM) SAS drives, in particular 2TB, 4TB, or 6TB disks. The disk drives serve as the nonvolatile memory for storing data in the storage grid and the cache memory is used for caching data previously read, prefetching of data from a disk, and for delayed destaging of previously written data.

    Note: Data modules are located on both upper and lower sections of the rack.
InfiniBand switch (x2)

        Dual power supply
        Each IB switch is connected to each XIV module
        Both IB switches are inter-connected on their ports 16, 17
        Port 18 is left empty for spare
        Ports 19-36 are inactive

Maintenance module
    Allows remote support access using a modem.
Interface modules (IM)
    Each contains disk drives and cache memory similar to the data modules. In addition, these modules have Host Interface Adapters with FC and iSCSI ports.
8Gbps FC

        2 dual-port FC HBAs on each interface module, i.e. 4 ports on each interface module, i.e. 24 ports on a full rack.

Uninterruptible power supply module complex
    The uninterruptible power supply module complex consists of three units. It maintains an internal power supply in the event of a temporary failure of the external power supply. In the case of a continuous external power failure, the uninterruptible power supply module complex maintains power long enough for a safe and ordered shutdown of the IBM XIV Storage System. The IBM XIV Storage System can sustain the failure of one uninterruptible power supply unit while protecting against external power failures.
ATS
    The Automatic Transfer Switch (ATS) switches between line cords in order to allow redundancy of external power.
Modem
    Allows the system to receive a connection for remote access by IBM support. The modem connects to the maintenance module.

Data and interface modules are generically referred to as "modules". Modules communicate with each other by means of the PCIe adapter. Each module contains redundant ports for module to module communication. The ports are all linked to the internal network through the switches. In addition, for monitoring purposes, the UPSs are directly connected to the individual modules.

IBM® XIV® Storage System Gen3 model 314 is a hardware-enhanced XIV Gen3 storage array targeted to customers who want high utilization of IBM Real-time Compression (RtC).
With double the RAM and CPU resources, IBM XIV Storage System model 314 delivers improved IOPS per compressed capacity and 1 to 2 PB of effective capacity without performance degradation. IBM XIV Storage System model 314 hardware enhancements include:

    2 x 6-core CPUs per module (versus 1 x 6-core CPU per module in Model 214)
    96 GB RAM per module (versus 48 GB RAM per module in Model 214)

Available configurations
IBM XIV Storage System model 314 is available for ordering in the following configurations:

    9 to 15 modules in a system
    4 TB or 6 TB drives
    800 GB SSD cache (mandatory)

IBM XIV Storage System version 11.6.2 with IBM XIV Storage Gen3 System Model 314 also supports the following:

    Up to 2 PB of available soft capacity
    Reduced minimum compressible volume size from 103 GB (in model 214) to 51 GB
    Support for IBM Spectrum Accelerate software licenses

The IBM® XIV® Storage System provides several management options.

GUI and CLI management applications
    These applications must be installed on each workstation that will be used for managing and controlling the system. All configurations and monitoring aspects of the system can be controlled through the GUI or the CLI.
SNMP
    Third-party SNMP-based monitoring tools are supported using the IBM XIV MIB.
E-mail notifications
    The IBM XIV Storage System can notify users, applications or both through e-mail messages regarding failures, configuration changes, and other important information.
SMS notifications
    Users can be notified through SMS of any system event.

IBM® XIV® Storage System hardware components are fully redundant, and ensure failover protection for each other to prevent a single point of system failure.

System failover processes are transparent to the user because they are swiftly and seamlessly completed.

Data arriving from the host for storage is temporarily placed in two separate caches before it is permanently written to two disk drives located in separate modules. This guarantees that the data is always protected against possible failure of individual modules, and this protection is in effect even before data has been written to the nonvolatile disk media.

The IBM® XIV® Storage System includes built-in mechanisms for self-healing to take care of individual component malfunctions and to automatically restore full data redundancy in the system within minutes.

Self-healing mechanisms dramatically increase the level of reliability in the IBM XIV Storage System. Rather than necessitating a technician's on-site intervention in the case of an individual component malfunction to prevent a possible malfunction of a second component, the automatically restored redundancy allows a relaxed maintenance policy based on a pre-established routine schedule.

Self-healing mechanisms are not just started in a reactive fashion following an individual component malfunction, but also proactively - upon detection of conditions indicating potential imminent failure of a component. Often, potential problems are identified well before they might occur with the help of advanced algorithms of preventive self-analysis that are continually running in the background. In all cases, self-healing mechanisms implemented in the IBM XIV Storage System identify all data portions in the system for which a second copy has been corrupted or is in danger of being corrupted. The IBM XIV Storage System creates a secure second copy out of the existing copy, and it stores it in the most appropriate part of the system. Taking advantage of the full data virtualization, and based on the data distribution schemes implemented in the IBM XIV Storage System, such processes are completed with minimal data migration.

As with all other processes in the system, the self-healing mechanisms are completely transparent to the user, and the regular activity of responding to I/O data requests is thoroughly maintained with no degradation to system performance. Performance, load balance, and reliability are never compromised by this activity.

IBM® XIV® Storage System cache writes are protected. Cache memory on a module is protected with ECC (Error Correction Coding). All write requests are written to two separate cache modules before the host is acknowledged. The data is later destaged to disks.

Redundancy of power is maintained in the IBM® XIV® Storage System through the following means:

    Three uninterruptible power supply units - the system can run indefinitely on two uninterruptible power supply units. No system component will lose power if a single uninterruptible power supply unit fails.
    Redundant power supplies in each data and interface module. There are two power supplies for each module and each power supply for a module is powered by a different uninterruptible power supply unit.
    Redundant power for Ethernet switches - each Ethernet switch is powered by two uninterruptible power supply units. One is a direct connect; one is through the Ethernet switch redundant power supply.
    Redundant line cords - to protect against the loss of utility power, two line cords are supplied to the ATS. If utility power is lost on one line cord, the ATS automatically switches to the other line cord, without impacting the system.
    In the event of loss of utility power on both line cords, the uninterruptible power supply units will maintain power to the system until an emergency destage of all data in the system can be performed. Once the emergency destage has completed, the system will perform a controlled power down.

The IBM XIV Storage System uses Flash-as-Cache (SSD) as a second, read-only, caching layer between the cache node and the disks.

This way, the system reduces disk access with having a cache that is an order-of-magnitude larger than the DRAM cache. Currently, the system features one SSD disk per module. Flash-as-cache is designed in module granularity, so lacking this feature in one module does not affect its functionality on other modules. Flash-as-cache can be enabled and disabled at run time, so a storage system can be equipped with SSDs anytime.
Installation
The SSD is a new hardware component that is identified as 1:SSD:<module:1>. It is automatically added when plugged in (no equip command needed). The SSD can be phased-out, tested and phased-in like a regular disk drive. Since it is read-cache only, no rebuild is triggered due to SSD component state change. It is implemented and accessed similarly to other disks.

The IBM® XIV® Storage System is a ground breaking, high performance storage product designed to help enterprises overcome this challenge through an exceptional mix of game-changing characteristics and capabilities

Breakthrough architecture and design
    The revolutionary design of IBM XIV Storage System enables exceptional performance optimization typically unattainable by traditional architectures. This optimization results in superior utilization of system resources and automatic workload distribution across all system hard drives. It also empowers administrators to tap into the system’s rich set of built-in, advanced functionality such as thin provisioning, mirroring and snapshots without adversely affecting performance.
Consistent, predictable performance and scalability
    The IBM XIV Storage System’s ability to optimize load distribution across all disks for all workloads, coupled with a powerful distributed cache implementation, facilitates high performance that scales linearly with added storage enclosures. Because this high performance is consistent—without the need for manual tuning—users can enjoy the same high performance during the typical peaks and troughs associated with volume and snapshot usage patterns, even after a component failure.

Resilience and self-healing
    The IBM XIV Storage System maintains resilience during hardware failures, continuing to function with minimal performance impact. Additionally, the solution’s advanced self-healing capabilities allow it to withstand additional hardware failures once it recovers from the initial failure.
Automatic optimization and management
    Unlike traditional storage solutions, the IBM XIV Storage System automatically optimizes data distribution through hardware configuration changes such as component additions, replacements or failure. This helps eliminate the need for manual tuning or optimization.


The IBM® XIV® Storage System provides powerful snapshot mechanisms for creating point-in-time copies of volumes.
The snapshot mechanisms include the following features:

    Differential snapshots, where only the data that differs between the source volume and its snapshot consumes storage space
    Instant creation of a snapshot without any interruption of the application, making the snapshot available immediately
    Writable snapshots, which can be used for a testing environment; storage space is only required for actual data changes
    Snapshot of a writable snapshot can be taken
    High performance that is independent of the number of snapshots or volume size
    The ability to restore from snapshot to volume or snapshot


Volumes can be put in a consistency group to facilitate the creation of consistent point-in-time snapshots of all the volumes in a single operation.
This is essential for applications that use several volumes concurrently and need a consistent snapshot of all these volumes at the same point in time.


Storage pools are used to administer the storage resources of volumes and snapshots.
The storage space of the IBM® XIV® Storage System can be administratively portioned into storage pools to enable the control of storage space consumption for specific applications or departments


IBM® XIV® Storage System can email important system events to IBM Support.
This allows IBM to immediately detect hardware failures warranting immediate attention and react swiftly (for example, dispatch service personnel). Additionally, IBM support personnel can conduct remote support and generate diagnostics for both maintenance and support purposes. All remote support is subject to customer permission and remote support sessions are protected with a challenge response security mechanism.


Third-party SNMP-based monitoring tools are supported for the IBM® XIV® Storage System MIB.


The parallel design underlying the activity of the Host Interface modules and the full data virtualization achieved in the system implement thorough multipathing access algorithms.
Thus, as the host connects to the system through several independent ports, each volume can be accessed directly through any of the Host Interface modules, and no interaction has to be established across the various modules of the Host Interface array.


The system can be set to automatically transmit appropriate alarm notification messages through SNMP traps, or email messages.
The user can configure various triggers for sending events and various destinations depending on the type and severity of the event. The system can also be configured to send notifications until a user acknowledges their receipt.


The IBM® XIV® Storage System offers a user-friendly and intuitive GUI application and CLI commands to configure and monitor the system.
These feature comprehensive system management functionality, encompassing hosts, volumes, consistency groups, storage pools, snapshots, mirroring relationships, data migration, events, and more.
For more information, see the IBM XIV Management Tools Operations Guide and IBM XIV Storage System XCLI User Manual.


External replication and mirroring mechanisms in the IBM® XIV® Storage System are an extension of the internal replication mechanisms and of the overall functionality of the system.
These features provide protection against a site disaster to ensure production continues. The mirroring can be performed over either Fibre Channel or iSCSI, and the host-to-storage protocol is independent of the mirroring protocol.


The IBM® XIV® Storage System is available in a partial rack system comprised of as few as six (6) modules, or as many as fifteen (15) modules per rack.
Partial rack systems may be upgraded by adding data and interface modules, up to the maximum of fifteen (15) modules per rack.
The system supports a non-disruptive upgrade of the system, as well as hotfix updates.
