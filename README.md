# Personal portfolio website

This is the directory for my personal portfolio website. In this file you will find all the information needed to reproduce this website on your computer.

The project is called *ioannissp.github.io*, because this is the address of my website on github pages. Due to technical issues I have not uploaded the website yet, but I will do it soon.

-The purpose of this website is to showcase my skills in Data Science and let other people interact with my projects.

-Also, the projects I have included aim to give a different, more collaborative perspective on Data Science, that's why they focus on concepts that are relevant when working with other people.

I created this website using Quarto. You can get a comprehensive guide on how to download Quarto here: <https://quarto.org/docs/get-started/>

Our project is not a common Data Science project and as a result this project directory is different from the usual project directory structure. Below we give a description of what each folder contains. We have omitted all folders that were not relevant to our project. For example, Quarto websites do not use functions to be built and as a result the project directory does not have a source/ folder. We note that our project is the website and not the projects uploaded in the website.

**reports/**: The reports folder contains everything you need to render the website. Specifically, *index.qmd* is the main file which you render to produce the website. Then *_quarto.yml* is the file that organises the structure of the website. Our website's home page is *index.qmd* and the image used for it is *mainpage.jpg*, while we have *projects.qmd* to list our projects. *Projects.qmd* lists the projects we have in the *listing_projects* folder and gives information about their title, subtitle, image and date. We have three projects that are in the *listing_projects* folder, the *theeconomist.qmd* that contains a project that plots financial data from a survey using the "Economist" style guide. Then, we have the *snp500rvest.qmd* project, which is a project that uses web scraping to obtain S&P 500 annual returns data from the web. In the end, we have *dataexploration.qmd* that shows how a proper exploratory analysis on the iris dataset would look like. The related images have the same names as the projects. We decided to name the images and project with informative names of their content, since they do not follow any logical order.

**.gitignore, .gitattributes and .git**: These files are not intended to be used by the user who wants to build the website and are there for specific cases. You can ignore them.

In the end, if you have any questions or comments to make you can contact me here: is323@ic.ac.uk
