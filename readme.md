
# COMP3023 DV Group Project

## Author Information

- **Name:** Henry, Adon, Tina, Dreama
- **Department:** Data Science
- **Course:** Introduction to Data Visualization
- **Environment for Game_Vis.Rmd:** macOS 12.7.1; Apple M1. 
- **Enviroment for 3D-Plots:** Windows 11 22H2 22621.2715; AMD Ryzen 5 5600U; R Version: 4.2.2.


# Usage

## General

To run our code, you could direct to `Game_Vis.Rmd`, and install the package below. 

For `shiny` implementation (e.g. 'Time Control' and 'Marketing Analysis 3'), it cannot be shown directly in HTML file. You may re-knit the code, and select *`'Yes Once'`* for `shiny` package after finishing kniting.

Our enviroment is macOS 12.7.1; Apple M1. Additionally, the code would cost up to 10mins to excute, be patient. Thanks.

```{r}
library(dplyr)
library(highcharter)
library(flexdashboard) 
library(highcharter) 
library(plotly) 
library(viridis) 
library(tidyverse) 
library(countrycode) 
library(rjson) 
library(crosstalk) 
library(DT)
library(ggstream)
library(cowplot)
library(paletteer)
library(colorspace)
library(scales)
library(tidyr)
library(lubridate)
library(shiny)
library(readr)
library(RColorBrewer)
library(tm)
library(wordcloud)
library(SnowballC)
```

## 3D-implementation

Due to the limitation of the Dashboard, it cannot show the 3D plot from `library(rayshader)`, which can run correctly in Rmd in RStudio. So we create another two Rmd file to implement the 3D code.
To run our 3D-implementation code, you cloud direct to `3D_Heatmap.Rmd` and `3D_Map.Rmd`, and install the package below. **You need to run them directly in RStudio rather than knit to HTML.** Our running environment is Windows 11 22H2 22621.2715; AMD Ryzen 5 5600U, R Version: 4.2.2.

```{r}
library(dplyr)
library(ggplot2)
library(rayshader)
library(scales)
```



