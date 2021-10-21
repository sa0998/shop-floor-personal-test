---
layout: oee-monitoring-system
title: How ShopFloorConnect Monitors OEE
document_title: OEE calculation software | How to calculate OEE - ShopFloorConnect
permalink: "/oee-monitoring-system"
description: The ShopFloorConnect OEE monitoring software tracks machine availability
  for OEE by assigning time to specific machine states.
banner_bg_image: "/uploads/2021/10/21/bnr2.jpg"
monitors_oee_heading: How ShopFloorConnect Monitors OEE
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
  expertise_small_heading: ''
  expertise_main_heading: ''
  expertise_details_para_1: ''
  expertise_details_para_2: ''
  expertise_details_para_3: ''
  expertise_image: ''
get_in_touch: ''
get_in_touch_bold_para: ''
get_in_touch_large_para: ''
what_you_will_get_heading: ''
what_you_will_get_para: []

---
