---
layout: oee-monitoring-system
title: How ShopFloorConnect Monitors OEE
document_title: OEE calculation software | How to calculate OEE - ShopFloorConnect
permalink: "/oee-monitoring-system"
description: The ShopFloorConnect OEE monitoring software tracks machine availability
  for OEE by assigning time to specific machine states.
banner_bg_image: "/uploads/2021/10/21/bnr2.jpg"
monitors_oee_heading: How ShopFloorConnect Monitors OEE test
monitors_oee_details_para: The ShopFloorConnect Machine Interface (SMI 2) automatically
  detects when your machines are running, when they are stopped, and the number of
  parts they produce. The SMIs send this information to the ShopFloorConnect OEE monitoring
  software over your existing Ethernet. ShopFloorConnect logs the data from every
  machine, calculates the machines’ OEE and other critical metrics, and makes the
  information available to you in real time.
monitors_oee_details_para_1: Our goal with ShopFloorConnect OEE software is to enable
  you to monitor OEE and machine efficiency with an absolute minimum of operator involvement
  or manual data entry.
monitors_oee_details_para_2: In order to collect machine OEE status information automatically,
  a ShopFloorConnect Machine Interface (SMI 2) is installed on each machine in your
  facility. The ShopFloorConnect Machine Interface (SMI 2) features a touch-screen
  display that allows the machine operator to select downtime reasons and enter data.
  With just a few connections to the machine controller, the SMI 2 can detect when
  the machine is running, count cycles or parts (where applicable), and inhibit machine
  operation after a stoppage until the operator specifies a downtime reason.
monitors_oee_details_para_3: 'The Machine Interface communicates over your existing
  Ethernet to the ShopFloorConnect OEE monitoring software running on your server.
  ShopFloorConnect constantly polls the machines, and logs all machine time into one
  of five different categories or “states”:'
major_features_tabs_content:
- tab_content_title: Running Time
  tab_content_heading: Running Time
  tab_content_para_details: Running time is logged as 'Uptime', and means the machine
    is operating and making parts. The Running time becomes the basis for the Availability
    portion of the OEE calculation.
  tab_content_image: "/uploads/2021/10/21/running-bg.jpg"
- tab_content_title: Idle State
  tab_content_heading: Idle State
  tab_content_para_details: The Idle state indicates that the machine has stopped,
    but ShopFloorConnect does not (yet) know why. Idle time is converted to downtime
    or changeover when the machine operator selects a downtime reason. When OEE is
    calculated, any unconverted Idle time it treated as Unplanned Down.
  tab_content_image: "/uploads/2021/10/21/idle-bg.jpg"
- tab_content_title: Unplanned Downtime
  tab_content_para_details: The machine is stopped, the reason for the stoppage has
    been reported to ShopFloorConnect, and the reason had been previously assigned
    to the Unplanned downtime state. Unplanned downtime causes the OEE software to
    reduce the “Availability” percentage.
  tab_content_image: "/uploads/2021/10/21/down-bg.jpg"
  tab_content_heading: Unplanned Downtime
- tab_content_title: Planned Downtime
  tab_content_heading: Planned Downtime
  tab_content_para_details: The machine is stopped, the reason for the stoppage has
    been reported to ShopFloorConnect, and the reason had been previously assigned
    to the Planned Downtime state. Planned downtime logged by the OEE system DOES
    NOT affect the “Availability” calculation.
  tab_content_image: "/uploads/2021/10/21/planned-bg.jpg"
- tab_content_title: Changeover
  tab_content_heading: Changeover
  tab_content_para_details: The machine is stopped, the reason for the stoppage has
    been reported to ShopFloorConnect, and the reason had been previously assigned
    to the Changeover (Setup)state. The ShopFloorConnect OEE software allows the user
    to decide whether Changeover is logged as planned or unplanned downtime. When
    logged as unplanned downtime, the OEE software will reduce the availability percentage
    for any Changeover time logged by the system.
  tab_content_image: "/uploads/2021/10/21/changeover-bg.jpg"
expertise_content:
  expertise_small_heading: Expertise
  expertise_main_heading: Downtime Identification for OEE
  expertise_details_para_1: ShopFloorConnect allows you to create a list of downtime
    reasons specific to each machine. The list is sent down to the ShopFloorConnect
    Machine Interface (SMI) and appears as the Downtime Reason menu at the machine.
    When a running machine stops, the SMI instantaneously detects the transition,
    and changes the machine state from ‘Running” to “Idle”. If the operator immediately
    restarts the machine, the brief stoppage will be recorded as Idle time, which
    the OEE software regards as unplanned downtime. If the stoppage lasts for longer
    than a user-selectable time period (usually one minute), the SMI will disply the
    downtime reasonmenu and inhibit further machine operation until the operator selects
    an appropriate downtime reason. Once the reason is selected, ShopFloorConnect
    will ‘backfill’ the previous block of idle time with the downtime reason.
  expertise_details_para_2: The ShopFloorConnect OEE software is unique in its ability
    to compare actual machine performance to part-specific ideal production rates
    to calculate the performance portion of the OEE metric. percent.
  expertise_details_para_3: ShopFloorConnect monitors the amount of time each machine
    spends in the various machine states, and also keeps an accurate parts count (where
    appropriate). In addition to making the information available in real time through
    the Factory Viewer, all of the information is available to the reporting interface
    to create downtime, production summary, OEE, and other reports.
  expertise_image: "/uploads/2021/10/21/software-bg-new.png"
get_in_touch: Let's get in touch
get_in_touch_bold_para: Give us a call or drop by anytime, we endeavour to answer
  all enquiries within 24 hours on business days.
get_in_touch_large_para: By 700+ customers for 3200+ Web and Mobile App development
  projects.
what_you_will_get_heading: "& What you will get:"
what_you_will_get_para:
- what_you_will_para_details: Contrary to popular belief, Lorem Ipsum is not simply
- what_you_will_para_details: Random text. It has roots in a piece of classical Latin
    literature
- what_you_will_para_details: Latin professor at Hampden-Sydney College in Virginia
major_features_main_heading: Major Features
major_features_para: The ShopFloorConnect Machine interface major features are as
  follows
get_in_touch_bg: "/uploads/2021/10/20/bg1.jpg"
key_words:
- OEE monitoring
- OEE System
- OEE Software
menu:
  main:
    weight: 2
    parent: item_DsyKHj_
    identifier: item_yUad9TL

---
