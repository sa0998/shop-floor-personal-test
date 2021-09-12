---
title: How ShopFloorConnect Monitors OEE
description: The ShopFloorConnect OEE monitoring software tracks machine availability
  for OEE by assigning time to specific machine states.
document_title: OEE calculation software | How to calculate OEE - ShopFloorConnect
key_words:
- OEE monitoring
- OEE System
- OEE Software
permalink: "/oee-monitoring-system"
menu:
  main:
    weight: 2
    parent: item_DsyKHj_
    identifier: item_taFPh5z

---
**The** [**ShopFloorConnect Machine Interface (SMI 2)**](/machine-monitoring-interface.html) **automatically detects when your machines are running, when they are stopped, and the number of parts they produce. The SMIs send this information to the ShopFloorConnect OEE monitoring software over your existing Ethernet. ShopFloorConnect logs the data from every machine, calculates the machines' OEE and other critical metrics, and makes the information available to you in real time.**

![The ShopFloorConnect OEE monitoring system tracks machine availability](/uploads/2020/04/15/statepie.jpg)

Our goal with ShopFloorConnect OEE software is to enable you to monitor OEE and machine efficiency with an absolute minimum of operator involvement or manual data entry.

In order to collect machine OEE status information automatically, a ShopFloorConnect Machine Interface (SMI 2) is installed on each machine in your facility. The ShopFloorConnect Machine Interface (SMI 2) features a touch-screen display that allows the machine operator to select downtime reasons and enter data. With just a few connections to the machine controller, the SMI 2 can detect when the machine is running, count cycles or parts (where applicable), and inhibit machine operation after a stoppage until the operator specifies a downtime reason.

The Machine Interface communicates over your existing Ethernet to the ShopFloorConnect OEE monitoring software running on your server. ShopFloorConnect constantly polls the machines, and logs all machine time into one of five different categories or “states”:

{% include snippets/icon-grid.html %}

## Downtime Identification for OEE

ShopFloorConnect allows you to create a list of downtime reasons specific to each machine. The list is sent down to the ShopFloorConnect Machine Interface (SMI) and appears as the Downtime Reason menu at the machine. When a running machine stops, the SMI instantaneously detects the transition, and changes the machine state from 'Running" to "Idle". If the operator immediately restarts the machine, the brief stoppage will be recorded as Idle time, which the OEE software regards as unplanned downtime. If the stoppage lasts for longer than a user-selectable time period (usually one minute), the SMI will disply the downtime reasonmenu and inhibit further machine operation until the operator selects an appropriate downtime reason. Once the reason is selected, ShopFloorConnect will 'backfill' the previous block of idle time with the downtime reason.

The ShopFloorConnect OEE software is unique in its ability to compare actual machine performance to part-specific ideal production rates to calculate the performance portion of the OEE metric. percent

    Production Tracking

ShopFloorConnect monitors the amount of time each machine spends in the various machine states, and also keeps an accurate parts count (where appropriate). In addition to making the information available in real time through the Factory Viewer, all of the information is available to the reporting interface to create downtime, production summary, OEE, and other reports.

![](/uploads/2021/01/20/smi-2-running.jpg)