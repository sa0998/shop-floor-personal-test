---
key_words: []
layout: ''
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
  how_traditional_oee_main_heading: It factors in those three variables and displays
    a simple percentage that shows the ratio of actual machine output to its theoretical
    maximum.
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
  shopfloorconnect_oee_example_details: |-
    <p>During an 8-hour shift with 1/2 hour for lunch and two 15-minute breaks, a machine has a maximum availability of 7 hours (420 minutes). If there were 82 minutes of unplanned downtime during the shift, then the machine would’ve actually run for 338 minutes. The availability would be calculated as follows:</p><pre><code>&lt;div class="row widget widget_getintuch widget_getintuch-pro-details m-lr0 custom-oee-sa"&gt;
        &lt;div class="col-xl-12 col-lg-12 col-md-12 col-sm-12 p-lr0"&gt;
            &lt;div class="pro-details"&gt;
                &lt;i class="ti ti-user"&gt;&lt;/i&gt;
                &lt;strong&gt;Availability = 338 minutes / 420 minutes = 80%&lt;/strong&gt;
            &lt;/div&gt;
        &lt;/div&gt;
    &lt;/div&gt;</code></pre>
oee_calculation_improvements_last_heading: ''
oee_calculation_improvements_last_details: []
oee_calculation_improvements_contact_info: ''

---
