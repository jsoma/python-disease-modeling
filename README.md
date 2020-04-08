# Modeling disease spread Python

**A walkthrough of how SIR infectious disease modeling works**, along with a do-it-yourself Python COVID model that you can use to simulate a lockdown.

If you work through the videos and the notebooks you'll end up with a pretty solid foundational understanding of how COVID models work. You'll also (hopefully) understand how small changes in concepts like "how many people does an average person interact with each day?" can create a large difference in how many people end up infected.

## The videos

You'll want to check out [the YouTube playlist](https://www.youtube.com/playlist?list=PLewNEVDy7gq1w-CbbPUowTHaHZWSt-Ojc), but hey, I've broken it down here anyway:

1. [What is disease modeling? Intro to the SIR model.](https://www.youtube.com/watch?v=VIlsJas54-g&list=PLewNEVDy7gq1w-CbbPUowTHaHZWSt-Ojc&index=2&t=0s)
2. [Contact rate and removal rate in the SIR model of infectious disease](https://www.youtube.com/watch?v=K0fv4wVwPNY&list=PLewNEVDy7gq1w-CbbPUowTHaHZWSt-Ojc&index=3&t=0s)
3. [Breaking down R0 in epidemic models](https://www.youtube.com/watch?v=7DcSsN3gTu8&list=PLewNEVDy7gq1w-CbbPUowTHaHZWSt-Ojc&index=4&t=0s)
4. [Building a COVID disease model in Python (with shelter in place)](https://www.youtube.com/watch?v=ITUiX5Fpmm4&list=PLewNEVDy7gq1w-CbbPUowTHaHZWSt-Ojc&index=5&t=0s)

You need the videos. Just looking at the notebooks would be a crime.

## The notebooks


First, the not-very-attractive [Basics of COVID modeling](blob/master/Basics%20of%20COVID%20modeling.ipynb)
We have two notebooks here. notebook, which is me scrawling down words and phrases as I work through the videos above.

Then, [Disease modeling in Python](blob/master/Disease%20modeling%20in%20Python.ipynb), which is a do-it-yourself SIR model where you can put in different effective contact rates and removal rates and see how things shake out.   

The first one is not terribly interesting, and you can get all of its contents out of watching the video. The second one is worth taking a peek at, and it also includes some **homework problems!**
