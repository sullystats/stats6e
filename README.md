# Welcome to the Data Site for Statistics: Informed Decisions Using Data 6e by Michael Sullivan, III

   ![](cover.png)

All the data on this site can be retrieved using the URL  `https://sullystats.github.io/stats6e/Data/Chapter_x/*.txt` All data files for this text are coded as Chapter_Section_Problem.txt.  

For example, the data set for Problem 11 in Section 1.3 is named 1_3_11.txt. Therefore, the file has a URL of `https://sullystats.github.io/stats6e/Data/Chapter_1/1_3_11.txt`.

## Loading Data into StatCrunch from Github

From the StatCrunch spreadsheet, select 

When you are setting up your repository, you will be logged into GitHub and at a URL like this: `github.com/`*your_user_ID*`/`*your_course_name*.

When your students look at the repository, or when you make links to data files, etc., the URL will look like *your_user_ID*`.github.io/`*your_course_name*. Make sure it's clear to you how the GitHub user URL differs from the URL for students.

We're going to do some setup for your site, e.g. customizing the front page, adding data files, etc. So check that your Setup Tab is on the GitHub user site: `github.com/`*your_user_ID*`/`*your_course_name*. 

You can see a list of files, starting with a folder called "docs". The docs folder is where you will put all of the materials for your web site. Click on the name "docs" and you will see what files are already in the directory.  There are two:

- `test.csv` - a really small CSV data file
- `index.md` - a text file containing the front page of your new site.

What might confuse you is that the site URL from the students' point of view is something like `http://`*your_user_ID*`.github.io/`*your_course_name*, which does not include the word `docs`. Get used to it. The URL really does point to the `docs` directory. And, since there is a file called `index.md` in the `docs` directory, per the standard behaviour of web sites the contents of `index.md` are what will be displayed when someone points their browser to your `github.io` site.

## Customizing your site

Mostly, you're going to do two things with your site:

1. Upload data files from your own computer into the `docs` folder on your site. Conveniently, there is an "Upload Files" button just for this purpose.
2. Edit the `index.md` file. To do this, click on the name `index.md`, which will open the file. You will see a little pencil icon; press that to edit the file. When you're done with your edits, scroll down and press the green "Commit changes" button. That simply saves your work. As soon as you've done this, the modified page is live on your web site, but it might take a few minutes and a refresh of your browser to see it.

## Putting links to data files on your own course web site

If you are going to use your site to provide student access to data sets of particular interest to you, you will want to put links and instructions on your course web site.

The markup that you include in your `index.md` file (in the `docs/` directory) might look like this:

````
## Data files

Data files for this week:

- `https://dtkaplan.github.io/stat101/test.csv`

To create the data table in your R session, copy and paste 
this command into your console:

```r
My_data <- read.csv("https://dtkaplan.github.io/stat101/test.csv")
```
````



