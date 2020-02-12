# project_template
a template for an analysis project

# structure
- `00_text/` put any text outputs in here for instance MS or reports
- `01_data/00_raw/` put your raw data in here
- `01_data/` put intermediate data in here
- `02_helperfunctions/` put any project specific helper functions in here. i also have a package that has some of my favorite personal helper functions, but for reproducibility it might be better to have everything self contained if you are going to share a project and drop copies of those functions in here. not sure...
- `03_figures/` i like to put the figures in here, each with their own directory and their own self contained script to generate.
- `04_load_data.r` analysis files to follow 04, 05, 06, etc. the general format would be to load some data at the beginning do a chunck of analysis and then export intermediate data (rda, rdata, csv) for import in later steps.
