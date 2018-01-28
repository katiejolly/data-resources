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

* [Data helpers](https://www.datahelpers.org/) - A site by Angela Bassa with a list of people willing to help/mentor!

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

#### Extracting data from PDFs

ROpenSci has an awesome package to use tabula in R-- [tabulizer](https://github.com/ropensci/tabulizer)

```{r}
# example code from github

library("tabulizer")
f <- system.file("examples", "data.pdf", package = "tabulizer")
out1 <- extract_tables(f)

out2 <- extract_tables(f, pages = 1, guess = FALSE, method = "data.frame")

extract_areas() # turns the pdf into an R graphic so you can select the tables on a page, if the whole page isn't a table! 

out3 <- extract_text(f, page = 3) # gets just the text from the table, without turning it into a dataframe
cat(out3, sep = "\n")
## len supp dose
## 4.2 VC 0.5
## 11.5 VC 0.5
## 7.3 VC 0.5
## 5.8 VC 0.5
## 6.4 VC 0.5
## 10.0 VC 0.5
## 11.2 VC 0.5
## 11.2 VC 0.5
## 5.2 VC 0.5
## 7.0 VC 0.5
## 16.5 VC 1.0
## 16.5 VC 1.0
## 15.2 VC 1.0
## 17.3 VC 1.0
## 22.5 VC 1.0
## 3
```

How to install tabulizer:

(On Windows) 

From github vignette:

In command prompt, install Chocolately if you don't already have it:

```
@powershell -NoProfile -ExecutionPolicy Bypass -Command "iex ((new-object net.webclient).DownloadString('https://chocolatey.org/install.ps1'))" && SET PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin
```

Then install java! 

```
choco install jdk7 -y
```

To set an environment variable in R use

```
Sys.setenv(JAVA_HOME = "C:/Program Files/Java/jdk1.8.0_92")
```

if that doesn't work, look at the other options in the vignette. 

Then install the dev version of the package (not yet on CRAN) 

```{r}
if (!require("ghit")) {
    install.packages("ghit")
}
# on 64-bit Windows
ghit::install_github(c("ropensci/tabulizerjars", "ropensci/tabulizer"), INSTALL_opts = "--no-multiarch")
# elsewhere
ghit::install_github(c("ropensci/tabulizerjars", "ropensci/tabulizer"))
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

[XLConnect](https://www.rdocumentation.org/packages/XLConnect/versions/0.2-13) - dynamic connection between R and excel. 

```{r}
createSheet(book, “name”)
loadWorkbook(“path”)
getSheets(book)
writeWorksheet () # function (object, data, sheet, startRow = 1, startCol = 1, header = TRUE, 
    rownames = NULL) 
writeWorkbook(object, “path”)
renameSheet() # function (object, sheet, newName) 
removeSheet() # function (object, sheet) 
```


### Googlesheets package <3

[googlesheets](https://github.com/jennybc/googlesheets)

There's a [vignette](https://rawgit.com/jennybc/googlesheets/master/vignettes/basic-usage.html) with lots of good info. 

```{r}
# uses oauth to access drive

gs_auth() # run to authorize
```

From the github site, an overview of the functions:

```{r}
gs_ls() # list sheets
gs_title() # register a sheet by title
gs_key() # register a sheet by key
gs_url() # register a sheet by url

... tbd 
```

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
