## Week 2
## Topics covered in this week :
* To design a fixed-wing drone using the mission parameters.<br/>
* Learn how to analyse a 3D plane design in XFLR5.

This **[video](https://youtu.be/q7c9PCkvIOY?t=660)** consisting wing geometry and MAC, will easily make you understand the topics which are important for the later part of the course,at a single glance.So make sure you do this at very first.

Let’s start with what exactly a mission will typically look like, a mission typically gives you parameters that your UAV should satisfy. It would include 
* Range
* Endurance
* payload
* sometimes even things like takeoff distance.

Now one thing to note is you will never have a single UAV satisfying all the mission parameters, instead, all the parameters of the UAV will lie in a certain range and of course will heavily depend on one another.

Before we go into how to determine these parameters.let’s look at the governing **[equations](https://www.grc.nasa.gov/www/k-12/airplane/cruise.html)** for fixed-wing flight .<br/>

Just to get a flavour for it this is how range and endurance of a fuel powered plane is calculated have a look at this **[document](https://nptel.ac.in/content/storage2/courses/101104007/Module2/Lec9.pdf)**.<br/>
If it is not very clear have a look at the following **[video](https://youtu.be/2NR2eFxaK74)**.

With this info, I want you all to get a brief idea on thrust required and power required, I am giving you a slightly long video but this will give you a recap of everything we did till now and the Power required part which will come very handy in the analysis ahead:<br/>
**[Thrust Required, Power Required: Cruise](https://youtu.be/YDChv27slEE)**


 ## How to go from there to range and endurance of a battery powered UAV?
Remember we said something about it in mission parameters.
Well you just equate power required to battery power: TV = power-required (as done in the last video). Now to equate it with power available from the battery (never forget to use safety factors here no battery has 100% efficiency).  Every battery will have a mAh rating, and a SED (Specific Energy Density), these values are easily available on net, what you can do is with this power of battery comes out to be: <a href="https://www.codecogs.com/eqnedit.php?latex=\bg_white&space;(W_{battery})*SED&space;=&space;T*V*(Time&space;of&space;flight)&space;=&space;\frac{W*V*(Time&space;of&space;flight)}{(L/D)}{\color{Green}&space;}" target="_blank"><img src="https://latex.codecogs.com/png.latex?\bg_white&space;(W_{battery})*SED&space;=&space;T*V*(Time&space;of&space;flight)&space;=&space;\frac{W*V*(Time&space;of&space;flight)}{(L/D)}{\color{Green}&space;}" title="(W_{battery})*SED = T*V*(Time of flight) = \frac{W*V*(Time of flight)}{(L/D)}{\color{Green} }" /></a>
From this you get time of flight which basically is the endurance. 



Just a note this is only for steady level flight, a lot more configurations are possible. If you are interested you could go through the following: 
 * **[Ascent](https://www.grc.nasa.gov/www/k-12/airplane/climb.html)**
 * **[Gliding flight](https://www.grc.nasa.gov/www/k-12/airplane/glidang.html)**.<br/>

Now after this we will cover the **Weight Iteration Technique**. It will be covered in the live session.

## XFLR5
* **[Design a plane](https://youtu.be/vhykE-mVBO4)**
* **[Plane analysis](https://youtu.be/bJddlSRSZGY)**
* **[Reference dimensions](https://youtu.be/VH3M1NQYZPA)**
* **[Design a flapped wing](https://youtu.be/uUQhFh0d4uM)**

And here is the Webinar 1 slides and recording link for your reference.
* **[Slides](https://docs.google.com/presentation/d/1yDpFzJeMpa7GxheA2u-Rbdd2NnsJJzdS3lKUppqSnF0/edit?usp=sharing)**
* **[Recording](https://iitbacin.sharepoint.com/sites/LSAircraftdesignandStabilityanalysisusingXFLR5/Shared%20Documents/General/Recordings/webinar%20of%20week1-20210705_170521-Meeting%20Recording.mp4?web=1)**

The [Assignment 2 - Part 1](https://docs.google.com/document/d/e/2PACX-1vTyw0uwCQbmnYgU9LDFRS7tR3dcKF5RpkU3mRTQTJ_sZhoxoaTZxFasBix9WMPvbtzxs0fMzroh2ZpY/pub) will be used for evaluation of the course, hence you are expected to complete that within the week.
If you get stuck in any of the above questions, feel free to post them in the Telegram group. Additionally, you can also search for the problems online.<br/>
## Assignment Submission 
Link for Assignment submission is [here](https://forms.gle/fM1kCM2LikYm5UP58)

Congratualtions! You have successfully completed Week 2 of the course! Keep up the enthusiasm!

Again, if you are having any difficulties with the course, please reach out to one of the moderators and we will surely help you out.
See you in Week 3!
