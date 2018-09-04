+++
banner = ""
categories = ['high-performance-computing']
date = "2018-08-26"
description = ""
images = []
menu = ""
tags = []
title = "Scaling analysis and Performance optimization of the Weather Forecasting Model at NCAR"
+++
I spent another exciting summer working on yet another open source project. This time it was during my internship at NCAR (National Center for Atmospheric Science and Research). I worked on the Weather Forecasting Model, originally developed at NCAR and being used by over 30,000+ users all over the world. I did a lot of bash scripting (pertty basic though) and python programming as well to help me automate running jobs on Cheyenne Supercomputer and gather a lot of performance results.
<br><br>
The Weather Research and Forecasting (WRF) model is a mesoscale numerical weather prediction (NWP) system extensively used in atmospheric research, operational forecasting and educational settings. My internship focused on analyzing the scalability of the model and finding performance improvements. During the internship, I compared WRF's performance against various compilers and MPI libraries along-with several optimization options that are available. I also tested Hybrid parallelization of model by varying number of MPI tasks and OpenMP threads with different processor binding strategies. The simulations use datasets obtained from NCEP with different grid sizes. For e.g. Hurricane Katrina data was used at 1km and 3km resolution. The benchmarks were performed on NCAR's current HPC platform, Cheyenne, which uses Intel Xeon E5-2697V4 (Broadwell) processors. WRF is a highly scalable model and the analysis shows that all cases scale similarly. The scaling analysis provided would also benefit users in selecting the best settings currently available to run WRF on Cheyenne and understand how the model's performance would vary at different node counts. This helps to estimate the number of core-hours that would be required for different problem sizes. More detailed analysis can be found <a href="https://www2.cisl.ucar.edu/siparcs-2018-dixit-patel">here</a> through my talk that I gave at the end of the internship. Feel free to contact me if you have questions! 