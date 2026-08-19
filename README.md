# 🐞 Awesome Analysis Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of available tools for the exploration and analysis of biodiversity records. The focus here is on data collected via traditional monitoring methods and data from computer vision-based monitoring systems. However, many of the tools listed can be more broadly applied. 

Contributions are welcome! Please check the [contribution guidelines](#contributing) below.

See also [Awesome InsectAI](https://github.com/InsectAI-COST-Action/awesome-insectai) for a curated list of papers, datasets, code, and pretrained models related to insect detection, classification, and monitoring using AI and deep learning.!

## Table of Contents
- [Tags](#tags)
- [1. Data Cleaning and Processing Tools](#data-cleaning-and-processing-tools)
- [2. Geographic Coverage and Spatial Analysis Tools](#geographic-coverage-and-spatial-analysis-tools)
- [3. Taxonomic Tools and Databases](#taxonomic-tools-and-databases)
- [4. Ecological Data Analysis Tools](#ecological-data-analysis-tools)
- [5. Annotation and Tracking Tools](#annotation-and-tracking-tools)
- [6. Visualization Tools](#visualization-tools)
- [7. Computer Vision](#computer-vision)
- [8. Literature and Knowledge Sources](#literature-and-knowledge-sources)
- [9. Example Workflows](#example-workflows)
- [Contributing](#contributing)
- [License](#license)



## Tags

Each tool has a **Tags** column indicating its main area of use. A tool may carry more than one tag.

| Tag | Meaning |
|:----|:--------|
| **CV** | Geared towards computer-vision-based monitoring — e.g. image/video data, annotation, detection, and classification. |
| **Monitoring** | Geared towards traditional biodiversity monitoring — e.g. survey design, occurrence records, and population/diversity analysis. |
| **General** | Broadly applicable data tools not specific to either workflow. |



## 1. Data Cleaning and Processing Tools

### 1.1 Image cleaning

| Tool Name | Tags | Description | Programming language | Available | Open Source? | Links |
|:----------|:-----|:------------|:---------------------|:----------|:-------------|:------|
| ImgDupes | CV | Github library to find duplicate images | Python | Yes | Open Source | [github](https://github.com/knjcode/imgdupes) |
| Imagededup | CV | Python library for remove the duplicate images | Python | Yes | Open Source | [github](https://github.com/idealo/imagededup) |
| Exif.tools | CV | Online tool to view and edit image metadata, like file type, file size, bits per pixel, background color etc. | Web-based | Yes | Freeware | [website](https://exif.tools/) |
| Pillow | CV | Python library that controls whether a file can open or not. So broken files can be easily removed from the dataset. | Python | Yes | Open Source | [website](https://pypi.org/project/pillow/) |



### 1.2. Structured Data Cleaning

| Tool Name | Tags | Description | Programming language | Available | Open Source? | Links |
|:----------|:-----|:------------|:---------------------|:----------|:-------------|:------|
| EntoInsights | CV, Monitoring | R package. Once made publicly available, EntoInsights will provide functions for wrangling, analysing, and visualising entomological datasets generated from AI-based insect identifications, such as those produced by AMI (Automated Monitoring of Insects). | R | in development | Open Source | [github](https://github.com/AMI-system/EntoInsights) |
| dplyr | General | R package. Easy data manipulation e.g., filtering, grouping, summarising data, removing duplicate records. | R | Yes | Open Source | [website](https://dplyr.tidyverse.org/) |
| lubridate | General | R package. Easy date manipulation e.g., to extract time or date from a image timestamp, or convert between date/time formats. | R | Yes |  Open Source | [website](https://lubridate.tidyverse.org/) |
| tidyR | General | R package. tidyr' contains tools for changing the shape (pivoting) and hierarchy (nesting and 'unnesting') of a dataset, turning deeply nested lists into rectangular data frames ('rectangling'), and extracting values out of string columns. | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/tidyr/index.html) |
| dataReporter | General | R package. For documenting and creating reports on data cleanliness. | R | Yes | Open Source | [github](https://github.com/ekstroem/dataReporter)|
| rstatix | General | R package. Another method to display these specific rows is with the identify_outliers() function from the {rstatix} package | R | Yes | open Source | [github](https://github.com/kassambara/rstatix) |
| PyOD 3 | General | Python library. A comprehensive but easy-to-use Python library for detecting anomalies in multivariate data. | Python | Yes | Open Source | [webpage](https://pyod.readthedocs.io/en/latest/) |
| CleanLab | CV, General | Python library. cleanlab helps you clean data and labels by automatically detecting issues in a ML dataset. | Python | Yes | Open Source | [webpage](https://pypi.org/project/cleanlab/) |
| BDclean | Monitoring | R package and shiny app. User-friendly data cleaning Shiny app for biodiversity data cleaning. | Shiny app | Yes | Open Source | [github](https://github.com/bd-R/bdclean) |
| CoordinateCleaner | Monitoring | R package. Automated flagging of common spatial and temporal errors in biological and paleontological collection data. | R | Yes | Open Source | [github](https://github.com/ropensci/CoordinateCleaner) |
| BeeBDC | Monitoring | R package. An occurrence data cleaning package that provides novel and updated functions for flagging, cleaning, visualising, and analysing occurrence datasets. | R | Yes | Open Source | [website](https://jbdorey.github.io/BeeBDC/) |
| OccAssess | Monitoring | R package. Enables quick and easy screening of species occurrence data for common forms of bias. | R | Yes | Open Source | [github](https://github.com/robboyd/occAssess) | 



## 1.3. General Data Processing Tools

| Tool Name | Tags | Description | Programming language | Available | Open Source? | Links |
|:----------|:-----|:------------|:---------------------|:----------|:-------------|:------|
| tidyverse | General | R package. Comprehensive toolkit for data manipulation tasks in R. | R | Yes | Open Source | [website](https://www.tidyverse.org/) |
| Pandas | General | Python library. Pandas, a powerful Python library for data manipulation and analysis, is a crowd favorite. | Python |  Yes | Open Source | [website](https://pandas.pydata.org/) |
| MATLAB Signal Processing Toolbox | General | Signal Processing Toolbox provides functions and apps to manage, analyze, preprocess, and extract features from uniformly and nonuniformly sampled signals. The toolbox includes tools for filter design and analysis, resampling, smoothing, detrending, and power spectrum estimation. | MATLAB |  Yes | Commercial | [website](https://www.mathworks.com/products/signal.html) |
| SQLite | General | SQLite is a C-language library that implements a small, fast, self-contained, high-reliability, full-featured, SQL database engine. | C | Yes | Open Source | [website](https://sqlite.org/) |
| summarytools | General | R package. provides a coherent set of functions centered on data exploration and simple reportingprovides a coherent set of functions centered on data exploration and simple reporting. | R | Yes | Open Source | [github](https://github.com/dcomtois/summarytools) |
| visdat | General | R package. vis_dat helps you visualise a dataframe and “get a look at the data” by displaying the variable classes in a dataframe as a plot with vis_dat, and getting a brief look into missing data patterns using vis_miss. | R | Yes | Open Source | [github](https://github.com/ropensci/visdat) |



## 2. Geographic Coverage and Spatial Analysis Tools

### 2.1. Mapping and Visualization

| Tool Name | Tags | Description | Programming language | Available | Open Source? | Links |
|:----------|:-----|:------------|:---------------------|:----------|:-------------|:------|
| Leaflet | General | Leaflet is the leading open-source JavaScript library for mobile-friendly interactive maps. | API/JavaScript/R | Yes | Open Source | [website](https://leafletjs.com/) |
| Google Earth Engine | Monitoring, General | A cloud-based platform that allows you to extract remote sensing-based environmental variables—such as NDVI, land-use, latitude etc around your sampling points. | JavaScript/Python | Yes | Freeware | [website](https://earthengine.google.com/) |
| exploratory.io| General | Exploratory Desktop provides a Simple and Easy-to-Use UI experience to access various data sources, clean and transform data, visualize and analyze data to gain deeper insights, communicate your discoveries with Notes, and monitor your business metrics with Dashboards. | Desktop app | Variable | Free for academic use | [website](https://exploratory.io/) |



### 2.2. Spatial Analysis

| Tool Name | Tags | Description | Programming language | Available | Open Source? | Links |
|:----------|:-----|:------------|:---------------------|:----------|:-------------|:------|
| spbal | Monitoring | R package. A package to encapsulate a number of spatially balanced sampling algorithms, namely, BAS (equal, unequal, seed point, panels), Halton frames (for discretizing a continuous resource), HIP (equal probability) and Simple Random Sampling (SRS). | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/spbal/index.html) |
| Spbsampling | Monitoring | R package. The Spbsampling package provides functions to draw spatially balanced samples. In particular, the implemented sampling designs allow to select probability samples well spread over the population of interest, in any dimension and using any distance function (e.g. Euclidean distance, Manhattan distance). | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/Spbsampling/index.html) |
| pytopo | General | PyTopo is a desktop tiled map viewer that can also show and edit track logs, waypoints and other simple geographic data. | Desktop app | Yes | Open Source | [website](https://pytopo.readthedocs.io/en/latest/) |
| spThin | Monitoring | R package. Thinning of Species Occurrence Records for Use in Ecological Models | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/spThin/index.html)
| spocc | Monitoring | R package. A programmatic interface to many species occurrence data sources, including Global Biodiversity Information Facility ('GBIF'), 'iNaturalist', 'eBird', Integrated Digitized 'Biocollections' ('iDigBio'), 'VertNet', Ocean 'Biogeographic' Information.System ('OBIS'). | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/spocc/index.html) |
| pyinaturalist | Monitoring | Python library. pyinaturalist is a client for the iNaturalist API that makes these data easily accessible in the python programming language. | Python | Yes | Open Source | [website](https://github.com/pyinat/pyinaturalist) |
| Conefor | Monitoring | GIS extension for quantifying the importance of habitat patches and links for landscape connectivity. | GIS extension | Yes | Freeware | [website](http://www.conefor.org/gisextensions.html) |



## 3. Taxonomic Tools and Databases

### 3.1. Species Classification and Identification

| Tool Name | Tags | Description | Programming language | Available | Open Source? | Links |
|:----------|:-----|:------------|:---------------------|:----------|:-------------|:------|
| taxize | General | R package. Interacts with a suite of web application programming interfaces (API) for taxonomic tasks, such as getting database specific taxonomic identifiers, verifying species names, getting taxonomic hierarchies, fetching downstream and upstream taxonomic names, getting taxonomic synonyms, converting scientific to common names and vice versa, and more. | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/taxize/index.html) |
| GBIF | Monitoring | GBIF—the Global Biodiversity Information Facility—is an international network and data infrastructure funded by the world's governments and aimed at providing anyone, anywhere, open access to data about all types of life on Earth. | Database | Yes | - | [website](https://www.gbif.org/) |
| Pl@ntNet | CV | Online tool that helps you to identify plants with pictures. | Web-based | Yes | Freeware | [website](https://identify.plantnet.org/) |
| ObsIdentify | CV, Monitoring | App and website to identify species from photos and keep your photos and observations organized. | Mobile app | Yes | Freeware | [website](https://observation.org/apps/obsidentify/) |
| taxharmonizexplorer | General | Shiny app developed to help users of taxonomic information better understand the links that exist between taxonomic reference databases, R packages that manipulate taxonomy, and both of them. | Shiny app | Yes | - | [website](https://mgrenie.shinyapps.io/taxharmonizexplorer/) |



### 3.2. Deep Learning for Classification

| Tool Name | Tags | Description | Programming language | Available | Open Source? | Links |
|:----------|:-----|:------------|:---------------------|:----------|:-------------|:------|
| TensorFlow & Keras | CV | Deep learning platform suitable for building and training convolutional neural networks (CNN) for insect species classification. Can be used with pre-trained models like InceptionV3 or ResNet for faster results. | Python, C | Yes | Open Source | [website](https://www.tensorflow.org) [website]( https://keras.io/) |
| PyTorch | CV | PyTorch is a software-based open source deep learning framework used to build neural networks, combining the machine learning (ML) library of Torch with a Python-based high-level API. | Python | Yes | Open Source | [website](https://pytorch.org/) |
| AMI system github | CV, Monitoring | Source code of software for deploying, and analysing data from, the Automated Monitoring of Insects (AMI) systems. Contains multiple repositories. | Python, R | Variable | Variable  | [github](https://github.com/AMI-system) |
| BioTrove-CLIP | CV | A suite of CLIP-style vision-language foundation models for biodiversity, trained on BioTrove-Train (a large-scale dataset of 40 million images of 33K species of plants and animals); evaluated on zero-shot image classification tasks. | Python | Yes | Open Source | [website](https://huggingface.co/BGLab/BioTrove-CLIP) |
| Butterfly Classifier | CV | AI model trained on butterfly species using deep learning techniques (demo). | Web-based | Yes | - | [website](https://insectaidemo-975656330223.africa-south1.run.app/) |
| Fashion Tagger | CV | Web application that classifies fashion items using an ensemble of CNNs trained on a Kaggle dataset, predicting labels like category and color for each uploaded image. | Python | Yes | Open Source | [github](https://github.com/MahanVeisi8/FashionTagger) |
| Hugging Face | General | Platform where the machine learning community collaborates on models, datasets, and applications. | Web-based / Python | Yes | Freeware | [website](https://huggingface.co/) |
| Kaggle | General | Online platform for datasets, machine learning competitions, notebooks, and models. | Web-based | Yes | Freeware | [website](https://www.kaggle.com/) |
| ONNX | General | An open format built to represent machine learning models. ONNX defines a common set of operators—the building blocks of machine learning and deep learning models—and a common file format to enable AI developers to use models with a variety of frameworks, tools, runtimes, and compilers. | - | Yes | Open Source | [website](https://onnx.ai/) |



## 4. Ecological Data Analysis Tools

### 4.1. Biodiversity Analysis

| Tool Name | Tags | Description | Programming language | Available | Open Source? | Links |
|:----------|:-----|:------------|:---------------------|:----------|:-------------|:------|
| iNEXT | Monitoring | R package. iNEXT (iNterpolation and EXTrapolation) is an R package, available in CRAN and Github, for rarefaction and extrapolation of species diversity (Hill numbers). It can aid in calculating richness and diversity metrics (Shannon, Simpson), generating rarefaction/extrapolation curves to compare uneven samples, and plotting species accumulation to evaluate sampling completeness. | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/iNEXT/index.html) [github](https://github.com/AnneChao/iNEXT) |
| estimateS | Monitoring | EstimateS is a free software application for Windows and Macintosh operating systems, designed to help assess and compare the diversity and composition of species assemblages, based on sampling data. | Desktop app | Yes | Freeware | [website](https://www.robertkcolwell.org/pages/estimates) |
| biodiversityR | Monitoring | R package. Graphical User Interface (via the R-Commander) and utility functions (often based on the vegan package) for statistical analysis of biodiversity and ecological communities, including species accumulation curves, diversity indices, Renyi profiles, GLMs for analysis of species abundance and presence-absence, distance matrices, Mantel tests, and cluster, constrained and unconstrained ordination analysis. | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/BiodiversityR/index.html) |
| sparta | Monitoring | R package. An R package that includes methods used to analyse trends in unstructured occurrence datasets and a range of useful functions for mapping such data in the UK. Note that this package is not the sparta that is on CRAN and must be accessed via Github. | R | Yes | Open Source | [github](https://github.com/BiologicalRecordsCentre/sparta/tree/master) |
| biomonitoR | Monitoring | R package for managing taxonomic and functional information and for calculating indices for biomonitoring of running waters, with a focus on the macroinvertebrate community. | R | Yes | Open Source | [github](https://github.com/alexology/biomonitoR) |
| Perlodes / ASTERICS | Monitoring | Assessment system for evaluating the ecological quality of running waters using the macrozoobenthos (benthic invertebrate) quality component, per the EU Water Framework Directive (saprobity, general degradation and acidification modules). | Web-based / Desktop app | Yes | Freeware | [website](https://gewaesser-bewertung.de/index.php?article_id=419&clang=1) |



### 4.2. Ecological Modeling

| Tool Name | Tags | Description | Programming language | Available | Open Source? | Links |
|:----------|:-----|:------------|:---------------------|:----------|:-------------|:------|
| rangeBuilder | Monitoring | R package. Includes tools for filtering occurrence records, generating alpha-hull-derived range polygons and mapping species distributions. | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/rangeBuilder/index.html) |
| bipartite | Monitoring | R package. Bipartite provides functions to visualise webs and calculate a series of indices commonly used to describe pattern in (ecological) networks. | R | Yes | Open Source | [github](https://github.com/biometry/bipartite) |
| unmarked | Monitoring | R package. Occupancy & abundance models. Works well when you have repeat visits to the same site. | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/unmarked/index.html) |
| spOccupancy | CV, Monitoring | R package. Spatial occupancy + data integration: fits single- and multi-species occupancy models with spatial autocorrelation, and importantly supports **data integration** — combining CV monitoring and traditional survey data in a joint likelihood framework. | R | Yes | Open Source | [website](https://doserlab.com/files/spoccupancy-web/) |
| rtrim | Monitoring | R package. Population trend indices: TRIM (Trends & Indices for Monitoring data) is the standard method used across European bird and butterfly monitoring schemes. Handles missing data and produces population indices over time. | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/rtrim/index.html) |
| rbms | Monitoring | R package. Abundance indices & phenology for monitoring data: computes abundance indices specifically for butterfly monitoring count data, accounting for phenology (flight season timing). Directly relevant to seasonal insect data. | R | Yes | Open Source | [github](https://github.com/RetoSchmucki/rbms) |
| biomod2 | Monitoring | R package. Ensemble species distribution models: ensemble SDM platform combining multiple algorithms (Random Forest, MaxEnt, GBM, etc.). Good for range modelling with occurrence data from monitoring schemes. | R | Yes | Open Source | [website](https://biomodhub.r-universe.dev/biomod2) |
| maxnet | Monitoring | R package. MaxEnt species distribution models: MaxEnt SDMs implemented directly in R (no Java needed). Works with presence-only data, common in opportunistic monitoring. | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/maxnet/index.html) |
| DHARMa | General | R package. Residual diagnostics for hierarchical (multi-level / mixed) regression models: uses a simulation-based approach to create readily interpretable scaled (quantile) residuals for fitted generalized linear (mixed) models. | R | Yes | Open Source | [website](https://cran.r-project.org/web/packages/DHARMa/index.html) |
| albopictus | Monitoring | Python (v3.7) package implementing the environmentally-driven population dynamics model of Aedes albopictus. | Python | Yes | Open Source | [github](https://github.com/kerguler/albopictus) |
| Population | Monitoring | New generation population dynamics model with a dynamic population structure. | C | Yes | Open Source | [github](https://github.com/kerguler/Population) |



## 5. Annotation and Tracking Tools

### 5.1. Annotation Tools

| Tool Name | Tags | Description | Programming language | Available | Open Source? | Links |
|:----------|:-----|:------------|:---------------------|:----------|:-------------|:------|
| CVAT | CV | Open data annotation platform. Image or Video Annotation Tool. | Online app | Yes | Open Source | [website](https://www.cvat.ai/) | 
| labelstud.io | CV | A flexible data labeling platform to fine-tune LLMs, prepare training data, or evaluate AI models. | App | Yes | Open Source | [website](https://labelstud.io/) |
| DeepLabCut | CV | DeepLabCut™ is an efficient method for 2D and 3D markerless pose estimation based on transfer learning with deep neural networks that achieves excellent results (i.e. you can match human labeling accuracy) with minimal training data (typically 50-200 frames). | Python | Yes | Open Source | [website](https://www.mackenziemathislab.org/deeplabcut) |
| VGG Image Annotator (VIA) | CV | A simple and standalone manual annotation software for image, audio and video. VIA runs in a web browser and does not require any installation or setup. | JavaScript | Yes | Open Source | [website](https://gitlab.com/vgg/via-suite/via) |
| Roboflow | CV | Platform for building computer vision models — image/video annotation, dataset management and model training ("AI that sees and understands the physical world"). | Web-based | Yes | Freeware and paid | [website](https://roboflow.com/) |
| BIIGLE | CV | BIIGLE is a web service for the efficient and rapid annotation of still images and videos. It was built for marine environmental monitoring and exploration but can be used for any image and video annotation task. | Online platform | Yes | Open Source | [website](https://biigle.de) [github](https://github.com/biigle) |



### 5.2. Tracking and Monitoring

| Tool Name | Tags | Description | Programming language | Available | Open Source? | Links |
|:----------|:-----|:------------|:---------------------|:----------|:-------------|:------|
| ecoSecrets | CV, Monitoring | A web application enabling users to manage their camera traps data. | Web app | Yes | Open Source | [website](https://github.com/naturalsolutions/ecoSecrets) |
| Biowatch | CV, Monitoring | Biowatch is a free, open-source desktop application that lets you analyze, visualize, and explore camera trap datasets entirely offline. Your sensitive wildlife data never gets uploaded to any server — everything runs locally on your computer. | Desktop app | Yes | Open Source | [website](https://www.earthtoolsmaker.org/tools/biowatch/) |
| Antenna | CV, Monitoring | Antenna is an interdisciplinary platform to upload, classify, and analyse in-the-wild images of invertebrates for research and conservation efforts. It could be used for data cleaning to cross-check annotations. | Online platform | Yes | - | [website](https://www.insectai.org/) |
| camtrapR | CV, Monitoring | R package. Camera trap data management & detection histories: built specifically for camera trap workflows. Organises images, extracts detection histories, and feeds directly into occupancy analyses via `unmarked`. | R | Yes | Open Source | [website](https://jniedballa.github.io/camtrapR/) |
| agouti | CV, Monitoring | Platform for camera trap data that identifies species, filters out empty shots and transforms raw data into valuable insights. | Web app | Yes | - | [website](https://agouti.eu/) |
| Insect Detect Post | CV, Monitoring | Software for post-processing of data captured with the Insect Detect camera trap. It turns the captured images and metadata into cropped, classified and filtered results ready for analysis, by combining image processing, AI-based classification and metadata aggregation into a single configurable pipeline. | Python | Yes | Open Source | [github](https://github.com/maxsitt/insect-detect-post) |
| DynAIkonTrap | CV, Monitoring | Uses Raspberry Pi-style hardware to analyse video streams for camera trapping. | Python | Yes | Open Source | [website](https://dynaikon.com/trap-docs/) |
| Ecto-Trigger | CV, Monitoring | A toolkit designed to help ecologists develop lightweight AI models which can automate species detection in camera trap images. Especially useful where traditional motion sensors aren't reliable, e.g. detecting insects, as they lack the body-heat required to trigger conventional PIR sensors. | Python | Yes | Open Source | [website](https://rossgardiner.github.io/ecto-trigger/html/) |



## 6. Visualization Tools

### 6.1. Graphic Tools and Visualization

| Tool Name | Tags | Description | Programming language | Available | Open Source? | Links |
|:----------|:-----|:------------|:---------------------|:----------|:-------------|:------|
| ggplot2 | General | R package. For data visualisation, i.e. creating various plot types, maps etc. | R | Yes | Open Source | [website](https://ggplot2.tidyverse.org/) |
| ImageMagick | CV, General | ImageMagick is a collection of command-line tools that can be used to modify and manipulate images. | Command-line tools | Yes | Open Source | [website](https://imagemagick.org/script/command-line-tools.php) |
| ImageJ / Fiji | CV | ImageJ / Fiji is designed for scientific image processing and analysis. | Desktop app | Yes | Open Source | [website](https://imagej.net/software/fiji/downloads) |
| Gephi | General | Gephi is the leading visualization and exploration software for all kinds of graphs and networks. Gephi is open-source and free. | Desktop app | Yes | Open Source | [website](https://gephi.org/) |
| scikit-image | CV | Python library. scikit-image is a collection of algorithms for image processing. | Python | Yes | Open Source | [website](https://scikit-image.org/) |
| Weights & Biases (wandb) | General | Platform for machine learning experiment tracking and visualization, e.g. for monitoring model training (such as detecting overfitting). | Python / Web-based | Yes | Open Source and paid | [website](https://wandb.ai/site/) |
| TensorBoard | General | TensorFlow's visualization toolkit, providing the visualization and tooling needed for machine learning experimentation. | Python | Yes | Open Source | [website](https://www.tensorflow.org/tensorboard) |



### 6.2. Interactive Tools

| Tool Name | Tags | Description | Programming language | Available | Open Source? | Links |
|:----------|:-----|:------------|:---------------------|:----------|:-------------|:------|
| shiny | General | Build interactive web applications. Shiny apps are easy to write. Let users interact with your data and your analysis, all with R or Python. | R, Python | Yes | Open Source | [website](https://shiny.posit.co/) |



## 7. Computer Vision

### 7.1. Identification Systems

| Tool Name | Tags | Description | Programming language | Available | Open Source? | Links |
|:----------|:-----|:------------|:---------------------|:----------|:-------------|:------|
| OpenCV | CV | OpenCV is open source, contains over 2500 algorithms, and is operated by the non-profit Open Source Vision Foundation. Useful applications for noise filtering and image smoothing. Can calculate a "bluriness" measure using cv2.Laplacian(), which could then be used to filter out images over a certain 'bluriness' threshold. | N/A | Yes | Open Source | [website](https://opencv.org/) |
| Segment Anything | CV | Segment any objects in the image and cut out from the image. The most advanced AI to detect, edit and experiment with images and video. Powered by Meta SAM 3. | Python, C | Yes | Open Source | [website](https://segment-anything.com/) [github](https://github.com/facebookresearch/sam3) |
| LEPY | CV | Image analysis pipeline for extraction of color and structural traits from moth images placed on a white background. Structural traits such as wing span, body length, and wing areas are estimated using a scale bar in the image. | Python | Yes | Open Source | [github](https://github.com/tzlr-de/LEPY) [paper](https://ecoevorxiv.org/repository/view/8842) |
| LEPYLoop | CV | A tool to automate the analysis of large numbers of images with LEPY (LEPY can also be used without LEPYLoop). | Python | Yes | Open Source | [github](https://github.com/DesBoe/LepyLoop) |
| MZB-WORKFLOW | CV | Macrozoobenthos data workflow suite: an open-source deep learning and image processing pipeline designed to automate the segmentation, morphometric measurement, and classification of macrozoobenthos from lab image data. | Python | Yes | Open Source | [website](https://mzb-workflow.readthedocs.io/en/latest/) |
| WISE | CV | Search engine for images, videos, and audio powered by multimodal AI, allowing you to quickly and easily search through large collections of audiovisual media. | Python | Yes | Open Source | [website](https://gitlab.com/vgg/wise/wise/-/tree/main) |
| rembg | CV | A tool to remove image backgrounds. It can be used as a CLI, Python library, HTTP server, or Docker container. | Python | Yes | Open Source | [website](https://pypi.org/project/rembg/) |
| GrabCut | CV | Implements major portions of the GrabCut algorithm, a Markov random field based image segmentation algorithm (a variant of which is available as the background removal tool in Microsoft Office products). | Python | Yes | Open Source | [github](https://github.com/jiviteshjain/grabcut) |



## 8. Literature and Knowledge Sources

### 8.1. Published papers

| Paper | Paper type | Main authors | Summary | Code available? | Links |
|:------|:-----------|:-------------|:--------|:----------------|:------|
| From buzzes to bytes | Review | Kohlberg, Myers & Figueroa | Systematic review of 176 studies spanning four decades of automated bioacoustics models used to detect, classify and monitor insects. Finds machine (and especially deep) learning is becoming the gold standard, with some models classifying hundreds of species at >90% accuracy. Useful for selecting an appropriate model for acoustic data. | No — review paper; underlying data on [Dryad](https://datadryad.org/dataset/doi:10.5061/dryad.hmgqnk9r1) | [paper](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/1365-2664.14630) |
| Automated insect monitoring | Research article | Gillespie, Bjerge, Alison et al. | Demonstrates how automated camera traps combined with AI/deep-learning identification can advance insect monitoring — correcting phenology estimates by weeks and improving estimates of abundance, richness and community dynamics. | Planned — authors state code and data will be released in an open repository on publication | [paper](https://ecoevorxiv.org/repository/view/10577/) |
| Towards a toolkit for global insect biodiversity monitoring | Review | van Klink, Sheard, Høye et al. | Introduction to a theme issue synthesising four major technological approaches for automated insect monitoring (molecular methods, computer vision, acoustic monitoring, radar) and how to integrate them into a global monitoring system. | No — review/perspective paper | [paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC11070268/) |
| Emerging technologies revolutionise insect ecology and monitoring | Review | van Klink, August, Bas et al. | Reviews the state of the art of four technologies (computer vision, acoustic monitoring, radar, molecular methods), their advantages, current limitations and future potential, plus implications for data standards and citizen science. | No — review paper | [paper](https://www.sciencedirect.com/science/article/pii/S0169534722001343) |
| Towards reliable estimates of abundance trends using automated non-lethal moth traps | Research article | Möglich, Lampe, Fickus et al. | Examines how automated non-lethal moth traps can be used to derive reliable estimates of insect abundance trends. Published in Insect Conservation and Diversity. | Yes — AMT operating system on [GitHub](https://github.com/Nature40/InsectPhotoTrapOS/releases/tag/IPTv1.0.7); datasets archived via data_UMR ([repository](http://dx.doi.org/10.17192/fdr/194)) | [paper](https://resjournals.onlinelibrary.wiley.com/doi/10.1111/icad.12662) |
| MagicBrush: A Manually Annotated Dataset for Instruction-Guided Image Editing | Research article | Zhang, Mo, Chen, Sun & Su | Introduces MagicBrush, a large-scale, manually annotated dataset for instruction-guided real image editing. | Yes — code and dataset available | [paper](https://arxiv.org/abs/2306.10012) |
| DINOv2: Learning Robust Visual Features without Supervision | Research article | Oquab, Darcet, Moutakanni et al. | Presents DINOv2, a method for learning robust, general-purpose visual features from images without supervision. | Yes | [paper](https://arxiv.org/abs/2304.07193) |
| YOLOv1 to YOLOv11: A Comprehensive Survey of Real-Time Object Detection Innovations and Challenges | Review | Kotthapalli, Ravipati & Bhatia | Comprehensive review of the YOLO family of real-time object detectors, covering architectural innovations, performance benchmarks, and extended capabilities (instance segmentation, pose estimation, object tracking, and domain-specific applications such as medical imaging and industrial automation), plus real-world use cases and emerging research directions. | No — survey paper | [paper](https://arxiv.org/html/2508.02067v1) |
| Motion vectors and deep neural networks for video camera traps | Research article | Riechmann, Gardiner, Waddington et al. | Combines motion vectors with deep neural networks to process video streams from camera traps. | Data on [Dryad](https://datadryad.org/dataset/doi:10.5061/dryad.m0cfxpp3m) | [paper](https://www.sciencedirect.com/science/article/pii/S1574954122001066) |
| Harmonizing taxon names in biodiversity data: A review of tools, databases and best practices | Review | Grenié, Berti, Carvajal-Quintero et al. | Review of the tools, databases and best practices for harmonizing taxon names in biodiversity data. | No — review paper | [paper](https://besjournals.onlinelibrary.wiley.com/doi/10.1111/2041-210X.13802) |
| InsectDCT: A generalized pipeline for detection, taxonomic classification, and tracking of insects in camera-trap recordings | Research article | Bjerge, Wogram, Serra-Marin et al. | A pipeline combining YOLO11 detection, hierarchical taxonomic classification (80 groups across order/family/genus/species) and multi-object temporal tracking of insects in camera-trap images and video. | Yes — code and datasets publicly available | [paper](https://www.biorxiv.org/content/10.64898/2026.07.07.736939v2) |
| Computer vision reveals flower visitor interactions are mediated by agroforestry management, driving cocoa yield | Research article | Toledo-Hernández, Xu, Barillaro et al. | Uses computer vision and structural equation modelling to show that flower-visitor (arthropod) interactions in cocoa agroforests are mediated by shade-tree diversity and canopy management, affecting cocoa yield in China and Brazil. | On request — MicroPython script for frame differencing and blob detection in the ecoEye camera available upon request | [paper](https://www.nature.com/articles/s43247-026-03794-4) |



## 9. Example Workflows

Resources for finding reproducible workflows or redoing published studies.

| Name | Description | Programming language | Available | Links |
|:-----|:------------|:---------------------|:----------|:------|
| Workflow library (PlantHub) | Provides R and Python code for data analysis and visualization in the realms of biodiversity, ecology, and earth system sciences. The data used is open-access; however, in some cases (such as TRY), registration with the data providers is necessary. Useful for finding workflows or redoing published studies. | R, Python | Yes | [website](https://planthub.idiv.de/jupyter/html/) |



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
