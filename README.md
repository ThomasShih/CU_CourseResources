This is a repository of markdown files meant specifically for students as a supplementary study resource. 

I do not promise that all the study material is of my own work. If it is not, you will clearly find that the material is a link to a third party source, or you will find the credits to contributing authors at the bottom of the document.

The site is broken up to courses and chapters, a course is selected via the left navbar and displays courses offered by Carleton University (course code). Each course has an associated JavaScript object entry in which contains a list of chapters(topics) that is associated to that course. The file containing the JavaScript objects is courseList.js in assets.

*Why is it done this way?*

**Because we might bring on different course codes that teach part of the same material, such as a calculus for engineering, and a calculus for business. Each of the different course codes can point to the same "calculus" chapters.**

Contributions are welcome! 

Here is the *two* main sections for contribution:

1. Coding and development.
2. Writing new course content

## 1. Coding and Development

The website is built from the ground up using React, work still needs to be done making the website responsive (currently its desktop only), improving UI/UX, supporting new content in markdown, and most importantly; **reducing the amount of bandwidth** this website needs to grab course materials.

The main reason why reducing bandwidth is important is because I am also a student like everyone else, this site is currently hosted via netlify and they have a data cap for free use. We can't go over this data cap... 

## 2. Writing new course content

Any content for any course is welcome to contribution. However, as bandwidth is the primary constraint, I ask everyone to write the chapters in plain text using the markdown format. PDFs and word documents are wonderful, but they would eat my data cap alive. 

To contribute,  simply write a chapter in markdown format, and submit a pull request. If you want to append the chapter information into the course courseList.js feel free to do so. If you are not experienced in GitHub, but still want to help out, please send a email to thomasshih@cmail.carleton.ca with your markdown file and I can add it on for you!

As for how to create a markdown file, I recommend using [Typora](https://typora.io/). As markdown files are essentially code, Typora can asset you in visualizing what your document looks like.

## How to contribute
Please indicate what you are working on in the "issues" page once you start working on something. Just assign a new issue to yourself and use the apporiate labels. Before starting work on contributions, please visit the "issues" page to see if someone else is already working on the feature/chapter.

For coding and development, please modify either this repository, or the database [repository](https://github.com/ThomasShih/CU_ResourceDatabase). 

For new course content, please submit a pull request to the database [folder](https://github.com/ThomasShih/CU_ResourceDatabase/tree/master/markdownFiles). For now, I will manually pull it, and add it into the database register, I will come up with something else that doesn't involve me in the future.

