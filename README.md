# Data resources

### A list of helpful links and code for R, SQL, Python, HTML/CSS, etc. 

If you know of a good resource that you want to share, feel free to submit a pull request! If you're not sure how to do that, you can also submit an issue with the link to the resource and a quick intro to why it's helpful for you. 

This doc is based on my [google doc](https://docs.google.com/document/d/1dN9eeNJNaDIInpn7RCuigNL5NeBVkTFJxFtj8CkTW2g/edit?usp=sharing) of resources. I'm slowly working on coverting that file! 

## News

* [GovTech](http://www.govtech.com/) - articles about technology in government
* [Fivethirtyeight](http://fivethirtyeight.com/)
* [Upshot](https://www.nytimes.com/section/upshot) - NYT's data analysis 
* [Flowing Data](http://flowingdata.com/) - beautiful data visualization, both articles and tutorials 

## GIS and online mapping

* [Tableau public](https://public.tableau.com/s/) - Tableau desktop is **free** with a student email address! woohoo! 
* [Carto](https://carto.com/)
* [Mapbox](https://www.mapbox.com/)
* [Modest maps](http://modestmaps.com/)
* [Leaflet JS](http://leafletjs.com/)
* [Stamen](https://stamen.com/maps/)

## Data visualization (mostly point-and-click)

* [Gephi](https://gephi.org/)
* [UMD treemap](http://www.cs.umd.edu/hcil/treemap/)
* [Chart.js](https://github.com/chartjs)
* [Raw graphs](http://rawgraphs.io/)
* [Timeline](https://timeline.knightlab.com/)

### General data viz books, etc. 

* [Data points: visualization that means something](http://flowingdata.com/data-points/) by Nathan Yau
* [Visualize this](http://book.flowingdata.com/) by Nathan Yau
* Anything by Edward Tufte
* [Designer's guide to creating charts and diagrams](https://www.amazon.com/Designers-Guide-Creating-Charts-Diagrams/dp/0823013383) by Nigel Holmes
* [Cool infographics](https://www.amazon.com/Cool-Infographics-Effective-Communication-Visualization/dp/1118582306) by Randy Krum
* [TED talk: The beauty of data visualization](https://www.ted.com/talks/david_mccandless_the_beauty_of_data_visualization?language=en) by David McCandless
* [The functional art](http://www.thefunctionalart.com/p/about-book.html) by Alberto Cairo

## R

### Links

#### Mentorship

* [Data helpers] - A site by Angela Bassa with a list of people willing to help/mentor!

#### Podcasts

#### Interviews

#### Packages to know/learn

#### Blogs

#### Books

#### Style guides

### General

### Helpful file functions

```{r}
file.path() # takes folder names and returns a path to your file

file.choose() # pulls up finder so you can point to your file

download.file(url, dest_path) # makes downloading files reproducible
```

### Excel in R

[Using the xlsx package to create an excel file](https://www.r-bloggers.com/using-the-xlsx-package-to-create-an-excel-file/)

[readxl package](http://readxl.tidyverse.org/) - tidyverse w/ excel

```{r}
excel_sheets() # gives a character vector of the sheet names

read_excel() # reads in excel files
# args: sheets (defines which sheet you want)
        col_names = TRUE
        col_types ("blank" to skip a column)
        skip (n rows to skip)

# put all sheets in a list to keep them together

my_workbook <- lapply(excel_sheets("data.xlsx"),
  read_excel,
  path = "data.xlsx")
```

### Googlesheets package

### Dates and times

### Dataframes/tables

### Conditionals

---

* Python

* HTML/CSS

* Data sources

* Regex

* SQL

* Jekyll + blogging

* General tips + tricks
