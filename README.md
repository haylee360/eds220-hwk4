# Visualizing the Thomas Fire Scars in Santa Barbara and Ventura County

This repository houses:
- Jupyter Notebook constructing a fire boundary for the 2017 Thomas Fire in California
- Jupyter notebook visualzing a false color image of the Thomas Fire in combination with the fire's boundary

## Description
File map
```
├── data
│   ├── thomas_boundary
│   │   ├── thomas_boundary.cpg
│   │   ├── thomas_boundary.dbf
│   │   ├── thomas_boundary.prj
│   │   ├── thomas_boundary.shp
│   │   └── thomas_boundary.shx
│   └── landsat8-2018-01-26-sb-simplified.nc
├── .DS_Store
├── .gitignore
├── README.md
├── hwk4-task2-false-color-oyler.ipynb
└── hwk4-task2-fire-perimeter-oyler.ipynb      
```

## Data access
Data in this project were pulled from  
- [US EPA's EJSCREEN tool](https://www.epa.gov/ejscreen/download-ejscreen-data)
- HOLC redlining data from the [Digital Scholarship Lab](https://dsl.richmond.edu/panorama/redlining/#loc=5/39.1/-94.58&text=downloads)
- Bird diversity observations from the [Global Biodiversity Information Facility](https://eds-223-geospatial.github.io/assignments/gbif.org)

All relevant data available [here](https://drive.google.com/file/d/14CauXFZkVh_6z2Euq0m1Sq1kHQ31fiMk/view?usp=drive_link).

## References and Acknowledgements
All materials were created by [Ruth Oliver](https://github.com/ryoliver) for EDS-223. 

### Citations

- Global Biodiversity Information Facility, GBIF.org (13 October 2024) GBIF Occurence Download. 
- HOLC Redlining Data. Nelson, R. K., Winling, L, et al. (2023). Mapping Inequality: Redlining in New Deal America. Digital Scholarship Lab. https://dsl.richmond.edu/panorama/redlining 
- EJScreen: Environmental Justice Screening and Mapping Tool. United States Environmental Protection Agency. 2024 version. EJScreen. Retrieved: 10/4/24 from www.epa.gov/ejscreen. 
A brief explanation of the repository’s purpose. Paragraphs or a bulleted list are both acceptable options. You may include an image or logo that represents the project.

A concise description of what’s housed in the repository. This includes information about the repository structure or file organization.

Details regarding data access. Any necessary information on where data lives (e.g. is it housed in the repo, on a server, in a library / package etc.) and how to access it in order to run the code.

References or acknowledgements. In an appropriate, consistent format, including links. Provide a reference to the course and any other sources that supported the development of the repository. Add references for data sets too.
