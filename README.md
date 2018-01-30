# Data resources

### A list of helpful links and code for R, SQL, Python, HTML/CSS, etc. 

If you know of a good resource that you want to share, feel free to submit a pull request! If you're not sure how to do that, you can also submit an issue with the link to the resource and a quick intro to why it's helpful for you. 

This doc is based on my [google doc](https://docs.google.com/document/d/1dN9eeNJNaDIInpn7RCuigNL5NeBVkTFJxFtj8CkTW2g/edit?usp=sharing) of resources and inspired by a coversation I had on [twitter](https://twitter.com/katiejolly6/status/957641676130082817).

I'm slowly working on coverting the original doc! 

# Contents 

* [News](#news)
* [GIS and online mapping](#gis-and-online-mapping)
* [Data visualization- point and click](#data-visualization-mostly-point-and-click)
* [Rstats](#rstats)
   * [Links](#links)
      * Mentorship
      * Podcasts
      * Interviews
      * Packages
      * Blogs
      * Books
      * Style guides
    * [Helpful file functions](#helpful-file-functions) 
      * Extracting data from PDFs
    * [Excel in R](#excel-in-r)
    * [Googlesheets](#googlesheets-package-3)
    * [Dates and times](#dates-and-times)
    * [Dataframes/tables](#dataframestables)
    * [Conditionals](#conditionals)
    * [ggplot2](#ggplot2)
    * [GIS in R](#gis-in-r)
    * [Cleaning data](#cleaning-data)
    * [Modeling in R](#modeling-in-r)
* [Data](#data)
    * [Gov open data](#gov-open-data)
    * [Popular press data](#popular-press-data)
    * [Curated lists](#curated-lists)
* [Civic tech projects](#civic-tech-projects-open-source-contributing-yay)
* [General tips + tricks](#general-tips--tricks)

## News

* [GovTech](http://www.govtech.com/) - articles about technology in government
* [Fivethirtyeight](http://fivethirtyeight.com/)
* [Upshot](https://www.nytimes.com/section/upshot) - NYT's data analysis 
* [Flowing Data](http://flowingdata.com/) - beautiful data visualization, both articles and tutorials 
* [HuffPost Data](http://data.huffingtonpost.com/)
* [WaPo Wonkblog](https://www.washingtonpost.com/news/wonk/?utm_term=.0c876ed1d11b)
* [Brookings](https://www.brookings.edu/)
* [Urban Institute data/viz](https://www.urban.org/data-viz)
* [NPR Political data and technology](https://www.npr.org/sections/political-data-technology)
* [LA Times data desk](http://www.latimes.com/local/datadesk/#nt=taxonomy-article)
* [The Guardian datablog](https://www.theguardian.com/data)
* [Data journalism awards](https://www.datajournalismawards.org/)
* [7 types of people who are out of work, categorized with data](https://www.vox.com/policy-and-politics/2017/7/3/15893996/7-types-people-out-of-work)
* [Smart Cities DIVE](https://www.smartcitiesdive.com/)
* [Pudding](https://pudding.cool/)


## GIS and online mapping

* [Carto](https://carto.com/)
* [Mapbox](https://www.mapbox.com/)
* [Modest maps](http://modestmaps.com/)
* [Leaflet JS](http://leafletjs.com/)
* [Stamen](https://stamen.com/maps/)
* [ColorBrewer: color advice for maps](http://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3)

## Data visualization (mostly point-and-click)

* [Tableau public](https://public.tableau.com/s/) - Tableau desktop is **free** with a student email address! woohoo! 
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

## Rstats

### Links

* [awesome-R](https://github.com/qinwf/awesome-R) - github repo with SO MANY good R resources! Mostly packages, some other things at the end. 
* [RStudio online learning](https://www.rstudio.com/online-learning/)

#### Mentorship

* [Data helpers](https://www.datahelpers.org/) - A site by Angela Bassa with a list of people willing to help/mentor!

#### Podcasts

* [Dataframed](https://www.datacamp.com/community/podcast) - datacamp's podcast
* [Not so standard deviations](http://nssdeviations.com/)
* [Data skeptic](https://dataskeptic.com/)
* [Partially derivative](http://partiallyderivative.com/)
* [Linear digressions](http://lineardigressions.com/)
* [Data Stories](http://datastori.es/)


#### Interviews

* [.Rprofile Mara Averick](https://ropensci.org/blog/2017/11/10/rprofile-mara-averick/)
* [.Rprofile Karthik Ram](https://ropensci.org/blog/2018/01/12/rprofile-karthik-ram/)
* [.Rprofile Jenny Bryan](https://ropensci.org/blog/2017/12/08/rprofile-jenny-bryan/)

#### Packages to know/learn

* [ROpenSci packages](https://ropensci.org/packages/)
* [Emo: emojis in R](https://github.com/hadley/emo) because why not? 
* [Tidyverse packages](https://www.tidyverse.org/)
* [Broom](https://cran.r-project.org/web/packages/broom/vignettes/broom.html)- tidy model output
* [Markovify](https://github.com/abresler/markovifyR)- use this for future Markov chain poems! Re: Malcolm's [tweet](https://twitter.com/malco_bearhat/status/956593858573316096)

#### Blogs

* [ROpenSci](https://ropensci.org/blog/)
* [RWeekly](https://rweekly.org/)
* [David Robinson](http://varianceexplained.org)
* [Datacamp blog](https://www.datacamp.com/community/blog)
* [Datacamp tech](https://www.datacamp.com/community/tech)
* [RStudio](https://blog.rstudio.com/)
* [Mara Averick](https://maraaverick.rbind.io/)
* [Simply statistics](https://simplystatistics.org/)
* [Andrew Gelman](http://andrewgelman.com/)
* [Civil stat](http://civilstat.com/)
* [Citizen statistician](http://citizen-statistician.org/)
* [Maelle Salmon](http://www.masalmon.eu/)
* [Live free or dichotomize](http://livefreeordichotomize.com/)
* [Caitlin Hudon](https://caitlinhudon.com/)
* [Julia Silge](https://juliasilge.com/blog/)
* [Thomas Lin Pedersen](https://www.data-imaginist.com/)

#### Books

* [R for data science](http://r4ds.had.co.nz/) by Hadley Wickham
* [Advanced R](https://adv-r.hadley.nz/) by Hadley Wickham
* [Happy Git with R](http://happygitwithr.com/) by Jenny Bryan and the STAT 545 TAs
* [Stat 545](http://stat545.com/) - not quite a book, but same idea by Jenny Bryan
* [R Packages](http://r-pkgs.had.co.nz/intro.html) by Hadley Wickham
* [Graphics Cookbook for R](http://www.cookbook-r.com/) by Winston Chang
* [Data visualization: a practical introduction](http://socviz.co/) by Kieran Healy
* [R programming for data science](https://leanpub.com/rprogramming) by Roger Peng
* [Exploratory data analysis with R](https://leanpub.com/exdata) by Roger Peng
* [An intro to statistical and data sciences via R](http://moderndive.com/) by Chester Ismay and Albert Y. Kim
* [Tidy text mining](https://www.tidytextmining.com/) by Julia Silge and David Robinson
* [Intro to empirical Bayes](https://gumroad.com/l/empirical-bayes) by David Robinson
* [Curated list of R books](https://github.com/RomanTsegelskyi/rbooks)
* [Computational linear algebra course](http://www.fast.ai/2017/07/17/num-lin-alg/)
* [The fundamentals of data visualization](http://serialmentor.com/blog/2018/1/23/fundamentals-of-data-visualization) by Claus Wilke
* [Geocomputation with R](https://geocompr.robinlovelace.net/)


#### Style guides

* [Tidyverse style guide](http://style.tidyverse.org/)
* [Specifically: tidyverse error style guide](http://style.tidyverse.org/error-messages.html)
* [Google R style guide](https://google.github.io/styleguide/Rguide.xml)
* [R style guide](https://github.com/rdatsci/PackagesInfo/wiki/R-Style-Guide)
* [Data sharing style guide](https://github.com/vkoul/datasharing)

### Helpful file functions

```{r}
file.path() # takes folder names and returns a path to your file

file.choose() # pulls up finder so you can point to your file

download.file(url, dest_path) # makes downloading files reproducible
```

#### Extracting data from PDFs

ROpenSci has an awesome package to use tabula in R-- [tabulizer](https://github.com/ropensci/tabulizer)

[Tabula](http://tabula.technology/) is also awesome on its own. 

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

`strptime` to convert character strings to POSIXct.

```{r}
strptime(x, format, tz = "")
```
Formatting POSIXct objects:

* %Y: 4-digit year (1982)
* %y: 2-digit year (82)
* %m: 2-digit month (01)
* %d: 2-digit day of the month (13)
* %A: weekday (Wednesday)
* %a: abbreviated weekday (Wed)
* %B: month (January)
* %b: abbreviated month (Jan)
* %H: hours as a decimal number (00-23)
* %I: hours as a decimal number (01-12)
* %M: minutes as a decimal number
* %S: seconds as a decimal number
* %T: shorthand notation for the typical format %H:%M:%S
* %p: AM/PM indicator

Example use: 

```{r}
# from r documentation
x <- c("1jan1960", "2jan1960", "31mar1960", "30jul1960")
z <- strptime(x, "%d%b%Y")
```

Also use `lubridate` for working with date objects!

There's helpful info on the [tidyverse site](http://lubridate.tidyverse.org/) as well as a nice [vignette](https://cran.r-project.org/web/packages/lubridate/lubridate.pdf)

Lubridate makes it easy to manipulate and work with dates. 

It has some of the same capacity as `strptime`, although I actually prefer the former.

```{r}
ymd(20101215)
#> [1] "2010-12-15"
mdy("4/1/17")
#> [1] "2017-04-01"
```
Lubridate also makes timezones less confusing!

```{r}
time <- ymd_hms("2010-12-13 15:30:30")
time
#> [1] "2010-12-13 15:30:30 UTC"

# Changes printing
with_tz(time, "America/Chicago")
#> [1] "2010-12-13 09:30:30 CST"

# Changes time
force_tz(time, "America/Chicago")
#> [1] "2010-12-13 15:30:30 CST"
```

You can also pull out specific parts of a date object.

```{r}
bday <- dmy("14/10/1979")
month(bday)
#> [1] 10
wday(bday, label = TRUE)
#> [1] Sun
#> Levels: Sun < Mon < Tue < Wed < Thu < Fri < Sat
```

Say you want to turn a time into a numerical representation (i.e. 8:30 AM would be 8.50). Use lubridate!

```{r}
time <- hm("8:30")

hour(time) + minute(time)/60
#> 8.5
```

### Dataframes/tables

### Conditionals

In R, you can write an if/else statement, similar to the way you would write it in Python. It helps me to think about it this way because I started programming in Python first.

It would look something like this:

```{r}
if (condition) {
  do something
 } else if (condition) {
  do something
 } else {
  do something
 }
```
But let's say you want to define a variable in a dataframe based on a conditional. It is way easier with tidyverse packages!

You can use `mutate()` with `ifelse(condition, if-do, else-do)`

For example, let's say you want to assign high & low with a conditional based on some values. You could do:

```{r}
library(dplyr)

df %>%
  mutate(x = ifelse(var > 5, "high", "low"))
  
# this assigns "high" to anything strictly higher than 5
```
You can also use a nested `ifelse()` for more complicated conditionals, although that is discouraged. More on that in a bit...

In this example, I wanted the final variable to say "White subjects", "Nonwhite subjects", or "Unknown". I started with two different variables. One said whether or not race was known, and the other gave race, if known. 

```{r}
library(tidyverse)

biopics <- read_csv("https://raw.githubusercontent.com/fivethirtyeight/data/master/biopics/biopics.csv")

biopics <- biopics %>% # start with our original data
  mutate(race_plotting = ifelse(race_known == "Unknown", "Unknown", ifelse(subject_race == "White", "White subjects", "Nonwhite subjects"))) # this says, if race_known is unknown, stop there and just mark unknown. But if we know the race, check to see if the race is coded as white. If it is, mark white and stop there. If not, mark nonwhite. 
```

Instead of getting lost in nested statements, try this instead! Found in [Github](https://github.com/tidyverse/dplyr/issues/1518)

```{r}
df <- mutate(df, newvar = derivedFactor(
  "group1" = oldvar %in% c("a", "b", "c"),
  "group2" = oldvar %in% c("d", "e", "f"),
  "group3" = oldvar %in% c("g", "h", "i"),
  .default = NA
))
```

`case_when()` is another good alternative that draws on some SQL syntax. Here's an example from [Stack Overflow](https://stackoverflow.com/questions/38649533/case-when-in-mutate-pipe)

```{r}
library(dplyr) # >= 0.7.0
mtcars %>% 
  mutate(cg = case_when(carb <= 2 ~ "low",
                        carb > 2  ~ "high"))
```

### ggplot2

[ggplot2 gallery](http://r-statistics.co/Top50-Ggplot2-Visualizations-MasterList-R-Code.html) 

How to change the order of the bars in `geom_bar()` !!!!

```{r}
# from https://stackoverflow.com/questions/5208679/order-bars-in-ggplot2-bar-graph

require(forcats)

ggplot(data, aes(x = fct_infreq(var))) + geom_bar()

# from https://rstudio-pubs-static.s3.amazonaws.com/7433_4537ea5073dc4162950abb715f513469.html

x$name <- factor(x$name, levels = x$name[order(x$val)])
ggplot(x, aes(x = name, y = val)) + theme_bw() + geom_bar(stat = "identity")
```

To look into: [gghighlight](https://yutani.rbind.io/post/2017-10-06-gghighlight/?utm_content=buffer25e45&utm_medium=social&utm_source=twitter.com&utm_campaign=buffer) in this blog post! Looks like an easier way to highlight certain lines/bars instead of manually coding that. 

### GIS in R

[GIS in R](http://www.nickeubank.com/gis-in-r/) by Nick Eubank. 

[Robin Lovelace: Creating maps in R](https://github.com/Robinlovelace/Creating-maps-in-R)

[R Spatial](http://rspatial.org/index.html)

For geocoding, try [opencage](https://ropensci.org/tutorials/opencage_tutorial/) per Maelle's suggestion! 

```{r}
# forward geocoding

output <- opencage_forward(placename = "Sarzeau")

# reverse geocoding

output2 <- opencage_reverse(latitude = 51.5034070,
                            longitude = -0.1275920)
                            
# adding parameters

results3 <- opencage_forward(placename = "Berlin", country = "DE")
```

But for now, I'm using a function I found online. Example:

I wanted to geocode the locations of the Boston community centers recently. I found the names [here](https://www.boston.gov/community-centers). Using the chrome extension for [CSS selector gadget](http://selectorgadget.com/), I scraped the names into R.

```{r}
community_centers_url <- read_html("https://www.boston.gov/community-centers") # site with names

centers <- community_centers_url %>%
  html_nodes(".cd-t") %>% # css selector
  html_text() # I want the text
```

Then I used a combination of functions to geocode. 

```{r}
url <- function(address, return.call = "json", sensor = "false") {
 root <- "http://maps.google.com/maps/api/geocode/"
 u <- paste(root, return.call, "?address=", address, "&sensor=", sensor, sep = "")
 return(URLencode(u))
} # calling google maps API
 
geoCode <- function(address,verbose=FALSE) {
 if(verbose) cat(address,"\n")
 u <- url(address)
 doc <- getURL(u)
 x <- fromJSON(doc,simplify = FALSE)
 if(x$status=="OK") {
 lat <- x$results[[1]]$geometry$location$lat
 lng <- x$results[[1]]$geometry$location$lng
 location_type <- x$results[[1]]$geometry$location_type
 formatted_address <- x$results[[1]]$formatted_address
 return(c(lat, lng, location_type, formatted_address))
 } else {
 return(c(NA,NA,NA, NA))
 } 
} # actually getting the addresses
```

I'm sure there's a cleaner way to do this, I'll work on using opencage and then updating this page!

Another method of geocoding is using ggmap package and Google API. First, register for a key [here](https://developers.google.com/maps/documentation/geocoding/get-api-key). After you get the key, this script will geocode for you (up to the API limit which is around 2500/day)

```{r}
library(ggmap)
register_google(key = "my_key")

for(i in 1:nrow(turnout_data)){
  #location is a string like "123 University Ave, Gainesville FL"
  #This works best if you format your locations the same way you would for Google Maps/Waze/Tom Tom
  result <- geocode(my_data_frame$location[i], output = "latlona", source = "google")
  my_data_frame$lon[i] <- as.numeric(result[1])
  my_data_frame$lat[i] <- as.numeric(result[2])
  turnout_data$geoAddress[i] <- as.character(result[3])
}

```


#### Census data! I love census data!

[Tidycensus](https://github.com/walkerke/tidycensus) for demographic data. 

```{r}
# median income in Boston census tracts

bos_inc <- get_acs(geography = "tract", 
              variables = c(medincome = "B19013_001"), 
              state = "MA",
              county = "Suffolk")

# see available variables for 2016 acs 5-year

load_variables(year = 2016, dataset = "acs5")
```

[Tigris](https://github.com/walkerke/tigris) to load the shapefiles to map census data!

```{r}
options(tigris_use_cache = TRUE) # doesn't cache by default
bos_tract <- tracts(state = "MA", county = "Suffolk")
```

You can join the two with `tigris::geo_join`. Regular joins don't work with spatial data. 

```{r}
bos_joined <- geo_join(bos_tract, bos_inc, by = "GEOID")
```

And if I want to exclude a particular tract (it's mostly water, NA for all demographics) that makes my maps looks ugly :(

```{r}
bos_joined <- subset(bos_joined, NAME.1 != "Census Tract 9901.01, Suffolk County, Massachusetts")
```

`dplyr::filter` doesn't work with spatial data!! 

### Cleaning data

Principles of tidy data:

* Each row is an observation, each column in an attribute/variable
* Exactly one type of observational unit per table
* Column headers should be variable names, not values (ie eye color vs blue)

The `tidyverse` has understandable and compatible functions for dealing with data cleaning!

Sometimes you have a table that is "wide" or "narrow," and you want it to be the other way. Use spread and gather!

From the [RStudio blog](https://blog.rstudio.com/2014/07/22/introducing-tidyr/):

```{r
library(tidyr)
library(dplyr)

messy <- data.frame(
  name = c("Wilbur", "Petunia", "Gregory"),
  a = c(67, 80, 64),
  b = c(56, 90, 50)
)
messy
#>      name  a  b
#> 1  Wilbur 67 56
#> 2 Petunia 80 90
#> 3 Gregory 64 50

# We have three variables (name, drug and heartrate), but only name is currently in a column. We use gather() to gather the a and b columns into key-value pairs of drug and heartrate:

# gather(data, key, value, ..., na.rm = FALSE, convert = FALSE,
  factor_key = FALSE)

messy %>%
  gather(drug, heartrate, a:b)
#>      name drug heartrate
#> 1  Wilbur    a        67
#> 2 Petunia    a        80
#> 3 Gregory    a        64
#> 4  Wilbur    b        56
#> 5 Petunia    b        90
#> 6 Gregory    b        50
```

Conversely, you also might want to `spread` your data.

```{r}
spread(data, key, value, fill = NA, convert = FALSE, drop = TRUE,
  sep = NULL)
```

Let's say you have a variable for date-time, but you want one variable for date and the other for time. 

In the case of the vignette, they wanted to separate location and time (randomized variables) in the table.

```{r}
tidier <- messy %>%
  gather(key, time, -id, -trt)
tidier %>% head(8)
#>   id       trt     key    time
#> 1  1 treatment work.T1 0.08514
#> 2  2   control work.T1 0.22544
#> 3  3 treatment work.T1 0.27453
#> 4  4   control work.T1 0.27231
#> 5  1 treatment home.T1 0.61583
#> 6  2   control home.T1 0.42967
#> 7  3 treatment home.T1 0.65166
#> 8  4   control home.T1 0.56774

tidy <- tidier %>%
  separate(key, into = c("location", "time"), sep = "\\.")
tidy %>% head(8)
#>   id       trt location time    time
#> 1  1 treatment     work   T1 0.08514
#> 2  2   control     work   T1 0.22544
#> 3  3 treatment     work   T1 0.27453
#> 4  4   control     work   T1 0.27231
#> 5  1 treatment     home   T1 0.61583
#> 6  2   control     home   T1 0.42967
#> 7  3 treatment     home   T1 0.65166
#> 8  4   control     home   T1 0.56774
```
The opposite of `separate()` is `unite()`. 

Let's say I have a dataframe where one of the variables is a full address. I want only the rows from Minnesota. 

Found in a [SO question](https://stackoverflow.com/questions/13043928/selecting-rows-where-a-column-has-a-string-like-hsa-partial-string-match)

```{r}
df %>%
    filter(str_detect(address, "Minnesota"))
    
# "detects" the string "Minnesota" in the address column    
```

What if we have NA values and blank cells, both meant to be NA?

Answer found in a [SO question](https://stackoverflow.com/questions/9126840/delete-rows-with-blank-values-in-one-particular-column)

```{r}
df <- df[!(is.na(df$var) | df$var==""), ]
```

### Modeling in R

David Robinson's `broom` package gives model output in a "tidy" format. 

## Data

### General Repositories:
* [Kaggle Datasets](https://www.kaggle.com/datasets)
* [data.world](https://data.world/)

### Gov open data

* [US gov data](https://www.data.gov/)
* [Charlottesville open data](http://opendata.charlottesville.org/)
* [Open data DC](http://opendata.dc.gov/)
* [Open data Minneapolis](http://opendata.minneapolismn.gov/)
* [Open data St Paul](https://information.stpaul.gov/)
* [MN geospatial commons](https://gisdata.mn.gov/)
* [Met Council (Twin Cities)](https://metrocouncil.org/Data-and-Maps/Data.aspx)
* [Boston Open Data](https://data.boston.gov/)
* [World Bank databank](http://databank.worldbank.org/data/home.aspx)

### Popular press data 

* [Fivethirthyeight](https://github.com/fivethirtyeight/data/tree/master/biopics)
* [Buzzfeed](https://github.com/BuzzFeedNews)
* [Seth Stephens-Davidowitz: google trends data](http://sethsd.com/research/)
* [ProPublica datasets](https://www.propublica.org/datastore/datasets)- only some are free

### Curated lists

* [Awesome public datasets](https://github.com/awesomedata/awesome-public-datasets)
* [Sunlight labs- before they closed](https://github.com/sunlightlabs)
* [Public APIs](https://github.com/toddmotto/public-apis)
* [The Guardian: global development data](https://www.theguardian.com/global-development-professionals-network/2016/mar/16/the-top-10-sources-of-data-for-international-development-research)


## Civic tech projects (open source contributing! yay!)

* [Open elections](https://github.com/openelections/openelections-core)- creating a central database of US election data at the precinct level. Uses Python + roles for non-coding. 
* [Mapping prejudice](https://www.mappingprejudice.org/get-involved/)- digitizing and mapping racial covenants in MPLS home deeds. No coding required!

## General tips + tricks

* [Guidelines for telling a great data science story](http://101.datascience.community/2017/06/09/guidelines-for-telling-a-great-data-science-story/)
* [Beginner mistakes](https://elitedatascience.com/beginner-mistakes)
* [How to call bullshit on big data: a practical guide](http://www.newyorker.com/tech/elements/how-to-call-bullshit-on-big-data-a-practical-guide)
* [The blissful ignorance of the narrative fallacy](https://multithreaded.stitchfix.com/blog/2017/06/07/hot-hand-and-narrative-fallacy/)
* [Emoji cheat sheet](https://www.webpagefx.com/tools/emoji-cheat-sheet/)

---

* Python

* HTML/CSS

* Regex

* SQL

* Jekyll + blogging


