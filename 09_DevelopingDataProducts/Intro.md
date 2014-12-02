##Statistical Inference: On rCharts
It was pointed out in the forums that rCharts may need to be installed from devtools if you have a recent version of R. Here's the note from Ramnath

https://github.com/ramnathv/rMaps/issues/54

The devtools package on cran is a must to install. Its most useful function is the ability to install packages from github. Note, if you're on windows, I would suggest installing rtools. This allows you to build R packages (and R itself). 
http://cran.r-project.org/bin/windows/Rtools/

======

##Introduction and welcome
Hi class,

A couple of first week housekeeping items. First, make sure that you've had R Programming and the Data Scientist's Toolbox. Reproducible Research would be helpful, but is not mandatory. We're running all classes monthly now, so it's worthwhile considering delaying this class until you've had those. At a minimum you must know: very basic git, basic R and very basic knitr.

An important aspect of this class is to peruse the materials in the github repository. 
All of the most up to date material can be found here

https://github.com/bcaffo/courses/tree/master/09_DevelopingDataProducts

You should clone this repository as your first step in this class and make sure to fetch updates periodically.
(Please send pull requests too!) It is one of the most essential components of the Specialization that you start to use 
Git frequently.
We're practicing what we preach as well by using the tools in the series to create the series, especially git.

You can clone the whole repo with (http)

git clone https://github.com/bcaffo/courses.git

or (ssh)

git clone git@github.com:bcaffo/courses.git

The lectures are in the index.Rmd lecture files. In this class, 
we'll cover how to create these sorts of slides.You will see all of the 
R code to recreate the lectures. Going through the R code is the best way to
familiarize yourself with the lecture materials.

If you'd like to keep up with the instructors 
I'm (add)bcaffo on twitter, Roger is (add)rdpeng and Jeff is (add)jtleek. The Department of Biostat here is (add)jhubiostat.

Since today is the first day running all 9 courses simultaneously, we'll be live tweeting at (hash)jhudatascience.


=====

### Developing Data Products: Week 1
Welcome to Week 1 of Developing Data Products. This week we'll cover Shiny, Rcharts and googleVis. Make sure to watch all of the videos. When you feel that you are ready, you can demonstrate your knowledge by taking Quiz 1, which is due by 11:30 PM UTC on Sunday.

Please visit the [Data Science Specialization github repository] (https://github.com/DataScienceSpecialization/courses) to pull the latest version of the course materials.

Also, the Course Project details are available by clicking the Course Project link in the left navigation bar. Your project is due BEFORE 11:30 PM UTC on the Sunday at the end of Week 3.

I'm glad that you decided to take Developing Data Products, part of the [Data Science Specialization](https://www.coursera.org/specialization/jhudatascience/1?utm_medium=listingPage) from Johns Hopkins Biostatistics!

A data product is the production output from a statistical analysis. Data products automate complex analysis tasks or use technology to expand the utility of a data informed model, algorithm or inference. This course covers the basics of creating data products using Shiny, R packages, and interactive graphics. This course focuses on the statistical fundamentals of creating a data product that can be used to tell a story about data to a mass audience.

You will learn how communicate using statistics and statistical products. Emphasis will be paid to communicating uncertainty in statistical results. You will learn how to create simple Shiny web applications and R packages for their data products. In addition, we'll cover reproducible presentations and interactive graphics.

We believe that the key word in Data Science is "science". Our specialization is focused on providing you with three things: (1) an introduction to the key ideas behind working with data in a scientific way that will produce new and reproducible insight, (2) an introduction to the tools that will allow you to execute on a data analytic strategy, from raw data in a database to a completed report with interactive graphics, and (3) on giving you plenty of hands on practice so you can learn the techniques for yourself. This course represents the final cog in a data science application, creating an end-usable data product.

We are excited about the opportunity to attempt to scale Data Science education. We intend for the courses to be self-contained, fast-paced, and interactive. We intend to run them frequently to give people with busy schedules the opportunity to work on material at their own pace.

Finally, we are interested in hearing about your reasons for taking this course and your intentions for the Data Science Specialization. Please take a few moments to complete our Pre-Course Survey: https://www.surveymonkey.com/s/8CW2XZJ?user_id=412b59036f2efd0411c89f4f445c52854c84a12a

Have a great week!

Brian and the Data Science Specialization team
