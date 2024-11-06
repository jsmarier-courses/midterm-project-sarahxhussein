**November 4 2024**<br>
**MPAD2003 Introductory Data Storytelling**<br>
**Sarah Hussein**<br>
**Presented to Jean-Sébastien Marier**<br>

# Midterm Project: Exploratory Data Analysis (EDA)

Use one hashtag symbol (`#`) to create a level 1 heading like this one.

## Foreword

For this assignment, you must extract data from a dataset provided by the instructor. You must then clean and analyze the data, create exploratory charts/visualizations, and find a potential story idea. Your assignment must clearly detail your process. You are expected to write about 1500-2000 words, and to include several screen captures showing the different steps you went through. Your assignment must be written with the Markdown format and submitted on GitHub Classroom.

I have been assigning different versions of this project to my digital journalism and data storytelling students for a few years now. Its structure was inspired by the main sections/chapters of [*The Data Journalism Handbook*](https://datajournalism.com/read/handbook/one/). This version was further inspired by the [Key Capabilities in Data Science](https://extendedlearning.ubc.ca/programs/key-capabilities-data-science) program offered by the University of British Columbia (UBC).

**Here are some useful resources for this assignment:**

* [GitHub's *Basic writing and formatting syntax* page](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
* [The template repository for this assignment in case you delete something by mistake](https://github.com/jsmarier/jou4100_jou4500_mpad2003_project2_template)

Did you notice how to create a hyperlink? In Markdown, we put the clickable text between square brackets and the actual URL between parentheses.

And to create an unordered list, we simply put a star (`*`) before each item.

## 1. Introduction

This assignment focuses on the City of Ottawa dataset which provided a large scope of services that are being offered primarily the municipal service requests which is offered on their [website](https://open.ottawa.ca/documents/65fe42e2502d442b8a774fd3d954cac5/about).
This specific dataset for the purpose of this assignment through [github]( https://raw.githubusercontent.com/jsmarier/course-datasets/refs/heads/main/ottawa-311-service-requests-august-2024.csv) providing insight to the types of services the residents of Ottawa are engaged in and it primarily highlights how the municipal recourses are allocated and the distributed overall. The information collected shows how citizens make service requests, that details the nature of the issues and the status of the resolution. Upon initial examination, the dataset is comprised of diverse service categories that include Garbage and Recycling, Parking Control Enforcement, and Bylaw Services. We can gather based on the frequency of service requests, the patterns of municipal concerns throughout the community which enables a better understanding of city infrastructure and most importantly the resident needs.


## 2. Getting Data

###Importing the Data into Google Sheets
To import the City of Ottawa service request dataset into google sheets, I first accessed the data link via Brightspace. By right clicking the link opened up a new page, and from there I clicked on the "file" tab. I proceeded to saved the data as a csv file. In Google Sheets, I clicked on file >  and then "import" and uploaded the CSV, successfully adding it to my existing sheet. Below is a screen capture showing the first few rows and columns of the dataset. 
![](import1.png)<br>


###Observations
The dataset contains 11 columns and 28,538 rows. In the truthful art Cairo says “a visualization is any kind of visual representation of information designed to enable communication, analysis, discovery, exploration”. The visual observation gathered shows a variety of service request with details such as the type, description, and opened: closed dates. Generally, the data appears roughly presentable however there are some entries with missing values in address fields, which may impact viewers understanding. Moreover, the spacing of the columns in addition to some specific entries may denote a further need of clean up for spacing and validity of the data. Further inspecting the columns, there are some specific observations that can be seen. 

*Column B shows a specific “Status” for each service ID number in Column A. They are nominal variables, denoted by their respective category (e.g., Resolved, Active, Cancelled).

*Column G is represented to show the address. Here the information gathered is either denoted by “/N” which means not applicable, or some addresses provided is shown. Two things might be deduced based off of this; suggesting either there are privacy concerns or there might be incomplete submissions.

*Column H and I  shows coordinate data for longitude/ latitude of the respective location. The data is shown for the locations with a specific address that is shown however the ones that don’t have an address can be seen denoted by “/N”.

Looking overall at the data gathered I further analysed that with respect to missing data, it reflects on The City of Ottawa’s mission to upholding the wishes/concerns of its citizens that chose to not share their location for privacy reason. Additionally, the data shows corresponding information with respect to Wards and upon further research, they are denoted numerically by their corresponding zone number from 1-24. 

This assignment can hypothesise that for wards with a higher population density and greater commercial activity could experience more frequent garbage service requests.


## 3. Understanding Data

### 3.1. VIMO Analysis

Use three hashtag symbols (`###`) to create a level 3 heading like this one. Please follow this template when it comes to level 1 and level 2 headings. However, you can use level 3 headings as you see fit.

Insert text here.

Support your claims by citing relevant sources. Please follow [APA guidelines for in-text citations](https://apastyle.apa.org/style-grammar-guidelines/citations).

**For example:**

As Cairo (2016) argues, a data visualization should be truthful...

### 3.2. Cleaning Data

Insert text here.

### 3.3. Exploratory Data Analysis (EDA)

Insert text here.

**This section should include a screen capture of your pivot table, like so:**

![](pivot-table-screen-capture.png)<br>
*Figure 2: This pivot table shows...*

**This section should also include a screen capture of your exploratory chart, like so:**

![](chart-screen-capture.png)<br>
*Figure 3: This exploratory chart shows...*

## 4. Potential Story

Insert text here.

## 5. Conclusion

Insert text here.

## 6. References

Include a list of your references here. Please follow [APA guidelines for references](https://apastyle.apa.org/style-grammar-guidelines/references). Hanging paragraphs aren't required though.

**Here's an example:**

Bounegru, L., & Gray, J. (Eds.). (2021). *The Data Journalism Handbook 2: Towards A Critical Data Practice*. Amsterdam University Press. [https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153](https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153)
