---
key_words:
- 'OEE calculation  '
- how to calculate OEE
layout: oee-calculation-design
title: OEE Calculation Improvements with ShopFloorConnect
document_title: OEE calculation software | How to calculate OEE - ShopFloorConnect
permalink: "/oee-calculation"
description: 'ShopFloorConnect software leverages the OEE calculation formula for
  production equipment to provide improved OEE measurement that factors in performance
  for specific parts. '
banner_bg_image: "/uploads/2021/10/22/bnr4.jpg"
oee_calculation_improvements:
  oee_calculation_improvements_main_heading: OEE Calculation Improvements with Shop
    Floor Connect
  oee_calculation_improvements_para: 'Traditional Overall Equipment Effectiveness
    (OEE) is a well-established method for tracking process efficiency. An OEE calculation
    is based on the formula:'
  oee_calculation_improvements_bold_text: Availability x Performance x Quality = OEE
  oee_calculation_improvements_para_2: It factors in those three variables and displays
    a simple percentage that shows the ratio of actual machine output to its theoretical
    maximum.
  how_traditional_oee_main_heading: How Traditional OEE is Calculated
  how_traditional_oee_small_heading: Traditional OEE Calculation Variables
calculation_variables:
- variables_main_heading: Availability
  variables_icon_class: flaticon-factory
  variables_para: Accounts for unplanned downtime losses. Availability It is equal
    to the actual machine/process running time divided by the total available time.
    Planned downtime events such as lunch breaks are not part of the OEE calculation.
- variables_main_heading: Performance
  variables_icon_class: flaticon-settings
  variables_para: Accounts for speed loss. Performance in the OEE calculation is equal
    to the ratio of number of parts produced over the measurement period (shift, day,
    etc) to the theoretical maximum number of parts that could be produced if the
    machine or process ran at its highest possible speed. This is called the Machine
    Ideal Rate.
- variables_main_heading: Quality
  variables_icon_class: flaticon-worker
  variables_para: In traditional OEE calculations, quality is the ratio of good parts
    to total parts produced.
calculation_improvements_images:
  calculation_improvements_top_image: "/uploads/2021/10/22/pic3-oee.jpg"
  how_traditional_first_row_image_1: "/uploads/2021/10/22/pic2.jpg"
  how_traditional_first_row_image_2: "/uploads/2021/10/22/pic3.jpg"
  how_traditional_second_row_image_1: "/uploads/2021/10/22/about2.jpg"
the_drawbacks:
  the_drawbacks_main_heading: The Drawbacks of “Traditional” OEE Calculations
  the_drawbacks_details_para: "<p>OEE calculations are based on the premise that all
    production losses on machines and processes can be measured and quantified.</p><p>But,
    traditional OEE calculations come up short in many applications. While the Availability
    and Quality metrics can be universally applied to all machine types, difficulty
    arises when the traditional Performance metric is applied to discrete manufacturing
    processes where the true “ideal production rate” is more dependent on the parts
    being manufactured than the machine itself.</p><p>Consider the following OEE Calculation
    example:</p><p>A machining center making ‘Part A’ produces 6 parts per hour. After
    a job change the same machine produces ‘Part B’ at a rate of 12 parts per hour.
    According to “traditional” OEE calculations, the “Part B’ is running at twice
    the efficiency of “Part A’. However, let’s say that under ideal circumstances,
    our machining center is actually capable of producing ‘Part A’ at a rate of 7
    parts per hour, and the much simpler “Part B” at 30 parts per hour.</p><p>In actuality,
    the machine was running at 86% efficiency while making Part A, and only 40% efficiency
    for Part B.</p><p>The errors inherent in traditional OEE calculations can be manually
    factored out on a job-by-job basis, but this task becomes extremely difficult
    when trying to summarize overall equipment effectiveness over a longer period
    of time. In addition, the calculations required to properly “weight” jobs of varying
    length become very complex.</p>"
how_shop_floor_cal_oee:
  how_calculates_oee_main_heading: How Shop Floor Connect Calculates OEE
  how_calculates_oee_details_para: "<p>Instead of using a single ideal performance
    rating for each machine, software calculates OEE by applying a specific ideal
    rate for each job segment/machine combination.</p><p>In applications where a machine
    must make more than one cycle to produce a part, ShopFloorConnect automatically
    divides the ideal rate by the number of cycles required to make the part.</p><p>The
    ShopFloorConnect system keeps a running total of the actual parts produced by
    the machine, as well as the number of parts that could have been produced according
    to the ideal rates and multipliers. This allows LETS to accurately summarize performance
    over time, regardless of the lengths of the jobs that ran in the machine. LETS
    automatically “weights” the percentages according to job length.</p>"
shopfloorconnect_oee_example:
  shopfloorconnect_oee_example_main_heading: 'ShopFloorConnect OEE Calculation Example:'
  shopfloorconnect_oee_example_details: "<p>During an 8-hour shift with 1/2 hour for
    lunch and two 15-minute breaks, a machine has a maximum availability of 7 hours
    (420 minutes). If there were 82 minutes of unplanned downtime during the shift,
    then the machine would’ve actually run for 338 minutes. The availability would
    be calculated as follows:</p><p>{% include snippets/icon-calculation-data-one.html
    %}</p><p>The second job (which ran for two hours) produced a part every 6 cycles
    of the machine. The Ideal Rate for this job was 50 cycles per minute. The theoretical
    maximum number of parts that could have been produced by this job was 1000; the
    machine produced 950.</p><p>The final job (which ran for one hour and 20 minutes)
    produced one part per cycle, with an ideal rate of 80 cycles per minute. The theoretical
    maximum number of parts that could have been produced by this job was 6400; the
    actual number of parts made was 5900.</p><p>During the 338 minutes of running
    time in our example, the machine could have theoretically made a total of 48,800
    parts for all jobs combined, but produced an actual total of 45,515. The performance
    percentage is calculated by dividing the actual number of parts by the theoretical
    maximum:</p><p>{% include snippets/icon-calculation-data-two.html %}</p><p>Out
    of the 45,515 parts produced, 830 had to be later scrapped. The quality percentage
    is the ratio of good parts to total parts, and is calculated as follows:</p><p>{%
    include snippets/icon-calculation-data-three.html %}</p><p>The ShopFloorConnect
    OEE calculation for this example is:</p><p>{% include snippets/icon-calculation-data-four.html
    %}</p><p>You can see that although the component measurements - 80% uptime at
    93% of maximum throughput with 98% quality - indicate a super-efficient process,
    when taken together as OEE, the process is really only 73% effective. ShopFloorConnect
    software provides a more realistic OEE calculation that reveals there is still
    room for improvement.</p>"
oee_calculation_improvements_last_heading: OEE Calculation Improvements with Shop
  Floor Connect
oee_calculation_improvements_last_details:
- oee_calculation_improvements_details_list: Make the most out of a limited amount
    of investment capital
- oee_calculation_improvements_details_list: Avoid making inappropriate equipment
    purchases
- oee_calculation_improvements_details_list: Free up capacity to better compete for
    new business
- oee_calculation_improvements_details_list: Quickly highlight the greatest areas
    of improvement to provide the greatest return on asset
- oee_calculation_improvements_details_list: Prioritize Lean initiatives
- oee_calculation_improvements_details_list: Decrease costs through waste elimination
- oee_calculation_improvements_details_list: Shorten equipment ROI through increased
    utilization
- oee_calculation_improvements_details_list: Reduce investigation time for root cause
    analysis
- oee_calculation_improvements_details_list: Directly tie production efficiencies
    to fiscal reporting
oee_calculation_improvements_contact_info: Learn more about improving overall equipment
  effectiveness by scheduling a demo of ShopFloorConnect or call 1-800-586-TECH (8324).
test_block:
- template: jumbotron
  jumbotrons:
  - jumbotron_subhead: ''
text_block_last: ''
menu:
  main:
    weight: 3
    parent: item_DsyKHj_
    title: How We Calculate OEE

---
