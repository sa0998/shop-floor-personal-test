---
title: Data Collection Examples
description: The ShopFloorConnect Machine Interface can track important efficiency
  metrics from any machine.  Here are some examples.
document_title: Machine Data Collection Examples - ShopFloorConnect
permalink: "/machines"
key_words:
- OEE calculation
- how to calculate OEE

---
The [ShopFloorConnect Machine Interface (SMI)](/machine-monitoring-interface.html) can be easily adapted to any machine. The ShopFloorConnect Machine Interface (SMI) has been specifically designed to require only the most basic of input signals from the machine to which it is connected. To calculate Overall Equipment Effectiveness (OEE), the SMI needs only to know whether or not the machine is running, and when it has made a cycle.

As a result, the SMI has been successfully installed on a wide variety of production equipment - from very simple machines to sophisticated manufacturing cells. Here are some examples of machines connected to ShopFloorConnect.

##### Machining Center

![Machining Center](/uploads/2020/04/15/samplemachine.jpg)

ShopFloorConnect tracks production rate and efficiency by part number, and automatically generates a production summary report after each shift.

The [SMI](/machine-monitoring-interface.html) receives its "Running" input from the coolant pump signal (which is only "ON" while the machine is cutting), while its "Inhibit" output is connected to the door interlock.

##### Packaging Machine

![Machining Center](/uploads/2020/04/15/samplemachine.jpg)

ShopFloorConnect measures uptime and downtime by SKU number, provides 'downtime by product type' reports, and automatically logs stoppages initiated by downstream equipment.

The [SMI](/machine-monitoring-interface.html) receives its "Cycles" signal from a sensor on the sealing platen, while its "Inhibit" output is connected to the weighing scale error interlock.

##### Metal Cutting Laser

![](/uploads/2020/04/15/laser.jpg)

ShopFloorConnect tracks uptime and downtime by material type (providing a monthly 'downtime by material' report), and tracks the number of sheets consumed by the laser.

The [SMI](/machine-monitoring-interface.html) receives its "Running" input by 'stealing' a signal from the "On" lamp on the laser's controller. The cycles input for is provided by the sheet feeder, and the inhibit output uses a spare interlock.

##### Industrial Saw

![](/uploads/2020/04/15/saw.jpg)

ShopFloorConnect collects downtime reasons and sorts them by material inventory number. It's also able to track the running hours on the saw blade to aid in maintenance.

The "Running" input is connected to the signal that starts the coolant pump. The "Inhibit" output is connected to a spare interlock.

##### Metal Stamping Press

![](/uploads/2020/04/15/press.jpg)

ShopFloorConnect tracks OEE by tool number, as well as the number of hits on each die for tooling maintenance purposes. ShopFloorConnect also graphs machine tonnage and stopping time over time.

The [SMI](/machine-monitoring-interface.html) receives its "Cycles" input from a programmable limit switch signal, while the "Inhibit" output is connected directly into the E-stop circuit.

##### Powder Coat Line

![](/uploads/2020/04/15/paint.jpg)

ShopFloorConnect tracks uptime efficiency of the line, and graphs the conveyor speed over time.

The [SMI](/machine-monitoring-interface.html) receives its "Running" input from a sensor that is retriggered by the moving conveyor. The same sensor enables the ShopFloorConnect Machine Interface to track the line speed.

##### Press Brake

![](/uploads/2020/04/15/brake.jpg)

ShopFloorConnect monitors efficiency by part and by operator. For parts requiring multiple bends, the [SMI](/machine-monitoring-interface.html) applies a multiplier to maintain an accurate parts count.

The [SMI](/machine-monitoring-interface.html) receives its "Cycles" signal from the press brake controller. its "Inhibit" output is connected to the stop circuit.

##### Robot Welder

![](/uploads/2020/04/15/welder.jpg)

ShopFloorConnect collects downtime by assembly number, and tracks the number of cycles on each welding fixture for maintenance.

The [SMI](/machine-monitoring-interface.html) receives its "Running" signal from the controller, and its "Inhibit" output is connected in series to the stop button.

##### Automated Shear

![](/uploads/2020/04/15/shear.jpg)

ShopFloorConnect tracks uptime and downtime by material type and tracks the number of sheets cut by the shear.

The [SMI](/machine-monitoring-interface.html) receives its "Running" signal from the controller; its "Inhibit" output is connected to a spare interlock.

##### Turret Press

![](/uploads/2020/04/15/turret.jpg)

ShopFloorConnect tracks uptime and downtime by material type (providing a monthly 'downtime by material' report), and tracks the number of sheets processed by the machine.

The [SMI](/machine-monitoring-interface.html) receives its "Running" signal from the controller; its "Inhibit" output is connected to the door interlock.

##### Injection Molding Machine

![](/uploads/2020/04/15/injection.jpg)

ShopFloorConnect tracks Overall Equipment Effectiveness (OEE) and automatically generates a daily OEE report sorted by part number.

ShopFloorConnect also tracks the number of cycles on each mold, and provides an indication whenever a mold reaches its maintenance interval.

##### Custom Machinery

![](/uploads/2020/04/15/custom.jpg)

The ShopFloorConnect machine Interface can be easily adapted to your custom machinery.