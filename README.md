# UCSD Course Evaluations

This repository contains a data science side project.  While at UCSD, I won a "Graduate Teaching Fellows Award," which granted me the opportunity to teach my own course.  I had a blast teaching and got really good evaluations from students.  Afterwards, I started wondering how well my evaluations stack up against physics courses at large.  The UCSD website (cape.ucsd.edu) is a greate data source, but makes said comparison very difficult.  This repo is my first stab at fixing that problem.  More specifically, there are two aims here:

1. To describe the quality of physics courses at UCSD (insofar as student evaluations indicate quality).
2. To understand what makes a good teacher.  More specifically, to understand which instructor/course characteristics (features) lead to highly recommended instructors/courses.

The basic workflow was:

1. Query the UCSD webpage for all physics course evaluations, then save the results as an html file.
2. Scrape content from said html file, using BeautifulSoup.
3. Put everything in pandas dataframes.
4. Run a multivariate linear regression (coming soon: random forest regression).
