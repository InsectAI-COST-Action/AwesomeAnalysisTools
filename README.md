# 🐞 Awesome Analysis Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of available tools for the exploration and analysis of biodiversity records. The focus here is on data collected via traditional monitoring methods and data from computer vision-based monitoring systems. However, many of the tools listed can be more broadly applied. 

Contributions are welcome! Please check the [contribution guidelines](#contributing) below.

See also [Awesome InsectAI](https://github.com/InsectAI-COST-Action/awesome-insectai) for a curated list of papers, datasets, code, and pretrained models related to insect detection, classification, and monitoring using AI and deep learning.!

## Table of Contents
- [1. Data Cleaning and Processing Tools](#data-cleaning-and-processing-tools)
- [2. Geographic Coverage and Spatial Analysis Tools](#geographic-coverage-and-spatial-analysis-tools)
- [3. Taxonomic Tools and Databases](#taxonomic-tools-and-databases)
- [4. Ecological Data Analysis Tools](#ecological-data-analysis-tools)
- [5. Annotation and Tracking Tools](#annotation-and-tracking-tools)
- [6. Visualization Tools](#visualization-tools)
- [7. Computer Vision](#computer-vision)
- [8. Literature and Knowledge Sources](#literature-and-knowledge-sources)
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
| spbal | R package. A package to encapsulate a number of spatially balanced sampling algorithms, namely, BAS (equal, unequal, seed point, panels), Halton frames (for discretizing a continuous resource), HIP (equal probability) and Simple Random Sampling (SRS). | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/spbal/index.html) |
| Spbsampling | R package. The Spbsampling package provides functions to draw spatially balanced samples. In particular, the implemented sampling designs allow to select probability samples well spread over the population of interest, in any dimension and using any distance function (e.g. Euclidean distance, Manhattan distance). | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/Spbsampling/index.html) |
| pytopo | PyTopo is a desktop tiled map viewer that can also show and edit track logs, waypoints and other simple geographic data. | Desktop app | Yes | Open Source | [website](https://pytopo.readthedocs.io/en/latest/) |
| spThin | R package. Thinning of Species Occurrence Records for Use in Ecological Models | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/spThin/index.html)
| spocc | R package. A programmatic interface to many species occurrence data sources, including Global Biodiversity Information Facility ('GBIF'), 'iNaturalist', 'eBird', Integrated Digitized 'Biocollections' ('iDigBio'), 'VertNet', Ocean 'Biogeographic' Information.System ('OBIS'). | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/spocc/index.html) |
| pyinaturalist | Python library. pyinaturalist is a client for the iNaturalist API that makes these data easily accessible in the python programming language. | Python | Yes | Open Source | [website](https://github.com/pyinat/pyinaturalist) |



## 3. Taxonomic Tools and Databases

### 3.1. Species Classification and Identification

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|
| β-Variational Autoencoders | Approach for reverse taxonomy and the detection and characterization of cryptic diversity. | Python | Not yet (in development) | - | - |
| taxize | R package. Interacts with a suite of web application programming interfaces (API) for taxonomic tasks, such as getting database specific taxonomic identifiers, verifying species names, getting taxonomic hierarchies, fetching downstream and upstream taxonomic names, getting taxonomic synonyms, converting scientific to common names and vice versa, and more. | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/taxize/index.html) |
| GBIF | GBIF—the Global Biodiversity Information Facility—is an international network and data infrastructure funded by the world's governments and aimed at providing anyone, anywhere, open access to data about all types of life on Earth. | Database | Yes | - | [website](https://www.gbif.org/) |



### 3.2. Deep Learning for Classification

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|
| TensorFlow & Keras | Deep learning platform suitable for building and training convolutional neural networks (CNN) for insect species classification. Can be used with pre-trained models like InceptionV3 or ResNet for faster results. | Python, C | Yes | Open Source | [website](https://www.tensorflow.org) [website]( https://keras.io/) |
| PyTorch | PyTorch is a software-based open source deep learning framework used to build neural networks, combining the machine learning (ML) library of Torch with a Python-based high-level API. | Python | Yes | Open Source | [website](https://pytorch.org/) |
| AMI system github | Source code of software for deploying, and analysing data from, the Automated Monitoring of Insects (AMI) systems. Contains multiple repositories. | Python, R | Variable | Variable  | [github](https://github.com/AMI-system) |



## 4. Ecological Data Analysis Tools

### 4.1. Biodiversity Analysis

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|
| iNEXT | R package. iNEXT (iNterpolation and EXTrapolation) is an R package, available in CRAN and Github, for rarefaction and extrapolation of species diversity (Hill numbers). It can aid in calculating richness and diversity metrics (Shannon, Simpson), generating rarefaction/extrapolation curves to compare uneven samples, and plotting species accumulation to evaluate sampling completeness. | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/iNEXT/index.html) [github](https://github.com/AnneChao/iNEXT) |
| estimateS | EstimateS is a free software application for Windows and Macintosh operating systems, designed to help assess and compare the diversity and composition of species assemblages, based on sampling data. | Desktop app | Yes | Freeware | [website](https://www.robertkcolwell.org/pages/estimates) |
| biodiversityR | R package. Graphical User Interface (via the R-Commander) and utility functions (often based on the vegan package) for statistical analysis of biodiversity and ecological communities, including species accumulation curves, diversity indices, Renyi profiles, GLMs for analysis of species abundance and presence-absence, distance matrices, Mantel tests, and cluster, constrained and unconstrained ordination analysis. | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/BiodiversityR/index.html) |
| sparta | R package. An R package that includes methods used to analyse trends in unstructured occurrence datasets and a range of useful functions for mapping such data in the UK. Note that this package is not the sparta that is on CRAN and must be accessed via Github. | R | Yes | Open Source | [github](https://github.com/BiologicalRecordsCentre/sparta/tree/master) |



### 4.2. Ecological Modeling

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|
| rangeBuilder | R package. Includes tools for filtering occurrence records, generating alpha-hull-derived range polygons and mapping species distributions. | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/rangeBuilder/index.html) |
| bipartite | R package. Bipartite provides functions to visualise webs and calculate a series of indices commonly used to describe pattern in (ecological) networks. | R | Yes | Open Source | [github](https://github.com/biometry/bipartite) |



## 5. Annotation and Tracking Tools

### 5.1. Annotation Tools

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|
| CVAT | Open data annotation platform. Image or Video Annotation Tool. | Online app | Yes | Open Source | [website](https://www.cvat.ai/) | 
| labelstud.io | A flexible data labeling platform to fine-tune LLMs, prepare training data, or evaluate AI models. | App | Yes | Open Source | [website](labelstud.io) |
| DeepLabCut | DeepLabCut™ is an efficient method for 2D and 3D markerless pose estimation based on transfer learning with deep neural networks that achieves excellent results (i.e. you can match human labeling accuracy) with minimal training data (typically 50-200 frames). | Python | Yes | Open Source | [website](https://www.mackenziemathislab.org/deeplabcut) |



### 5.2. Tracking and Monitoring

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|
| ecoSecrets | A web application enabling users to manage their camera traps data. | Web app | Yes | Open Source | [website](https://github.com/naturalsolutions/ecoSecrets) |
| Biowatch | Biowatch is a free, open-source desktop application that lets you analyze, visualize, and explore camera trap datasets entirely offline. Your sensitive wildlife data never gets uploaded to any server — everything runs locally on your computer. | Desktop app | Yes | Open Source | [website](https://www.earthtoolsmaker.org/tools/biowatch/) |
| Antenna | Antenna is an interdisciplinary platform to upload, classify, and analyse in-the-wild images of invertebrates for research and conservation efforts. It could be used for data cleaning to cross-check annotations. | Online platform | Yes | - | [website](https://www.insectai.org/) |



## 6. Visualization Tools

### 6.1. Graphic Tools and Visualization

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|
| ggplot2 | R package. For data visualisation, i.e. creating various plot types, maps etc. | R | Yes | Open Source | [website](https://ggplot2.tidyverse.org/) |
| ImageMagick | ImageMagick is a collection of command-line tools that can be used to modify and manipulate images. | Command-line tools | Yes | Open Source | [website](https://imagemagick.org/script/command-line-tools.php) |
| ImageJ / Fiji | ImageJ / Fiji is designed for scientific image processing and analysis. | Desktop app | Yes | Open Source | [website](https://imagej.net/software/fiji/downloads) |
| Gephi | Gephi is the leading visualization and exploration software for all kinds of graphs and networks. Gephi is open-source and free. | Desktop app | Yes | Open Source | [website](https://gephi.org/) |
| scikit-image | Python library. scikit-image is a collection of algorithms for image processing. | Python | Yes | Open Source | [website](https://scikit-image.org/) |



### 6.2. Interactive Tools

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|
| shiny | Build interactive web applications. Shiny apps are easy to write. Let users interact with your data and your analysis, all with R or Python. | R, Python | Yes | Open Source | [website](https://shiny.posit.co/) |



## 7. Computer Vision

### 7.1. Identification Systems

| Tool Name     | Description                            | Programming language | Available | Open Source? | Links |
|:--------------|:---------------------------------------|:---------------------|:----------|:-------------|:------|
| DAISY | Digital Automated Identification SYstem. Daisy is a universal identification AI. It can be applied to anything: images, sounds, chemical spectra, even molecular data. | N/A | - | - | [website](https://www.tumblingdice.co.uk/technologies/daisy/) |
| OpenCV | OpenCV is open source, contains over 2500 algorithms, and is operated by the non-profit Open Source Vision Foundation. Useful applications for noise filtering and image smoothing. Can calculate a "bluriness" measure using cv2.Laplacian(), which could then be used to filter out images over a certain 'bluriness' threshold. | N/A | Yes | Open Source | [website](https://opencv.org/) |
| Segment Anything | Segment any objects in the image and cut out from the image. The most advanced AI to detect, edit and experiment with images and video. Powered by Meta SAM 3. | Python, C | Yes | Open Source | [website](https://segment-anything.com/) |



## 8. Literature and Knowledge Sources

### 8.1. Published papers

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
