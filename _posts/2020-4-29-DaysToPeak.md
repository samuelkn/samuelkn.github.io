---
layout: post
title: "Corona - Days to peak"
author: "Samuel Knapp - samuel.k@gmx.de"
Description: Days to reach peak of daily confirmed cases
date: 2020-04-29
categories: rblogging
tags: corona
editor_options:
  chunk_output_type: console
output:
  md_document:
    variant: markdown_github
    preserve_yaml: true
  html_document:
    keep_md: true
    code_folding: none
    toc: false
    toc_float: true
    df_print: paged
    includes:
      in_header: analytics.html
  pdf_document: default
#cls: crop-science.csl
#bibliography: lib.bib
---

Download data
=============

Data were downloaded from the github repository of the Johns Hopkins
University. These are the same data, from which the famous GIS world map
is created. See:
<a href="https://github.com/CSSEGISandData/COVID-19" class="uri">https://github.com/CSSEGISandData/COVID-19</a>

This was last updated

    ## [1] "2020-04-27"

![](DaysToPeak_files/figure-markdown_github/WithPeak-1.png)
