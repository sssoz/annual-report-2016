# Érudit's annual report – 2016

## Install Jekyll

Ruby must be installed.

1. `gem install jekyll`

## Building the website

1. `git clone https://github.com/sssoz/annual-report-2016.git`
2. `cd annual-report-2016`
3. `jekyll build`
4. Content will be found in `annual-report-2016/_site`

## Updating copy / content

Content can be modified in the following files and directories
- `config.yml`
  - Labels, titles (both EN / FR), general site settings... 
- `_sections/`
  - One markdown file per section (six per language)
  - FR content prefixed with `fr-`, EN with `en-`
  
