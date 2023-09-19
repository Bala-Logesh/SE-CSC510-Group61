# Essay of Group 61

## [Sentiment Analysis:](https://github.com/mrpudlo/SE_Project1) &#128279;

This project aims to accurately analyze the sentiment of four types of inputs namely,
 1. Text
 2. Document
 3. Product review link
 4. Audio file. 

When running the app on an _Apple silicon Mac_, we faced a lot of issues. Some libraries used for this project belong to a specific version and when trying to install those in Apple Silicon Mac, there were _a lot of dependency mismatches_. We had to update all packages to the latest version to install the app to our local system and even after doing so, we came across deprecated django scripts (Line 19 in [urls.py](https://github.com/mrpudlo/SE_Project1/blob/master/sentimental_analysis/sentimental_analysis/urls.py)). We achieved a workaround in this by running the app in the _Ubuntu environment_ and the errors that came up while installing were relatively easier to solve. After launching the app, we played around with different kinds of inputs and the app worked perfectly for text and document input. 

The app failed to predict the output for audio file and product link. Another thing that we noticed is that the input to the product should be specific(the navigation for the link should be amazon.com -> specific product -> ratings -> all stars ratings). We found this part to be a bit unintuitive. Due to these reasons we decided to not use this app for Project2.

The documentation provided covered all the major aspects. The learnings we could take is that whenever developing an application, the important thing is to update/maintain it after release to the public. We should also make sure that it runs across every platform. These things make our application more robust. We try to keep these things in mind and carry forward this learning during our project 2 phase. 

## [Jobby:](https://github.com/sak007/Jobby) &#128279;

_Jobby_ offers a streamlined approach to job search, promising to make it easier, more efficient, and less frustrating for users. You can upload your resume and job which you want to search for. The application will _browse multiple Job Portals_ to search for jobs that best match your skills and requirements. While the project exhibits significant potential, it also faces challenges in terms of installation and building. 

### Techstack used in building Jobby:
- **_Python_** for its backend logic and data processing tasks.
- **_Flask_**, a lightweight and flexible web framework for Python, to build the web application.
- **_MySQL_** serves as the project's database management system
- For the frontend, the project incorporates **_HTML, CSS, and JavaScript_** to create an interactive and user-friendly interface.
- The project can be hosted locally using applications such as **_XAMPP or MAMP Pro_**, streamlining the testing and development process.

The repository's documentation is detailed and informative, offering insights into the project's objectives, features, and roadmap. Notable enhancements include code refactoring, the addition of new job boards, and an improved user interface. These updates enhance usability and scalability, positioning Jobby as a competitive job aggregator.

However, despite its potential, there are notable challenges in the installation and building process. Setting up the MySQL database and configuring DB credentials require careful attention. The documentation does provide guidance, but further simplification and step by step approach could benefit users, particularly those with limited technical expertise.

In the course of testing and building the Jobby project, we encountered an _error related to the project's codebase or packages_. This error pertained to a fault within the code or its dependencies, which hindered the smooth installation and building process.

## [GITS by Bhavesh Team](https://github.com/bhavesh242/GITS) &#128279; & [GITS by Harshit Team:](https://github.com/harshitpatel96/GITS) &#128279;

_GITS_ project aims at simplifying the complex git commands that are used by millions of developers across the globe. The two GITS projects are very similar to each other but differ in some aspects.

Both GITS projects are small projects that run in the _command line_. The projects were easy to install and run. The dependencies are installed automatically just by following the install instructions provided by them in the _README.md file_. Once the version of GITS is installed, it is as easy as running _“gits hello_world”_ to verify the . 

GITS by the team of Harshit Patel has implemented the installation script for the _fish terminal_ and explained in detail about the installation of GITS in both Linux based OS and Windows. There are also few more git functions implemented in the GITS by Harshit Patel’s team. Both projects use _PyDoc_ extensively to generate additional documentation apart from the documentation they have on the Readme and in the Documentation markdown files.

The projects have all the necessary files including _contributing.md, setup.md, license and code of conduct_. Both projects have good testing code and good code coverage but the tests are not run every time commits or done. There is a lack of proper CI/CD pipeline.

The major issue with both these GITS projects is the _inability to run natively on the Windows operating system_. Both the projects require Windows Subsystem for Linux (WSL) to run them. This makes development of the projects difficult for our team which is one of the reasons we decided not to go ahead with them.

## [SLASH:](https://github.com/NCSU-Group7-SE2021/slash) &#128279;

If you're person who shops frequently and is tired of spending hours surfing around E-commerce websites then you are in the right place. _SLASH_ is a one stop _web scraping API_ which collects all the product details that a user demands and showcases them in one sheet. It provides the best deals from most of the popular E-Commerce websites like _Amazon, Walmart, EBay, Costco, Target_.

SLASH is primarily built to help university students to shortlist  their requirements. It provides real time prices and links in the list. Which makes it very convenient for students to navigate and buy the product. SLASH is built using **_ReactJs, Python and several web scraping packages_**.

However, we have seen certain difficulties in the existing version of Slash. Most of the packages are deprecated and we had to use a separate command to bring those lines of code back live. Specific section of Slash is not functioning properly like the visualization section and the result section in the navigation bar should be made working. Apart from that the project is neat and we have noted down some innovation that can be made to further the impact of the project. Our future work will include.

1. Providing a User Authentication (Login/Register page)
2. Detailing the user interface with real time images of the products.
3. Bug fixing of existing functionalities
4. Adding filters specific to user need
5. Enable push notifications for hot deals/fast selling products.
6. Alerts when there is a price drop in a product after the user has shown to follow this product.
7. Visualization showing the trend of the product across the top few e-commerce websites for the past few months.
8. Providing a SQL/NoSql(MongoDB) database for storing user login credentials.





