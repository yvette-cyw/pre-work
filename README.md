# Pre-Work for SQL Workshop

## Download Data

Please download the [Open University Learning Analytics Data Set](https://analyse.kmi.open.ac.uk/open_dataset). 

## Installation & Account Setup

The following instructions set up the software and online tools that you will be using for this workshop. Below there are links and instructions to relevant sites.

## Create Accounts

The first step is to create a [Github account](https://github.com/join?source=header) if you do not already have one. Then create an [Amazon Web Services](https://aws.amazon.com/) account. **Note 1:** You will need a credit card to create an account but we will only use the free services as part of this workshop. **Note 2**: If you already have an Amazon account associated with the email you ise (EG - for shopping) then this process will change the password to that account as well. 

Next you will need to install the software we will be using (if you already have them installed make sure they are the latest versions):
   * R
   * RStudio
   * Git
   
**If you already have R & RStudio Installed please make sure that all packages and versions are updated**
   
## Installing R
* Choose a [download mirror site](https://cran.r-project.org/mirrors.html) from the list that is close to you geographically  
* Download the version of R that is appropriate to your operating system
* Install R in a manner appropriate to your operating system ([MacOSX](https://youtu.be/Ywj6yNfc5nM), [PC](https://youtu.be/5ZbjUEg4a1g))

## Installing RStudio (Graphical User Interface for R)
* Download the free version of [RStudio](https://www.rstudio.com/products/rstudio/download/)
* Install RStudio in a manner appropriate to your operating system ([MacOSX](https://youtu.be/Ywj6yNfc5nM), [PC](https://youtu.be/5ZbjUEg4a1g))

## Installing Git
* Git is a version control system to keep track of our work and collaboration
* Instructions for setup can be found [here](https://help.github.com/articles/set-up-git/) and [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* Download [Git](https://git-scm.com/downloads) 

## Connecting Git-Github-RStudio
* You will also need to link your Github account to RStudio by following [these instructions](https://support.rstudio.com/hc/en-us/articles/200532077-Version-Control-with-Git-and-SVN) or [these instructions](http://happygitwithr.com/rstudio-git-github.html)
* Once you have connected test your connection by forking this repository (top right of this page) then cloning your new repository (green button, copy the URL). Then in RStudio click `File` -> `New Project` -> `Version Control` -> `Git` and paste the URL into the top box

*Two common errors:* 

**Error 1** 

`error: unable to read askpass response from 'rpostback-askpass'`

The fix for most systems is:

* In RStudio, click on the "Tools" menu and select "Shell"
* Run the following command: `git push -u origin master` (*it might ask you for your git username and password. Supply this information, make sure it is correct*)
* Close the window
* Now make some more edits to some file so that you have new content to push click on the "push" button in RStudio and this time the push should work

**Error 2**

You are using a Mac and you cannot access Git when you try to create a new project through `Version Control`.

* Open `Tools` -> `Global Options` -> `Git/SVN`
* In the top box make sure that the file path reads:
`usr/local/git/bin/git`
* If it does not click on `Browse` and locate that file

done