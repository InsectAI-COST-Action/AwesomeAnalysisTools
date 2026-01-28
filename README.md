# 🐞 Awesome Analysis Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of available tools for the exploration and analysis of biodiversity records. The focus here is on data collected via traditional monitoring methods and data from computer vision-based monitoring systems. However, many of the tools listed can be more broadly applied. 

Contributions are welcome! Please check the [contribution guidelines](#contributing) below.

## Table of Contents
- [1. Data Cleaning and Processing Tools](#data-cleaning-and-processing-tools)
- [2. Geographic Coverage and Spatial Analysis Tools](#geographic-coverage-and-spatial-analysis-tools)
- [3. Taxonomic Tools and Databases](#taxonomic-tools-and-databases)
- [4. Ecological Data Analysis Tools](#ecological-data-analysis-tools)
- [5. Annotation and Tracking Tools](#annotation-and-tracking-tools)
- [6. Visualization Tools](#visualization-tools)
- [7. AI and Helper Tools](#ai-and-helper-tools)
- [8. Computer Vision](#computer-vision)
- [9. Literature and Knowledge Sources](#literature-and-knowledge-sources)
- [Contributing](#contributing)
- [License](#license)

## 1. Data Cleaning and Processing Tools

### 1.1 Image cleaning

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|
| ImgDupes | Github library to find duplicate images | Python | Yes | Open Source | [github](https://github.com/knjcode/imgdupes) |
| Imagededup | Python library for remove the duplicate images | Python | Yes | Open Source | [github](https://github.com/idealo/imagededup) |
| Exif.tools | Online tool to view and edit image metadata, like file type, file size, bits per pixel, background color etc. | Web-based | Yes | Freeware | [website](https://exif.tools/) |
| Pillow | Python library that controls whether a file can open or not. So broken files can be easily removed from the dataset. | Python | Yes | Open Source | [website](https://pypi.org/project/pillow/) |

### 1.2. Structured Data Cleaning

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|
| EntoInsights | R package. Once made publicly available, EntoInsights will provide functions for wrangling, analysing, and visualising entomological datasets generated from AI-based insect identifications, such as those produced by AMI (Automated Monitoring of Insects). | R | in development | - | - |
| dplyr | R package. Easy data manipulation e.g., filtering, grouping, summarising data, removing duplicate records. | R | Yes | Open Source | [website](https://dplyr.tidyverse.org/) |
| lubridate | R package. Easy date manipulation e.g., to extract time or date from a image timestamp, or convert between date/time formats. | R | Yes |  Open Source | [website](https://lubridate.tidyverse.org/) |
| tidyR | R package. tidyr' contains tools for changing the shape (pivoting) and hierarchy (nesting and 'unnesting') of a dataset, turning deeply nested lists into rectangular data frames ('rectangling'), and extracting values out of string columns. | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/tidyr/index.html) |
| dataReporter | R package. For documenting and creating reports on data cleanliness. | R | Yes | Open Source | [github](https://github.com/ekstroem/dataReporter)|
| rstatix | R package. Another method to display these specific rows is with the identify_outliers() function from the {rstatix} package | R | Yes | open Source | [github](https://github.com/kassambara/rstatix) |
| PyOD V2 | Python library. A comprehensive but easy-to-use Python library for detecting anomalies in multivariate data. | Python | Yes | Open Source | [webpage](https://pyod.readthedocs.io/en/latest/) |
| CleanLab | Python library. cleanlab helps you clean data and labels by automatically detecting issues in a ML dataset. | Python | Yes | Open Source | [webpage](https://pypi.org/project/cleanlab/) |
| BDclean | R package and shiny app. User-friendly data cleaning Shiny app for biodiversity data cleaning. | Shiny app | Yes | Open Source | [github](https://github.com/bd-R/bdclean) |
| CoordinateCleaner | R package. Automated flagging of common spatial and temporal errors in biological and paleontological collection data. | R | Yes | Open Source | [github](https://github.com/ropensci/CoordinateCleaner) | 


## 1.3. General Data Processing Tools

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|
| tidyverse | R package. Comprehensive toolkit for data manipulation tasks in R. | R | Yes | Open Source | [website](https://www.tidyverse.org/) |
| Pandas | Python library. Pandas, a powerful Python library for data manipulation and analysis, is a crowd favorite. | Python |  Yes | Open Source | [website](https://pandas.pydata.org/) |
| MATLAB Signal Processing Toolbox | Signal Processing Toolbox provides functions and apps to manage, analyze, preprocess, and extract features from uniformly and nonuniformly sampled signals. The toolbox includes tools for filter design and analysis, resampling, smoothing, detrending, and power spectrum estimation. | MATLAB |  Yes | Commercial | [website](https://www.mathworks.com/products/signal.html) |
| SQLite | SQLite is a C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine. | C | Yes | Open Source | [website](https://sqlite.org/) |
| summarytools | R package. provides a coherent set of functions centered on data exploration and simple reportingprovides a coherent set of functions centered on data exploration and simple reporting. | R | Yes | Open Source | [github](https://github.com/dcomtois/summarytools) |
| visdat | R package. vis_dat helps you visualise a dataframe and “get a look at the data” by displaying the variable classes in a dataframe as a plot with vis_dat, and getting a brief look into missing data patterns using vis_miss. | R | Yes | Open Source | [github](https://github.com/ropensci/visdat) |


## 2. Geographic Coverage and Spatial Analysis Tools

### 2.1. Mapping and Visualization

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|
| Leaflet | Leaflet is the leading open-source JavaScript library for mobile-friendly interactive maps. | API/JavaScript/R | Yes | Open Source | [website](https://leafletjs.com/) |
| Google Earth Engine | A cloud-based platform that allows you to extract remote sensing-based environmental variables—such as NDVI, land-use, latitude etc around your sampling points. | JavaScript/Python | Yes | Freeware | [website](https://earthengine.google.com/) |
| exploratory.io| Exploratory Desktop provides a Simple and Easy-to-Use UI experience to access various data sources, clean and transform data, visualize and analyze data to gain deeper insights, communicate your discoveries with Notes, and monitor your business metrics with Dashboards. | Desktop app | Variable | Free for academic use | [website](https://exploratory.io/) |



### 2.2. Spatial Analysis

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|






## 3. Taxonomic Tools and Databases

### 3.1. Species Classification and Identification

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|



### 3.2. Deep Learning for Classification

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|





## 4. Ecological Data Analysis Tools

### 4.1. Biodiversity Analysis

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|



### 4.2. Ecological Modeling

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|





## 5. Annotation and Tracking Tools

### 5.1. Annotation Tools

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|




### 5.2. Tracking and Monitoring

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|




## 6. Visualization Tools

### 6.1. Graphic Tools and Visualization

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|




### 6.2. Interactive Tools

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|




## 7. AI and Helper Tools

### 7.1. Language Models

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|







## 8. Computer Vision

### 8.1. Object Detection Models

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|



### 8.2. Identification Systems

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|





## 9. Literature and Knowledge Sources

### 9.1. Published papers

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|
| Paper: From buzzes to bytes | A review of available models for insect acoustic data. A tool to help select an appropriate model to analyse your data. | N/A | Yes | Open Access | [paper](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/1365-2664.14630) |



## Contributing

Contributions are welcome!  

Please:

1. Check for duplicates before adding a new entry.  
2. Follow the table format above.  
3. Include DOIs, GitHub links, and dataset sources if available.  
4. Open a pull request with a clear description of your addition.


## License

This project is licensed under the [MIT License](LICENSE).

---

> 🦋 *"Small bugs, big data."*
