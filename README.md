# Investigating and visualizing earnings, employability, and gender differences between Uni Majors.

Employment Rates and mean salaries associated with various college majors in US Universities were analyzed to understand the relationship between those factors and each major. Additionally, some secondary analysis on gender proportion changes over the year for some majors was also visualized. 

## 1) [Investigating earnings by Major](https://github.com/SphericalCopper/Investigating-and-visualizing-earnings-employability-and-gender-differences-in-Uni-Majors/blob/master/Investigating%20Earnings%20by%20College%20Major.ipynb)

The dataset used was available from FiveThirtyEight's [GitHub repository](https://github.com/fivethirtyeight/data/tree/master/college-majors)

Based on the dataset, visualizations such as scatter plots, histograms, and bar plots will be used to gain insight into matters such as:

- Do students in more popular majors make more money?
- How many majors are predominantly male or female?
- Which category of majors have the most students?

Some of the metrics of interest were:

- Unemployment Rates
- Median Salaries
- No. of students in each Major
- Gender

Various scatter plots were made comparing the correlation of the metrics.

A scatter matrix was also constructed where the relationship of class size, median salary, and unemployment rates were visualized together:

![scatter matrix](https://i.gyazo.com/2c2748781897a4bd2b93bd1016081276.png)

To a degree, more popular majors seemed to have higher Median Salaries. However, this wa only true until about $65,000. After that point, an increase in Median Salary doesn't necessarily mean that that course was more popular among students. This could be because majors with high Median salaries were very difficult to get into, thus some of those courses had fewer students.

Bar plots were also used to visualize the unemployment in a handful of engineering majors:

![unemployment](https://i.gyazo.com/6a3bf5d99e37cbe48cd657d1cc754a15.png)

In general, we observed that unemployment rates for Engineering-related majors is very low. The exception is the field of Nuclear Engineering, with an unemployment rate of almost 20%. This significantly stands out against the other Engineering fields that have an unemployment rate of on average 5-10% or less. This could be because the demand for Nuclear Engineers is much lower than the amount of Nuclear Engineers available, making it an extremely competitive job market.


## 2) [Visualizing gender differences by Major over the years](https://github.com/SphericalCopper/Investigating-and-visualizing-earnings-employability-and-gender-differences-in-Uni-Majors/blob/master/Visualizing%2BGender%2BGap%2Bchanges%2Bin%2BUni%2Bmajors.ipynb)

Changes in gender proportions in a handful of majors over the years, starting from 1970, were visualized together in a figure, after a process of optimizing the way the graphs appeared together:

![gender changes1](https://i.gyazo.com/0678c9ca5fb0e40c84ba46a5f139925d.png)

![gender changes2](https://i.gyazo.com/94a1cb4909666f6a514f0e8e4eed2f23.png)

The first column contains STEM majors, the 2nd column contains Liberal Arts majors, and the 3rd contains a mixed sample of majors that were broadly categorized as "Others" in the project.
