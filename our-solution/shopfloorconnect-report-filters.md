---
title: ShopFloorConnect Report Filters
description:
  ShopFloorConnect software leverages the OEE calculation formula for production
  equipment to provide improved OEE measurement that factors in performance for specific
  parts.
document_title: Report Filters | ShopFloorConnect
permalink: "/reportfilters"
key_words:
  - OEE calculation
  - how to calculate OEE
---

ShopFloorConnect's report templates can be easily adjusted to vary the report content using the 'filters' available on each template. The filters are user-configurable menu settings that control the information that will be contained in the report. Items such as the time period for the report, as well as which machines, operators, and parts numbers to include can be specified using the filters. Each template also features Delivery Filters to control the report file format and delivery schedule.

To create a report, simply make a copy of a template (this copy is called a "linked report") and adjust the filter settings to meet your content, format, and delivery requirements. The filters are described below:

##### Date Range Filters

The date Range filters are used to specify the time period covered by the report. With ShopFloorConnect, you have the ability to apply either a fixed or relative date range to the information contained in the report.

The relative date ranges (_shown below_) should be used for any automatically distributed report set up for recurring delivery on a preset schedule. For example, if you set up a Production Summary report for delivery via email every Monday morning to show the previous week's output, you would use the relative range of "Previous Week".

![](/uploads/2020/04/15/relative_range.jpg)
_Relative Range Filters_

The relative range filters are also useful for automatically distributed "visual factory" reports designed to be displayed on large format displays around the factory.

Fixed date ranges (\_shown below)\_are useful for specific data analysis tasks - For example, to view a machine's OEE for a three month period before and after a making a significant improvement.

![](/uploads/2020/04/15/fixed_date_range.jpg)
_Fixed Date Range Filters_

##### Machine, Primary, and Operator Filters

Many of the reports allow you to specify which machine types, specific machines, areas, operators, and primary items (like part, SKU, or tool number) to include in the report. These filters allow for multiple selections, and can be used in conjunction with each other to give you the ability to focus only on specific items. For example, you can create a report to show the downtime for three machines, while they're making a particular family of parts, being run by a specific operator on third shift.

##### Delivery Filters

All ShopFloorConnect reports share a common set of delivery filters. These filters determine where, how, and to whom the report is delivered, as well as the file format and name of the report, and the time schedule for report generation and distribution. These filters are saved with each report; so once they are set up, the delivery will occur automatically.

Hover over the image below for a description of each filter.

![](/uploads/2020/04/15/deliverAsMenu.jpg)

The **"Deliver As"** selection defines how the report will be delivered.

![](/uploads/2020/04/15/filetypemenu.jpg)

The **"File Type"** menu allows you to select the file format for the delivered report

The **"Delivery Schedule"** menu enables you to specify the report delivery time, as well as the frequency at which the report will be delivered.

You can create as many schedules as you need, and they will automatically be added to this menu. All delivery schedules are available for use by any report.

The **"Delivery Email/Groups"** section is used to select the delivery address (or addresses) for any reports that will be delivered as an email attachment or email body text.

![](/uploads/2020/04/15/deliveryName.jpg)

The **"Delivery Name Format"** filter allows you to select a naming convention for the report file.

Each report features buttons to allow you to save the filter settings, and to view a preview of the report.
