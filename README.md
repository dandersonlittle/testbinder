# testbinder

Post-op:

This was my first ever github repo! Hooray!
I had completed all of the essential tasks of my Assignment1. Before editing the Assignment, I wanted to make sure I had my turn-in mechanism down. 

The professor requested that we turn in an R file and a word document / email body of some of our essential results. I much preferred the approach of doing a Jupyter notebook with an R runtime environment because it allowed me to write my comments and tables in-line. 

The final solution was using: https://htmtopdf.herokuapp.com/ipynbviewer/ to convert my ipynb into a pdf for a turn-in. Only one convert a day, so be careful that you are converting your final file into a pdf. 

Process of getting there:
I wanted to create a runtime environment that the professor could use and re-run my data. Sharing a Google Colab document works pretty well--all of the code runs and the output is saved when someone else views the code. This is a great approach, but I wanted to allow the professor to interact and recode my project. I was exploring the Google Colab export options. One of the options allows an export to GitHub, so I tried just that. 

I wanted to upload my dataset to GitHub as well, but I found that I had an upload size limit on my GitHub account. I configured Git Large File Storage and paid $5 to upload the file. There was some command line interface on the uploading, and it should be pretty easy to repeat. In this process, I realized I needed to configure my SSH keys for GitHub, and now I am pretty much completely setup to do future git pulls and pushes. 

Once I had the data and .ipynb uploaded to GitHub, I wanted to use mybinder.org to host my live runtime environment. Basically, you export your Git repo to their service, and they create & host a Docker runtime environment where your code and dataset can be interacted with. This is where I quit in this process. Perhaps if I was running a basic Python environment, it would have been a simpler configuration. It was getting late, and I needed to configure my Docker environment in R and install extra libraries. I think I could figure it out if I put my attention on it, but for now, I have punted on this project as it is totally a nice-to-have, and I think my professor prefers a pdf anyway. 

I am a real coder now--I have a GitHub and a live connection to my laptop. Let's go. More to come.
