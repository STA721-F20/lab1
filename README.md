# STA 721 Lab1  8/30/2019

## Overview
 
In this lab 

* we will cover using RStudio on the department server or a laptop
* demonstrate using Sweave to produce pdf files using LaTeX with embedded R 


For why Reproducible Research is important read [Yihui's post](https://yihui.name/en/2012/06/enjoyable-reproducible-research/)  (and watch the video in the blog about what happened at Duke when Reproducible Research was not used!) or review CaseStudies from the 
[2018 StatSci Computing Bootcamp](https://github.com/DukeStatSci/computing-bootcamp-2018)

In case you missed the Bootcamp this summer, you may watch the Computing recording from [Zoom](https://github.com/shawnsanto/computing_bootcamp_2020)


## Preliminaries

A couple things to get everyone on the same page,

1. If you don't have one, sign up for a GitHub account (it takes 1 min.)

  * Go to https://github.com/join
  * Enter your information
  

Ready?


## Start R Studio

If you have a StatSci account,   
   1) Open RStudio on knight [http://knight.stat.duke.edu:8787](http://knight.stat.duke.edu:8787) and login with your Duke netid and password.   If you are unable to login to knight in lab and you have connected to the Duke VPN, please see the TA or instructor.  Email clyde@duke.edu and provide your Full Name and netid so that your account can be created.
   2) Next change some RStudio preferences. Go to Rstudio -> Preferences -> Sweave and make the following two changes:
    * Select "Sweave Rnw files using Knitr"
    * Set "Preview PDF" with "System Viewer"
   3) Clone the repository through the link from Github Classroom
   and accept the invitation.  This will create a repository  https://github.com/STA721-F20/lab1-yourname
   4) Create a new Project.  In RStudio, click on New Project in the file menu.  Select Version Control, then Git. Enter https://github.com/STA721-F20/lab1-yourname.git  in the  Repository URL field, provide a name for the project, e.g. 'lab1', and select a directory to save your work, e.g. Lab1    We suggest that you make a folder for STA721 to save your work for the course.
  5) On the lower right panel in RStudio, click on the Files tab. You should see a listing of the files in your directory. Click on `lab1.Rnw` to open it in the RStudio editor and then follow instructions there.  
   
  


  For more on getting started using RStudio and git see the [StatSci ComputingBootcamp slides](http://github.com/DukeStatSci/ComputingBootcamp2018/blob/master/slides/computing_bootcamp_2018.Rmd) and other materials at  [StatSci ComputingBootcamp](http://github.com/DukeStatSci/ComputingBootcamp2018/)
  
For more info on Sweave in Rstudio see the [RPubs page](https://rpubs.com/YaRrr/SweaveIntro))
