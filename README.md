# Intro to Virtual Desktop Infrastructure (VDI) Guide

**Description/Overview:** Virtual Desktop Infrastructure (VDI) is a centralized server technology in which a network's users can access virtualized Operating System desktop environments over their preferred network devices. VDI provides benefits for both network users and their organizations: securely cloud-hosted data, centralization of apps and app data, access to virtual workspaces from a variety of devices, remote access solutions, and straightforward management of network and system resources.

#### Table of Contents

1. [Virtual Desktop Infrastructure (VDI) Components](#components)
2. [VDI Operations Explained](#explained)
3. [VDI Types](#types)
4. [VDI Vendors](#vendors)
5. [VDI Advantages and Disadvantages](#benefits)
6. [Supplemental Resources](#supplemental)

<hr />

## 1. <a name="components">Virtual Desktop Infrastructure (VDI) Components</a>

*Three core components of VDI systems include:*

* **Hypervisors:** A physical server is necessary to run a hypervisor, which is used for generating and maintaining the virtual machines (VMs), or virtualized OS environments.
* **Virtualized Desktop Environments:** Every VM installation has an associated OS image, with an application suite deployed for each of those images.
* **Connections:** Client apps (such as web browsers) allow for connections to virtualized desktop environments to be made through users' preferred devices.
  + User input from their connected sessions to virtualized OS interfaces is redirected for hosting on the physical server.
    - However, not all VDIs support long-term saving of data and customizations.


<hr />

## 2. <a name="explained">VDI Operations Explained</a>

(TODO)

<hr />

## 3. <a name="types">VDI Types</a>

*VDI can be categorized into two types, based on environment retainment:*

* **Persistent VDI:** Every user, upon first log-in, is assigned to a unique virtual desktop image (distributed from a resource pool) that they can configure and save to.
  + Modifications to these desktop environments are retained, including after connections end and new connections are made.
  + The flexibility and permanence of this VDI compensate for rapid workflows and complicated user needs. The user experience is similar to operating with traditionally-hosted OS interfaces.
* **Non-Persistent VDI:** Users are aligned with generic desktops, allocated from a pool, for any individual session. Although user customizations are not retained when sessions are logged out of, this type of VDI tends to be less expensive and supportive of greater scalability.
  + This form of VDI can involve users being distributed the same desktop image for each session or to be assigned ones entirely at random.
  + There are are resource advantages to this form of VDI: in particular, expenses are lowered and data center management operations are less complicated (especially due to not needing to host many unique virtual OS images).
    - Additionally, it may be more user-practical to implement Non-Persistent VDI, such as for users who just need a VDI session to complete a one-time task.

<hr />

## 4. <a name="vendors">VDI Vendors</a>

(TODO)

<hr />

## 5. <a name="benefits">VDI Advantages and Disadvantages</a>

(TODO)

<hr />

## 6. <a name="supplemental">Supplemental Resources</a>

* *[Citrix Systems Official Website](https://www.citrix.com/)*
* *[Horizon 8 VDI Official Webpage](https://www.omnissa.com/products/horizon-8/)*
* *[HP Anywhere Official Webpage](https://www.hp.com/us-en/services/workforce-solutions/workforce-computing/digital-workspaces/anyware-standard.html)*
