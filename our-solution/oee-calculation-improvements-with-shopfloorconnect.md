---
title: OEE Calculation Improvements with ShopFloorConnect
description: 'ShopFloorConnect software leverages the OEE calculation formula for
  production equipment to provide improved OEE measurement that factors in performance
  for specific parts. '
document_title: OEE calculation software | How to calculate OEE - ShopFloorConnect
permalink: "/oee-calculation-old"
key_words:
- OEE calculation
- how to calculate OEE
menu:
  main:
    weight: 3
    parent: item_DsyKHj_
    title: How we Calculate OEE
    identifier: item_4gQ4kQy

---
Traditional Overall Equipment Effectiveness (OEE) is a well-established method for tracking process efficiency. An OEE calculation is based on the formula:

**Availability x Performance x Quality = OEE**  
It factors in those three variables and displays a simple percentage that shows the ratio of actual machine output to its theoretical maximum.

![OEE = Availability x Performance x Quality](/uploads/2020/04/15/calculating-oee.png)

## How Traditional OEE is Calculated

##### Traditional OEE Calculation Variables

1. Availability: Accounts for unplanned downtime losses. Availability It is equal to the actual machine/process running time divided by the total available time. Planned downtime events such as lunch breaks are not part of the OEE calculation.
2. Performance: Accounts for speed loss. Performance in the OEE calculation is equal to the ratio of number of parts produced over the measurement period (shift, day, etc) to the theoretical maximum number of parts that could be produced if the machine or process ran at its highest possible speed. This is called the Machine Ideal Rate.
3. Quality: In traditional OEE calculations, quality is the ratio of good parts to total parts produced.

##### The Drawbacks of "Traditional" OEE Calculations

OEE calculations are based on the premise that all production losses on machines and processes can be measured and quantified.

But, traditional OEE calculations come up short in many applications. While the Availability and Quality metrics can be universally applied to all machine types, difficulty arises when the traditional Performance metric is applied to discrete manufacturing processes where the true “ideal production rate” is more dependent on the parts being manufactured than the machine itself.

Consider the following OEE Calculation example:

A machining center making 'Part A' produces 6 parts per hour. After a job change the same machine produces 'Part B' at a rate of 12 parts per hour. According to "traditional" OEE calculations, the “Part B' is running at twice the efficiency of “Part A'. However, let's say that under ideal circumstances, our machining center is actually capable of producing 'Part A' at a rate of 7 parts per hour, and the much simpler "Part B" at 30 parts per hour.

In actuality, the machine was running at 86% efficiency while making Part A, and only 40% efficiency for Part B.

The errors inherent in traditional OEE calculations can be manually factored out on a job-by-job basis, but this task becomes extremely difficult when trying to summarize overall equipment effectiveness over a longer period of time. In addition, the calculations required to properly "weight" jobs of varying length become very complex.

##### How ShopFloorConnect Calculates OEE

Instead of using a single ideal performance rating for each machine, software calculates OEE by applying a specific ideal rate for each job segment/machine combination.

In applications where a machine must make more than one cycle to produce a part, ShopFloorConnect automatically divides the ideal rate by the number of cycles required to make the part.

The ShopFloorConnect system keeps a running total of the actual parts produced by the machine, as well as the number of parts that _could have been_ produced according to the ideal rates and multipliers. This allows LETS to accurately summarize performance over time, regardless of the lengths of the jobs that ran in the machine. LETS automatically "weights" the percentages according to job length.

## ShopFloorConnect OEE Calculation Example:

During an 8-hour shift with 1/2 hour for lunch and two 15-minute breaks, a machine has a maximum availability of 7 hours (420 minutes). If there were 82 minutes of unplanned downtime during the shift, then the machine would've actually run for 338 minutes. The availability would be calculated as follows:

**Availability = 338 minutes / 420 minutes = 80%**

Running at full speed, the machine is capable of producing 6000 parts/hour (or 100 parts per minute). However, the three jobs that ran during this shift were not designed to run at the machine's maximum speed. The first job (which ran for 2 hours and 18 minutes) produced 4 parts per cycle. This job's Ideal Rate is 75 cycles per minute. The theoretical maximum number of parts that could have been produced by this job was 41,400. The machine actually made 38,665.

The second job (which ran for two hours) produced a part every 6 cycles of the machine. The Ideal Rate for this job was 50 cycles per minute. The theoretical maximum number of parts that could have been produced by this job was 1000; the machine produced 950.

The final job (which ran for one hour and 20 minutes) produced one part per cycle, with an ideal rate of 80 cycles per minute. The theoretical maximum number of parts that could have been produced by this job was 6400; the actual number of parts made was 5900.

During the 338 minutes of running time in our example, the machine could have theoretically made a total of 48,800 parts for all jobs combined, but produced an actual total of 45,515. The performance percentage is calculated by dividing the actual number of parts by the theoretical maximum:

**Performance = 45,515 actual parts / 48, 800 possible parts = 93%**

Out of the 45,515 parts produced, 830 had to be later scrapped. The quality percentage is the ratio of good parts to total parts, and is calculated as follows:

**Quality = 44,685 Good Parts / 45,515 Total Parts = 98%**

The ShopFloorConnect OEE calculation for this example is:

**Availability (80%) x Performance (93%) x Quality (98%) = 73%**

You can see that although the component measurements - 80% uptime at 93% of maximum throughput with 98% quality - indicate a super-efficient process, when taken together as OEE, the process is really only 73% effective. ShopFloorConnect software provides a more realistic OEE calculation that reveals there is still room for improvement.

***

##### Why use the ShopFloorConnect system for OEE calculations?

* Make the most out of a limited amount of investment capital
* Avoid making inappropriate equipment purchases
* Free up capacity to better compete for new business
* Quickly highlight the greatest areas of improvement to provide the greatest return on asset
* Prioritize Lean initiatives
* Decrease costs through waste elimination
* Shorten equipment ROI through increased utilization
* Reduce investigation time for root cause analysis
* Directly tie production efficiencies to fiscal reporting

Learn more about improving overall equipment effectiveness by [scheduling a demo of ShopFloorConnect](/contact/schedule-a-demo.html) or call 1-800-586-TECH (8324).