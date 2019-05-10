# pp-sandbox
Project ideas starting documentation and research.

## Structure of my GitHub
I will have various purposes of this account. Ranging from a record of my university work to personal project and paper reviews/interesting research areas. 

All projects will have a prefix (as shown below) which means they fall into the following catergories: 

Project Type  | Prefix
-------------: | :-------------
Personal project  | pp-
University  | uni-csXXX-
Interview prep  | intv-
Online courses/tutorials  | course-
Miscellaneous  | msc-


## Purpose 
This repo is to keep a record of the random ideas I have and minor documentation for said projects. When the ideas begin to take shape I will move them to their own repo with the prefix "pp-" to denote that they're a personal project. 


## The Sandbox 

* BTS song reccomendation 
    * Python
        * With libraries: [Spotipy](https://spotipy.readthedocs.io/en/latest/), and [Pandas](https://pandas.pydata.org/) (to get data on songs), 
    * MySQL
    * [Starting point?](https://towardsdatascience.com/how-to-build-a-simple-song-recommender-296fcbc8c85)
    * [Example of unsupervised approach using key, tempo, etc](https://towardsdatascience.com/music-to-my-ears-an-unsupervised-approach-to-user-specific-song-recommendation-6c291acc2c12)
    * [Data science of Kpop](https://towardsdatascience.com/the-data-science-of-k-pop-understanding-bts-through-data-and-a-i-part-1-50783b198ac2)
* Evolutionary Art Algo 
    * Try with BTS or african print 
* NLP 
    * Write a song based off lyrics of an already given song e.g. BTS, Janelle Monae, Lizzo, Kojey Radical, Anderson Paak., Childish Gambino etc (lol its going to be crazy)
* Would you rather 
    * Python
* Feed in RGB colours, decide if the text is over the top should be light or dark for it to be readable
    * Python (?)
    * Implements some ML concepts
* Iris flowe diffrentiation 
    * Python
    * Sklrearn or tensorflow
* Determine if Jedi or Sith based on colour of weapon
    * Colour, culture(Sith or Jedi), blade type/# of blades
* Bangtan bot 
    * Twitter 
        * Creates random sentence with the members names in 
    * [Medium article on east setup of bot](https://medium.freecodecamp.org/easily-set-up-your-own-twitter-bot-4aeed5e61f7f)
    * [Botwiki resource on the difinitive guide](https://botwiki.org/resource/tutorial/how-to-make-a-twitter-bot-the-definitive-guide/)
* Update [fitton.co.uk](http://fitton.co.uk/index.html) site 
    * HTML
    * CSS
    * JavaScript
    * Base link for eeryones portfolios 
    * Update email with changed surname
    * Family photo gallery
    * Quick thoughts page
        * for family blog posts i.e. what we have been up so, something funny/great happens at home, I can update mum and dad when I'm at Uni by updating the page and vise vers.
* Website for Kojey Radical
    * HTML
    * CSS
    * JavaScript
    * Doesn't have an existing artist page, do some research on how other artist have their work set out to get inspiration
* Smart Mirror
    * Update: April 2019 - Out of budget atm 
    * [Rasberry Pi](https://www.makeuseof.com/tag/6-best-raspberry-pi-smart-mirror-projects-weve-seen-far/)
    * [The original Magic Mirror](https://github.com/MichMich/MagicMirror#installation)
* Semantic stuff 
    * [overarching topic of group using ML](https://medium.com/@nguy3409/discovering-overarching-themes-of-kpop-boy-band-bts-using-machine-learning-246c69115ac8)



### Tutorial Sandbox
This is a temporary store for the links of courses and tutorials that look interesting (both free and priced). Once the course is started the projects will be moved to a different repo with the prefix: course-, as shown above. 

* [Deep Learning Foundation Nanodegree at Udacity](https://eu.udacity.com/course/deep-learning-nanodegree--nd101)
* [Machine learning course at Udemy](https://www.udemy.com/courses/search/?src=ukw&q=machine+learning)
* [Generative art using strings](https://simpleprogrammer.com/python-generative-art-math/)
  * Python
* [Learning how to learn at Coursera](https://www.coursera.org/learn/learning-how-to-learn) --it's free!
* [Skillshare - Machine Learning and Data Science by Frank Kane](https://youtu.be/uBaU-n77B2Q?t=134)
    * Use affiliate link


### Certifications Sandbox
* AWS
    * Solutions architect 
        * What can be done
        * Exam based
        * Prep available on Udemy
    * DevOps
        * How things can be done 
        * Exam based
        * Prep available on Udemy
* Redhat
    * Certificate of Expertise in Ansible Automation
        * Performance based 
* Microsoft
    * MTA: Microsoft Technology Associate 
        * Entry level
        * No pre-requisites
    * MCSA: Microsoft Certified Solutions Associate
        * Pre-requisite: tech through existing skills or MTA certificaton 
    * MSCE: Microsoft Certified solutions experties
        * IT professionals, 
        * Pre-requisite: MCSA
    * MCSD: Microsoft Certified Solutions Developer
        * IT professionals, focused in programming/engineering
        * Pre-requisite: MCSA
    * MOS: Microsoft office specialist 
        * demonstrates proficienct in Microsoft Office Programs
* Cloudera
    * CCSS Spark and Hadoop Developer Exam (CCA175)
        * Spark, Scala, Python etc. 
* Google
    * Google Developers Certification
    * Associate Android Developer
    * Mobile Web Specialist 
    * Google Cloud Certified - Professional Cloud Architect 
    * Google Cloud Certified - Professional Data Engineer
    * Google Cloud Certified - Associate Clound Engineer
    

## Girl, it's not THAT hard to update the Git
* For all must navigate to where to be accessed in right directory
* Try and remember to update before you start working on a new doc so that you have the most recent version of the repo.
    * BUT DONT UPDATE AFTER YOU HAVE EDITED A FILE otherwise your work will be overwritten with what is currently on the Git aka not good!
### Pull/Clone 
* `git clone [url]`

### Update
* `git pull`

### Add work to repo
* `git add .` OR `git add [filename]`(adds all vs chosen file)
* `git commit -m "comment"`
* `git push origin` OR `git push -u origin branch_name`