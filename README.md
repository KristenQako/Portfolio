# Kristen Qako Digital Portfolio


  This is the link to my [digital portfolio](https://kristenqako.github.io/Portfolio/)
  
  ## Lab 1: Roman Coin Hoard Data-Set. 
  
  The data can be found here on [Online Coins of the Roman Empire](http://numismatics.org/ocre/)
  
  This data manipulated here was to answer these questions:
  1. How many different authorities strike coins in OCRE's data?  
  2. Who strikes the greatest number of issues? How many?  
  3. What is the smallest number of issues struck by a single authority?  
  
  In this data set, we mapped the data found on column(4) to a vector and counted how many authorities struck coins.
  We then grouped the records by authority and counted them.
  
  The jupyter notebook can be found below:  
  [Coin Hoard Data Set](https://github.com/KristenQako/clas299/blob/master/exploring-a-data-set.ipynb)  
  
  
  ## Interpreting Ptolemy's longitude/latitude data.  
  
  Ptolemy’s Geography includes locations in longitude-latitude coordinates for more than 6,000 points.
  While his scheme of longitude and latitude is the same one we use – 360 degrees of longitude measured from an arbitrary 0 (the origin), and 360 degrees of latitude with 0 at the equator, running to 90 degrees North and 90 degrees south at the poles – his raw data do not fall near the corresponding modern locations.  
  So to manipulate this data and make it more accurate, I used scala code to adjust scale, origin of longitude, and base line for measuring latitude.  
  
  The jupyter notebook can be found below:  
  [Ptolemy's Geographical Analysis](https://github.com/KristenQako/clas299/blob/master/ptolemy.ipynb)  
  
  ## Individual Project: Ancient Lycian Necropoleis  
  
  ### Overview:  
  In ancient Lycia, rock-cut tombs often clustered together in cemetery sites, or necropoleis, like ancient Myra (modern Demre). The set contains data about Lycian necropoleis including the number of tombs at each site. The purpose of the code is to figure out how many total tombs are represented in the data set.  
  
The [data set] can be found here (http://shot.holycross.edu/courses/ada/S20/data/lycianNecropoleis.cex)  

The data set is represented is like this: sitename#ztype#tombcount#comments#ztypetext#rageid  
  
  The jupyter notebook can be found below:  
  [Ancient Lycian Necropoleis](https://github.com/KristenQako/clas299/blob/master/Ancient-Lycian-Tombs.ipynb)  
  
  
 ## Group Final Project: Grouping Lycian Tombs by Ztype 
 
 #### Overview:
  Similarly to the previous individual project of finding the sum of Lycian Tombs, here we take a look at the ztypes of the same data. We ask the question: How many of each zType was found in the data? This jupyter notebook was worked on by Michael Dahlquist, Sean Sullivan, and I.
  
  The jupyter notebook can be found below:  
  [Lycian Tombs zType Final Project](https://github.com/KristenQako/clas299/blob/master/LyicanTombs_zType.ipynb)
  
  
  
  
