## Antarctica - a project during studies as part of the "Modeling in Earth Sciences" course.

The aim of the analysis is to create a GIF animation illustrating three components:
- The minimal range of ice
- The actual extent of ice (Based on the data, [daily_ice_edge](https://github.com/filiphalys02/Antarktyda/blob/main/daily_ice_edge.csv))
- The mathematically modeled extent of ice. The model is created iteratively using trigonometric functions. It depends on the minimum range of ice (it does not exceed it).

Each iteration consists of the aforementioned elements represented as lines plotted on a polar coordinate system.

#
The imported data represents the extent of ice as degrees of latitude for all 360 angles of longitude. Each record in the data is assigned a date (Temporal coverage of the data: 1978-2009).
#
Due to hardware limitations, iterations were not performed on all rows of data. For visualization purposes, the first and last 500 iterations were exported:

- ![FIRST 500 ITERATIONS](https://github.com/filiphalys02/Antarktyda/blob/main/animation_first_500_iterations.gif)

- ![LAST 500 ITERATIONS](https://github.com/filiphalys02/Antarktyda/blob/main/animation_last_500_iterations.gif)




