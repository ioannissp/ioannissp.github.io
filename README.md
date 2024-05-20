# Personal portfolio website

This is the directory for my personal portfolio website. In this file you will find all the information needed to reproduce this website on your computer.

The project is called *ioannissp.github.io*, because this is the address of my website on github pages. Due to technical issues I have not uploaded the website yet, but I will do it soon.

-The purpose of this website is to showcase my skills in Data Science and let other people interact with my projects.

-Also, the projects I have included aim to give a different, more collaborative perspective on Data Science, that's why they focus on concepts that are relevant when working with other people.

I created this website using Quarto. You can get a comprehensive guide on how to download Quarto here: <https://quarto.org/docs/get-started/>

Our project is not a common Data Science project and as a result this project directory is different from the usual project directory structure. Below we give a description of what each folder contains. We have omitted all folders that were not relevant to our project. For example, Quarto websites do not use functions to be built and as a result the project directory does not have a source/ folder. We note that our project is the website and not the projects uploaded in the website.

**data/**: This folder contains all the image data we are using for the website in the *raw* folder. The images' first part of the name indicates the .qmd files they are used in, while the last part is their name. The numerical data we are using for our projects are in the make file folder and more specifically in the *listing_projects* folder, since they are used for the projects uploaded on our website and not for the building of our website.

**reports/**: The reports folder contains everything you need to render the website. Specifically, *index.qmd* is the main file which you render to produce the website. Then *_quarto.yml* is the file that organises the structure of the website. Our website's home page is *index.qmd*, while we have *projects.qmd* to list our projects. *Projects.qmd* lists the projects we have in the *listing_projects* folder and gives information about their title, subtitle, image and date. We have three projects that are in the *listing_projects* folder, the *theeconomist.qmd* that has image *theeconomist_economistlogo.png* and contains a project that plots financial data from a survey using the "Economist" style guide. Then, we have the *snp500rvest.qmd* project with image *snp500rvest_snp500.png*, which is a project that uses web scraping to obtain S&P 500 annual returns data from the web. In the end, we have *dataexploration.qmd* that shows how a proper exploratory analysis on the iris dataset would look like. The image of this project is *dataexploration_dataexpl.png*.

To run this website you can just render the *index.qmd* file from the *reports* folder. If you want to commit any changes to the website you can change what you want and commit the changes on github using git bash. This directory is connected with the *ioannissp.github.io* repository, so they changes will be automatically passed there. For any questions or comments you have please contact me here: is323@ic.ac.uk
