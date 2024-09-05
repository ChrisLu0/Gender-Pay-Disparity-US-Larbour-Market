# Explorer: Gender Disparities in the US Labor Market

<img width="451" alt="image" src="https://github.com/ChrisLu0/DataVis/assets/145377410/58763357-698a-4c6a-b79e-518145eb575f">

Link to the interactive visualization: [link](https://vega.github.io/editor/?#/url/vega-lite/N4IgJAzgxgFgpgWwIYgFwhgF0wBwqgegIDc4BzJAOjIEtMYBXAI0poHsDp5kTykBaADZ04JAKyUAVhDYA7EABoQAEySYUqUAwBOgtBmx5CBbUgDu1OoyYMIcbVDmY4szJUcITAMzbbV66BoXKFFMGmUAT0wGOAhVCIJkCGdtAn8kAgAmAAYARgBOLLz8-myAZlKxAkk2JggAfTIXZXt3CGJFEB9tZEw0UEwInDh9KHaQAF8JpTDMQRHNEGcADz70AFFlnEFfe1QAAgBxZvt95RoIHCRtOiCIfZpZffo4fYBVAGV9wSQmX33kNoANZwPpKJCyWC+fQIcLKeadHyuD40ABeCxy0xAxEckLUaAA2qBcVB8agiSAzOF6GhcmJskp4DQyFg0PSGSArqYEBBCaBZEgEAtOWxHmCQHZ5lA1gMhsKcKLXIigoJlLzySBkDVtPVSc4yL4IiAALpYpiPZT6eZNWSWibGpSAoH9JZy-RMa6dRzaWT2ABKSHOtnWtrQAHYscE2OdZGQXUbFl4VZb0LDZL5dWpyIbOoNhvp02mkHoZnQEahZAxBIJwcsLi7ZvMAGJOFHo2kAFiUPyYcEELeRaIWAA4sTJtDKusn9MMHC5MPUvIhiyMlGwcDC4OcIZ1fC1tPoWtBmo841MlMsXUm+ynOfYQq5F8uETM3egAI4MCGzNQ0UidJAyDIbQ+GcTdt3kJRoBXF1lDYZBHkJBlcmybJTVLOZhSbZ9XgABWuMIoBoK4wjkfYAAokHuJB9gAUn2NgvGeNh1EEfYzF8IFuhCABKAC63VAYyzgAdMDbBZci7EAez7UTxNpTJzyWNg2EEMIN0WQDgNA4UhQg5Ubxne95yfZAX1dfMPy-Vw6F-f8sUcHYD0WXFzlI+RFi5QUZ0VcVr1VGEkG1TN9RzV9LJAQtHmLXNhP0ABZIL-gAYSzA1tAifYmxoNT7E6aDy1ALhEGFJAoAfPosWtZoXV8IIlXQeYvHFRsRNbIcFKgiIED+QQABU3wlT9rlXaTflk9r21QYdu3GwQABkaFhNYcmyJTiGLGIrWZLBtKNKZplAKllBpVA6Q5JkWTWdlHWuZ1FjzYUPQPJRvV9bQAyDCAQxTCMlCjGM40WS9E2ndAzEAuB6lnCr6kY+ozNGx79GGmz1DCf9wSAkCKDA1MtxoHcMPLEBsMR9jIYoqj9ho+jGP2RL5gAcggPja3rB7hLkjqzqkmT+0miTFKxBNQH8280wzPVswy3NBqigUSwlXxJ3F-QIaaaHjMfeHEd3DTNQJomQD3PL0CPB9AcmYmFkrat2cEpYucFztZt7AXBym0csUwFS1OIl0tJxrNwMJyCp0M8HIa1ucda8BGYPC4VUZ-DGRgc1ToRcuQ3PYDzQC8hAfLFAyAtTJKdWl9KjSTgt4OivQsQ2wQtsanbMD2yYpnQo7qRgNAADZUMZOB27QMph81O7i6Vf7IWjU8XRBsWwbvWOFyXPXa6s79bLT-iOaEzD9DJld9i5QjiN-MjKOouiGKY33WPYzjuLgPilNFiOy8paOYZM3WicLLJ2sqnP8o0kACQbHFdAp95gUyaFTO+dMmKMzgCzD+GcnIulcrcOQLpC4zz8qvLUUs0phWAXXIsjclDN1biATuB0FC9xOv3VAQ8LqjyurSSemBTCyAgN0Iu5IV65WcgXa43l0AKhLt3WaEQzYUidA2Qaz0vSZ2cgwkC+056OCtsDK8q8n7FnqHAa4shTwNC3iAc0+cp7LFseqCen9A7Yx0qMNgDAlRYnXGVOgX86ELGyJQMQTDQDKIeqoz0r0NH6AUdWNgZhrYgABovAxoNI7KVYqY8xljTJANsS6ZADjHjqkxA7aBx9YE4RpraBmZ8ADqnFTgAEFZCVmLPsdYuTYz3AACIXD4TQGw7l9jJXglyC4chyKfDADxfY-B9gAE0+w7DMAcOBrwCBHG0QcNBXclBfyDu49AjgvGVTXFcIigwXSBLQME0J3d7QTCAA/view)

## Dataset Overview

This is an adaptation of the "jobs_gender.csv" dataset, part of the “TidyTuesday” project, containing information on gender representation in various job categories in the United States. The dataset was originally compiled by the US Bureau of Labor Statistics (BLS) and was cleaned and formatted by the “TidyTuesday” team. It contains data for 24 job categories, such as "Computer and Mathematical," "Education, Training, and Library," and "Construction and Extraction," among others. For each category, the dataset provides the total number of workers, the number of male workers, the number of female workers, and the median weekly earnings for both genders. The dataset also includes a calculated field, "wage_percent_of_male," representing the median weekly earnings of female workers as a percentage of male workers' median weekly earnings. This dataset can be used to explore gender disparities in the labor market across various job categories and to analyze the wage gap between male and female workers.

## Design Considerations

### Overall Goal

My overall goal with this tool was to enable the exploration of female participation, the female earning gap (compared to male), and earning distribution differences between female and male in the US workforce by different occupation categories.

### Bar Chart 1 (Top Left)

This bar chart displays the percentage of women in each minor job category within major occupation groups, sorted by the median percentage of female participation rates. The encoding allows for a comparison of gender disparities in the labor market across different minor job categories. The color of the bars represents the selected major job category.

An alternative visualization could be a heatmap, with minor job categories on one axis and major job categories on the other. The cells of the heatmap could be colored based on the percentage of women in that category, allowing for quick comparison of gender disparities across different minor job categories within a major category. However, the bar chart format is more effective for identifying the magnitude of gender gaps between categories.

### Bar Chart 2 (Top Right)

This second horizontal bar shows the percentage of female wages relative to male wages for different (major) occupation groups. It is sorted by the median percentage of female wages relative to male wages. Its color scheme is the same as the first bar chart.

The attribute this table used is “wage_percent_of_male,” which contains many missing data. So in the “aggregate” part of encoding, I chose “median” instead of “mean” to avoid errors in data calculation.

Similarly, its alternative could be a heatmap that uses minor job categories on one axis and major job categories on the other axis. Yet, the bar chart format is still more effective for identifying the magnitude of gender gaps.

### Scatterplot

The third chart is a scatter plot that shows the relationship between the percentage of female participation and the percentage of female wages relative to male wages for each minor job category. Each circle represents an observation point. The color of the circles is determined by the major job category, using the same color scheme as in the first two charts.

I initially wished to reveal the correlation between the percentage of female participation and the percentage of female wages relative to male wages for each minor job category, but there seems to be no strong correlation between the two variables.

### Histogram

This is a histogram that compares the distributions of annual earnings between male and female workers in the selected minor job category. The x-axis represents the total earnings, and the y-axis represents the count of workers in each bin. To emphasize the female part visually, and to avoid stereotypical coloring (pink for female / blue for male), the male earnings are displayed as grey bars, and the female earnings are displayed as yellow bars. The advantage of this histogram is that it’s clear to see the earnings distribution of females and males. We can easily compare which gender group is better paid overall in any occupation category.

### Interaction Consideration

This visualization provides a major occupation category filter selection interaction that enables users to filter and highlight data by selecting specific categories from the legend. This allows users to focus on specific job categories of interest and compare them more easily. However, this interaction may have limitations if users want to compare multiple categories simultaneously.

Tooltips are also available, providing precise numerical values when hovering over the bars.

An improvement to the interaction could be the addition of a brush selection tool to the histogram. This would allow users to select an interval of the histogram and view more detailed data for that earning interval, providing additional insights into the distribution of data (e.g. what occupation has the least female participation in the earning range from 70000 to 90000?).
