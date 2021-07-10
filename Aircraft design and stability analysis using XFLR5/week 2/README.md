## Week 2
#### The final goal at the end of the week would be that you would learn:
* To design a fixed-wing drone using the mission parameters.<br/>
* Learn how to analyse a 3D plane design in XFLR5.


So let’s start with what exactly a mission will typically look like, a mission typically gives you parameters that your UAV should satisfy. It would include Range, Endurance, payload, sometimes even things like takeoff distance.<br/>
* Now one thing to note is you will never have a single UAV satisfying all the mission parameters, instead, all the parameters of the UAV will lie in a certain range and of course will heavily depend on one another.

Now before we go into how to determine these parameters let’s look at the governing [equations for fixed-wing flight](https://www.grc.nasa.gov/www/k-12/airplane/cruise.html).<br/>
Just to get a flavour for it this is how range and endurance of a fuel powered plane is calculated have a look at this [document](https://nptel.ac.in/content/storage2/courses/101104007/Module2/Lec9.pdf).If it is not very clear have a look at the following [video](https://youtu.be/2NR2eFxaK74).
With this info, I want you all to get a brief idea on thrust required and power required, I am giving you a slightly long video but this will give you a recap of everything we did till now and the Power required part which will come in very handy in the analysis ahead:[Thrust Required, Power Required: Cruise](https://youtu.be/YDChv27slEE)


#### Now how to go from there to range and endurance?
Remember we said something about it in mission parameters.
Well you just equate power required to battery power: TV = power-required.

Just a note this is only for steady level flight, a lot more configurations are possible. If you are interested you could go through the following: 
 * **[Ascent](https://www.grc.nasa.gov/www/k-12/airplane/climb.html)**
 * **[Gliding flight](https://www.grc.nasa.gov/www/k-12/airplane/glidang.html)**.<br/>

Now after this we will cover the weight iteration technique. It will be covered in the live session.

## XFLR5
* **[Design a plane](https://youtu.be/vhykE-mVBO4)**
* **[Plane analysis](https://youtu.be/bJddlSRSZGY)**
* **[Reference dimensions](https://youtu.be/VH3M1NQYZPA)**
* **[Design a flapped wing](https://youtu.be/uUQhFh0d4uM)**

And here is the Webinar 1 slides and recording link for your reference.
* **[Slides](https://docs.google.com/presentation/d/1yDpFzJeMpa7GxheA2u-Rbdd2NnsJJzdS3lKUppqSnF0/edit?usp=sharing)**
* **[Recording](https://iitbacin.sharepoint.com/sites/LSAircraftdesignandStabilityanalysisusingXFLR5/Shared%20Documents/General/Recordings/webinar%20of%20week1-20210705_170521-Meeting%20Recording.mp4?web=1)**
