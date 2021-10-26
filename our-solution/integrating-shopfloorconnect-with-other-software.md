---
title: Integrating ShopFloorConnect with Other Software
description: ShopFloorConnect features an Application Program Interface (API) that
  enables it to quickly and easily integrate with your other software.
document_title: Integrating ShopFloorConnect with Other Software | ShopFloorConnect
permalink: "/api-2"
key_words:
- integration
- API
- SAP
- Epicor
- JobBoss
menu:
  main:
    weight: 5
    parent: item_Bs8WyLo
    title: Integrating SFC with other software
    identifier: item__HG87is

---
There are several ways that ShopFloorConnect can automatically interact with your existing business software.

At the heart of ShopFloorConnect is the Microsoft SQL database - one of the most commonly used formats in the world. Once collected, any of the information in ShopFloorConnect's database is available to other systems, and can be directly accessed using any standard method - SQL queries, ASP, ODBC, etc.

![](/uploads/2020/09/02/sf-0090-graphic-final.png)
_ShopFloorConnect to 3rd Party Execution System Integration Block Diagram_

##### ShopFloorConnect API

ShopFloorConnect has an Application Program Interface (API) for sharing job information with other software. The ShopFloorConnect API is a web service-based two-way communication protocol that enables ShopFloorConnect to receive manufacturing job schedule information (such as job and part numbers, quantity of parts required, due dates, etc) from your ERP or MES software.

[ShopFloorConnect API Overview (White Paper - .PDF - 157K)](/uploads/2020/04/15/API_Summary.pdf)

As jobs are run and completed, ShopFloorConnect has an Event Notification Service that reports the results back to the ERP/MES software - including data such as job end time, number of good and scrap parts produced, etc.

The API enables your external software to add jobs, update job requirements, cancel jobs, or move jobs from one work center to another. The manufacturing schedule can be updated or even completely replaced by your ERP/MES software at any time, in real time.

We also feature CSV-to-API translator that enables you to update the ShopFloorConnect production schedule using [formatted .CSV files](/uploads/2020/04/15/CSV_API.pdf).