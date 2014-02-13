# Problem 5 Answers

1. The chart isn't usable in its current form. We don't have a title, or axis labels, so we don't really know what we're looking at. Furthermore we don't have a scale for the for the chart.

2. The most outer <code>g</code> element is the first entire svg object and its purpose in this bar graph is to translate the entire graph to add a left and upper margin so we don't have a graph that starts at the upper-left corner of the screen. The second <code>g</code> element is for the title of the graph which doesn't currently exist. The final <code>g</code> elements are each individual bar, which in this case are rectangle objects.

3. Appending the text or the rect elements first will vary which one appears on top. In other words if we append the text and then the rect objects, the rect will appear over the text covering it up. So we want to append the text after the rect objects so the bars have textoverlaying them rather than the other way around.