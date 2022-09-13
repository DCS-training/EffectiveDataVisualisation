# Introduction

## Good Visualisations
The human brain processes visual information quicker than it processes text — so using charts, graphs, etc. can help provide an immediate understanding of the story behind the data.

Data presented as text can be confusing (and boring), whereas data represented in a visual format can help people extract meaning from that information more quickly and easily. Data visualization allows you to expose patterns, trends, and correlations that may otherwise go undetected.

### Principles to adhere to

1.  Use the right graph for your data
2.  Use colour wisely
3.  Be accurate and transparent
4.  Get rid of clutter
5.  Provide a clear take-home message


#### 1. Using the right graph

Here is an example of where a line chart has been used to illustrate different expenses cost by department. Line graphs are best used to illustrate a series, or a trend and this graph is fairly confusing.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/Image1.png)


However, if a barchart had been used it would be immediately clear what is being demonstrated is a comparison in spending between departments.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/Image2.png)


#### 2. Using colour wisely

The color palette used in the chart below is not at all helpful. The difference between “None”, i.e. no cases and “10,001 or more” cases is huge (at least 10,001 to be precise). But the colour representation is virtually identical.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/Image3.png)

The following chart is much easier to understand. A limited colour palette and a clear separation between categories makes it much more effective.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/Image4.png)


#### 3. Be accurate and transparent

As a rule, the Y axis of a bar graph needs to start at zero. When that is the case, as in the chart below, any difference illustrated is relative. However, the use of female figures suggests that the difference is absolute giving the impression that Latvian women are 10 times the height of Indian women.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/Image5.png)

The misleading impression in the previous example is almost certainly accidental whereas the following example is probably deliberately misleading. The chart's Y-axis mysteriously begins at 58 per cent, and ends at 78 per cent. Thus, a 15 per cent drop is made to look more like a 70 per cent one. This exaggeration helps to bolster Fox News/Tucker Carlson's 'Replacement Theory', i.e. that traditional American society is being diluted by successive waves of immigrants.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/Image6.png)


#### 4. Get rid of clutter

I'm sure there is important information in the following chart but it is almost impossible to decipher.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/Image7.png)


#### 5.Provide a clear take-home message

The following chart provides an easily understood message, that over time, without the implementation of protective measures healthcare systems would be overwhelmed by the spread of Covid-19.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image8.jpg)


##  Using Excel 

### Excel Column Chart

Column charts are used to compare values across categories by using vertical bars.

Download the [Wildlife spreadsheet](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/wildlife.xlsx) and open in Excel.

To create a  **column chart**, execute the following steps.

1. Select the range A1:A7, hold down CTRL, and select the range C1:D7.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image9.png)

2. Click Insert from the top menu, then in the Charts group, click the Column symbol.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image11.png)

3. Click Clustered Column.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image12.png)

**Result**

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image13.png)

*Note*: if you have numeric labels, empty cell A1 before you create the column chart. By doing this, Excel does not recognize the numbers in column A as a data series and automatically places these numbers on the horizontal (category) axis. After creating the chart, you can enter the text Year into cell A1 if you like.


### Excel Line Chart

Excel is capable of generating various chart types, and as data is often stored in an Excel spreadsheet this is often an easy way to create a visualization

Download the [Wildlife spreadsheet](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/wildlife.xlsx) and open in Excel.

To create a line chart, execute the following steps.

1. Select the range A1:D7.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image14.png)

2. On the Insert tab, in the Charts group, click the Line symbol.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image15.png)

3. Click Line with Markers.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image16.png)

**Result:**

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image17.png)

*Note*: enter a title by clicking on Chart Title. For example, Wildlife Population.

#### Change Chart Type

You can easily change to a different type of chart at any time.

1. Select the chart.

2. On the Design tab, in the Type group, click Change Chart Type.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image18.png)

3. On the left side, click Column.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image19.png)

4. Click OK.

**Result:**

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image20.png)


### Excel Scatter Plot


Use a scatter plot (XY chart) to show scientific XY data. Scatter plots are often used to find out if there's a relationship between variable X and Y.

Download the [scatter-plot spreadsheet](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/scatter-plot.xlsx) and open in Excel.

To find out if there is a relationship between X (a person's salary) and Y (his/her car price), execute the following steps.

1. Select the range A1:B10.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image21.png)

2. On the Insert tab, in the Charts group, click the Scatter symbol.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image22.png)

3. Click Scatter.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image23.png)

**Result:**

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image23.jpg)

*Note*: we can add a trendline to clearly see the relationship between these two variables.

#### Adding a Trendline

1. Select the chart.

2. Add Chart Element > Trendline > Linear

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image25.png)

**Result:**

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image26.png)


## Online Tools - Datawrapper

There are a number of online websites that will create decent visualizations from your data

[Datawrapper](https://www.datawrapper.de/) is one such site - see examples below - you will need to supply them with an email address before you can download any chart you create. However, you can preview the results without doing this and create a screen grab.

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image27.png)

![image](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/images/image28.png)


## Using Python and Notebooks

The aim is that by using the pre-supplied code examples, and editing them to use your own files you will begin to gain an understand of the techniques used. However, even if much of the code seems unfathomable, it is possible to return to Jupyter Notebook and re-use this Notebook with your own texts.

You can run [this notebook](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/python-viz.ipynb.zip) either via Noteable, via Google Colab, or on your own device. Before you start you will have to download the zipped version of the notebook and extract the file within to an easy accessible part of your computer.

Once you have the file downloaded and extracted you can check the [Readme.md](https://github.com/DCS-training/EffectiveDataVisualisation/blob/main/README.md) file in this repository to learn how to open a Python Notebook via Noteable, via Google Colab, or on your own device. 

**THE END**


