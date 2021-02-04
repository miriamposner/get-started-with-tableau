# Getting started with Tableau Public

Tableau is a powerful data visualization tool, in heavy use among both laypeople and data professionals.

Tableau Public is the free version of this tool. There are several things to be aware of with regard to Tableau Public. It's free to download and use, but, aside from screenshots, the only way to share Tableau Public visualizations is to publish them to the Tableau Public website. That means they will be freely available on the web, and you will need to create a Tableau account in order to do this.

However, you do not need to create an account in order to use Tableau Public. We will use it today to make two charts, which we'll combine into a dashboard. [Here is a preview of what we'll make.](https://public.tableau.com/profile/miriam.posner#!/vizhome/IowaArtsGrants2015/Dashboard1?publish=yes) At the end of this tutorial, you'll find information on how to publish it to the web. For this exercise, you will need the Iowa Arts Council Grants data CSV file, which you can download at [this link](https://www.dropbox.com/s/lhanmm3v9ylccgz/Iowa_Arts_Council_Grants.csv?dl=0).

## 1. Choose your data source

After opening Tableau, you're presented with a list of file types you can choose to work with ("connect"). Even though our Iowa Arts Council Grants file *opens* in Excel, it's saved as a CSV. To Tableau, a CSV is a text file. So select **Text file.** Then navigate to the file you downloaded earlier and double-click to open it.

![][1]

[1]: images/getting-started-with-tableau-public/choose-your-data-source.png

## 2. Create a sheet

Tableau will open your file. It should look pretty familiar! In Tableau, you begin visualizing data by creating a **Sheet**. Do that by clicking on the orange **Sheet** button in the lower left-hand corner.

![][2]

[2]: images/getting-started-with-tableau-public/create-a-sheet.png

## 3. Data types in Tableau

Tableau divides your content types (that is, your columns) into **dimensions** and **measures**. Measures consist of numeric information: values that can be added together. Everything else is a dimension. Tableau will often provide recommendations based on these data types.

![][3]

[3]: images/getting-started-with-tableau-public/data-types-in-tableau.png

## 4. Your first visualization

Get started by clicking on **Applicant Arts Discipline** and drag it into the main section of the sheet (the **canvas**). It's not hugely exciting; you just see a list of arts disciplines.

There's a reason for that: Tableau doesn't know what you want it to count.

![][4]

[4]: images/getting-started-with-tableau-public/your-first-visualization.png

## 5. Tell Tableau which measure to use

We want Tableau to create a chart that visualizes the number of grants awarded per arts discipline. In order to do that, we need Tableau to count up the values for each category.

Scroll to the bottom of the **Data** column, and look at the measure types that are in italics. You'll see that they contain the word **generated** next to them in parentheses. This means that these are numbers that Tableau has calculated for you.

You'll notice a measure called **IAC.csv (Count)**. This measure provides a count of all grants. Click on this measure and drag it to the table on your canvas. Drop it in the second column of the table, where the values are currently represented as "Abc."

![][5]

[5]: images/getting-started-with-tableau-public/tell-tableau-which-measure-to-use.png

## 6. Choose the chart type you want

Once you've dropped the "Number of Records" measure, you'll see that they're nicely summarized for you in the table you created. You'll also notice that highlighted options appear in the palette of chart types on the right-hand side of your window. Now that you have measures, you have some chart options! Click on the bar chart.

![][6]

[6]: images/getting-started-with-tableau-public/choose-the-chart-type-you-want.png

## 7. Compare multiple values

You created a visualization! Now, let's see if we can create a stacked bar chart, the way we did with Excel. We'll show how **Application Instition Type** correlates with **Application Arts Discipline**.

Luckily, this is easy. Just drag the Application Institution Type measure onto the bar chart you've already created.

![][7]

[7]: images/getting-started-with-tableau-public/compare-multiple-values.png

## 8. Create a stacked bar chart

Now, let's switch to a stacked bar chart, so we can see the distinctions among institution types more clearly. You'll notice that as you hover over each segment, a tooltip gives you more information.

![][8]

[8]: images/getting-started-with-tableau-public/create-a-stacked-bar-chart.png

## 9. Give your chart a name

Click on your chart's title (it currently reads **Sheet 1**) to give it a more descriptive name.

![][9]

[9]: images/getting-started-with-tableau-public/give-your-chart-a-name.png

## 10. Start a new chart

Now let's make our second chart. Click on the **New worksheet** button (circled below) to begin our new visualization.

![][10]

[10]: images/getting-started-with-tableau-public/start-a-new-chart.png

## 11. Make a map

Tableau has automatically geocoded our geographic dimensions. You can tell because a tiny globe appears next to them. Drag **County** into the main canvas area, and give Tableau a moment to work.

![][11]

[11]: images/getting-started-with-tableau-public/make-a-map.png

## 12. You have a map!

Now that you've done a map, let's add a measure to it. Drag **Number of Records** into the main canvas area, on top of your map.

![][12]

[12]: images/getting-started-with-tableau-public/you-have-a-map-.png

## 13. Finish your map

Now the circles on your map grow larger as the number of grants awarded to that county increases. You can fine-tune the look of your map by altering the options in the **Marks window**. Give your new map a title, as you did for your chart.

![][13]

[13]: images/getting-started-with-tableau-public/finish-your-map.png

## 14. Create a dashboard

Now we'll combine our charts to create a **dashboard** -- a snapshot of multiple visualizations. Do that by clicking on the **Dashboard** button, circled below.

![][14]

[14]: images/getting-started-with-tableau-public/create-a-dashboard.png

## 15. Drag your sheets onto your dashboard

From the left-hand side of your dashboard's window, click on each of your sheets in turn and drag them into your main canvas. Very nice!

![][15]

[15]: images/getting-started-with-tableau-public/drag-your-sheets-onto-your-dashboard.png

## 16. Options for exporting

As I've mentioned, in order to make your visualization web-accessible, you will need to create a Tableau account and publish to Tableau's site. From there, you can embed your visualizations in other web pages. To begin this process, select **Save to Tableau Public As...** from the **File** menu. You will be prompted to begin the process of creating an account, logging in, and publishing to the web.

There's a *ton* more you can do with Tableau. You can begin learning about its other features [here](https://public.tableau.com/en-us/s/resources).

![][16]

[16]: images/getting-started-with-tableau-public/options-for-exporting.png
