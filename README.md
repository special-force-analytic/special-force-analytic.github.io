Main

## Showcase of Data Analytics for E-commerce data

### Background
Talk a bit about O-list data set here.

O-list data Schema
![](https://i.imgur.com/HRhd2Y0.png)

### Customer analytics

#### Customer 360
Extract customer insights from multi-dimensional transactional data and meta-data to a single view of customer.

**Recency**
<br>
![](img/recency.png)
<br>

|       |   recency |
|:------|---------------------:|
| count |             2977     |
| mean  |              136.035 |
| std   |              163.83  |
| min   |                1     |
| 25%   |               19     |
| 50%   |               48     |
| 75%   |              212     |
| max   |              701     |

<br>

**Total orders**
<br>
![](img/total_orders.png)
<br>

|       |   total_order |
|:------|--------------:|
| count |     2977      |
| mean  |       33.2304 |
| std   |      106.595  |
| min   |        1      |
| 25%   |        2      |
| 50%   |        7      |
| 75%   |       22      |
| max   |     1844      |

<br>

**Days between orders**
<br>
![](img/days_between_orders.png)
<br>

|       |   days_btw_order |
|:------|-----------------:|
| count |      2977        |
| mean  |        79.5608   |
| std   |       127.415    |
| min   |         0.305857 |
| 25%   |        10.6429   |
| 50%   |        27.6      |
| 75%   |        83        |
| max   |       701        |

<br>

**Average monetary**
<br>
![](img/monetary_avg.png)
<br>

|       |   monetary_avg |
|:------|---------------:|
| count |       2977     |
| mean  |        195.698 |
| std   |        368.065 |
| min   |          6     |
| 25%   |         60.15  |
| 50%   |        105.337 |
| 75%   |        188.61  |
| max   |       6735     |

<br>

**Total monetary**
<br>
![](img/monetary_total.png)
<br>

|       |   monetary_sum |
|:------|---------------:|
| count |        2977    |
| mean  |        4491.85 |
| std   |       14070.8  |
| min   |           6.5  |
| 25%   |         219.8  |
| 50%   |         848.3  |
| 75%   |        3522    |
| max   |      229238    |

<br>

**Average quantity**
<br>
![](img/quantity_avg.png)
<br>

|       |   quantity_avg |
|:------|---------------:|
| count |    2977        |
| mean  |       1.15571  |
| std   |       0.442877 |
| min   |       1        |
| 25%   |       1        |
| 50%   |       1        |
| 75%   |       1.14286  |
| max   |      15        |

<br>

**Customer Single View**

|    | seller_id                        |   recency |   total_order |   age |       frequency |   days_btw_order |   monetary_avg |   monetary_sum |   quantity_avg |   total_categories | category_with_most_sales   |
|---:|:---------------------------------|---------------------:|--------------:|------:|-----------:|-----------------:|---------------:|---------------:|---------------:|--------:|:--------------------------------|
|  0 | 0015a82c2db000af6aaaf3ae2ecb0532 |                  321 |             3 |   343 | 0.00874636 |        114.333   |       895      |         2685   |        1       |       1 | small_appliances                |
|  1 | 001cca7ae9ae17fb1caed9dfb1094831 |                   54 |           200 |   577 | 0.34662    |          2.885   |       125.4    |        25080   |        1.195   |       2 | garden_tools                    |
|  2 | 002100f778ceb8431b7a1020ff7ab48f |                  145 |            51 |   355 | 0.143662   |          6.96078 |        24.2059 |         1234.5 |        1.07843 |       1 | furniture_decor                 |
|  3 | 003554e2dce176b5555353e4f3555ac8 |                  263 |             1 |   263 | 0.00380228 |        263       |       120      |          120   |        1       |       1 | na                              |
|  4 | 004c9cd9d87a3c30c522c48c4fc07416 |                  124 |           158 |   585 | 0.270085   |          3.70253 |       124.764  |        19712.7 |        1.07595 |       2 | bed_bath_table                  |

<br>

#### Customer segmentation
Segment customers based on the extracted insights. Customised treatment could be applied to each customers segment to maximised your business outcome.

**Segment profile**
- 0 : Rising star
- 1 : X potential customer - (large basket / small volume)
- 2 : Highest value sellers (small basket/ large volume)
- 3 : Inactive

![](img/segmentation_1.png)
![](img/segmentation_2.png)
![](img/segmentation_3.png)
![](img/segmentation_4.png)
![](img/segmentation_5.png)
![](img/segmentation_6.png)
![](img/segmentation_7.png)

## TEST

| **var** | **let** | **const** |
|-----|-----|-----|
| Declares a variable, optionally initializing it to a value. | Declares a block-scoped, local variable, optionally initializing it to a value. | Declares a block-scoped, read-only named constant. |
| Variable declared by **`var`** must start with a letter, underscore ( _ ) or dollar sign ($) and can contain alphabetic, numeric, or underscore characters. | Variable declared by **`let`** must start with a letter, underscore ( _ ) or dollar sign ($) and can contain alphabetic, numeric, or underscore characters. | Variable declared by **`const`** must start with a letter, underscore ( _ ) or dollar sign ($) and can contain alphabetic, numeric, or underscore characters. |