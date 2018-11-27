# My personal webpage

This is the README file for the source code for my personal webpage. It can be found at <https://people-r-strange.github.io/webpage/>. 

name: "Vivenne Maxwell"
output_dir: docs
# The website theme was chosen from
# https://rmarkdown.rstudio.com/html_document_format#appearance_and_style
output:
  html_document:
    toc: yes
    toc_float: yes
    toc_depth: 2
    theme: journal
    highlight: tango
    df_print: paged
    lib_dir: site_libs
    self_contained: no
# All fa icons were obtained from https://fontawesome.com/icons?d=gallery
navbar:
  title: "My Website"
  left:
    - text: "Home"
      href: index.html
    - text: "About"
      href: about.html
  right:
    - icon: fas fa-hiking
      href: https://2018-fall-sds-albert.slack.com/


