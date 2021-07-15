
* A collection of Data Science Learning materials in the form of IPython Notebooks.
* Associated data sets.

The initial beta release consists of four major topics

* Linear Regression
* Logistic Regression
* Random Forests
* K-Means Clustering

Each of the above has at least three IPython Notebooks covering

* Overview (an exposition of the technique for the math-wary)
* Data Exploration (the nuts and bolts of real world data wrangling)
* Analysis (using the technique to get results)

One or more of these may have supplementary material.
Each of these have worksheets that contain mostly the code sections so you can iteratively explore the code.

Three openly available data sets are used.  

* For the Linear and Logistic Regression we use a data set on loans and interest rates provided by Learning Club http://learningclub.com  
* For Random Forests we use a data set of Android accelerometer and gyroscope readings used to predict body position and motion from the Human Activity Recognition project
http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
* UN data on economic indicators of countries

Installation  
------------

* Prerequisites  
One of the following distributions is needed. Please note that even if you have Python installed it is important to have one of these distributions installed and the binary for this installation in your path. This is because these distributions come packaged with all the supplementary libraries needed and these have been historically difficult to install separately.

  * EPD Free Enthought Python Distribution from http://enthought.com
  * Anaconda Python from http://continuum.io
  * Development has been done on v 1.5 of Anaconda distribution but EPD Free should work just as well.

* The following steps assume you have installed one of the distributions mentioned in prerequisites.

* From a zip or tar file
    * download the zip or tar file 
    * unpack the file to a directory called learnds
    * cd to the 'notebooks' subdirectory
    * start IPython Notebook 'ipython notebook --pylab=inline'
 
* From the git repo
    * clone the repo
    * cd to 'notebooks'
    * start IPython Notebook 'ipython notebook --pylab=inline'