+++
banner = ""
categories = ['Data processing','GSoC']
date = "2017-09-21"
description = ""
images = []
menu = ""
tags = []
title = "Data processing pipeline with Spring Batch"
+++

I spent a very exciting summer working on an open-source project through the <a href="https://summerofcode.withgoogle.com/">Google Summer of Code program</a>. Kudo's to Google for hosting such an amazing program. The project was challenging both technically as well as personally. I had the opportunity to learn a lot about Bioinformatics, from an amazing team of experts at the <a href="https://www.mskcc.org/"> Memorial Sloan Kettering Cancer Center </a> (MSKCC). MSKCC is a leading cancer treatment center in United States (and the first to get an NCI designation!) that houses physicians as well as scientists to collaborate for cancer research  (So cool!).
<br><br>
My project was to develop a data pipeline for importing cancer genomic data from a repository maintained by the National Institute of Health into <a href="http://www.cbioportal.org/">cBioPortal</a>, a cancer visualization and analysis tool. This data was previously unavailable to the research community. I developed this using Spring-Batch that provides a very awesome framework to develop robust batch applications that are very common in enterprise systems. My previous work at Rakuten also involved writing/fixing a lot of batch modules and I could compare how effective this framework is in terms of the flexibility it provides (writing a simple or a complex application) as well increasing developer efficiency while building and maintaining a complex code-base. I'd definitely consider using this framework for my future data processing related work as well! More techincal details about the project are on the github page here : <a href="https://github.com/cBioPortal/gdc-et-pipeline">GDC Pipeline</a>. The development code currently resides in the <a href=""https://github.com/cBioPortal/gdc-et-pipeline/tree/gsoc-development>gsoc-development-branch</a>
