---
layout: post
title: "Poles Apart Tutorial"
categories:
 - event
---

#### Poles Apart

The engineers are trying to design a vehicle that is capable of adapting itself to the rough terrain it is sent into. You are asked to design the prototype of such a bot that is capable of changing the distance between its wheels so as to cover a ground that cannot be done otherwise. There are multiple valleys that converge, diverge or are in an arc form and are to be crossed. 

Your challenge is to design a bot robust enough to adapt itself according to the valleys it faces. There are also certain parts of the path that you need to complete before you can cover the further ground. Use a mechanical gripper to complete this problem statement. 

**How this Tutorial works?**

This is a guide for an enthusiast like yourself to explore your own imagination and incorporate them in a robot that you can build with your team for this Robotix’18 edition! The tutorial lists out all the skills that this event can possibly require for your bot to complete the problem statement and tells you exactly how you can implement each of them. And finally, find our ‘Tips’ to put together all your mechanisms and build a winning that’s going to win you a ton of fun!

#### Problem Statement:

To build a manually controlled robot that is capable of crossing converging and diverging paths by changing its interaxial distance. It also needs to pick and place blocks and logs to complete its path.

To tackle this your robot needs a mechanism having a:

1. Adaptability by changing its interaxial distance

2. Land Traversal capability, slope climbing

3. Robotic arm, picking and placing.

4. A storage mechanism (optional)

#### MECHANISMS FOR CHANGING THE INTERAXIAL DISTANCE:

##### Design 1:

Use of Rack and pinion

There will be many instances during the run when you will come across a path where you have to change your interaxial distance steadily to reach the other side. The best way that we have come across so far is the use of rack and pinion coupled to a High Torque motor to spread the wheels against the friction of the ground. 

It would definitely help your case if you make a bot that is divided into four parts coupled together using two sets of rack and pinion. You need to ensure a symmetry holding mechanism for that design otherwise the trivial navigation of this bot will suffer and make it even harder for you to overcome the obstacles in the course.

**Material Required:**

* A four-part chassis, as shown in the figure, embedded with a four wheel differential drive (later explained in detail)

* 8 motors (Four for traversal, two for rack and pinions and two for the grippers)

* Two pairs of rack and pinion,

* Two motors to be coupled with the rack and pinion over the bot.

* 6 DPDT switches (Two for general traversal, two for each of the rack and pinion and two for controlling the two axis of the gripper)

* Ribbon wires of 2-3 meters of length

* 4 wheels

**How to make your bot?**

Try to think of an innovative design for your chassis, as we have tried to part it in four parts so as to increase our flexibility, but the demerit of such a design is the increased complexity in its control. Fixing and use of grippers and maneuvering of the bot using a differential drive has later been explained in this tutorial. With a control good enough over your bot, you are all set.

![](/img/tutorial/event/poles-apart/image_0.png){:.img-responsive}

![](/img/tutorial/event/poles-apart/image_1.png){:.img-responsive}

![](/img/tutorial/event/poles-apart/image_2.png){:.img-responsive}

##### Design 2:

The other way to look at the design is to *eliminate the rack and pinions*. Instead, have one motor each for changing the rotational axis of every wheel and then expand as much the situation demands. 

The steps of construction and the main frame of your bot, that is, the chassis will remain the same as described or photographed above. The only change will be that of rack and pinion. In this design, you do not need any.

**How will the design work?**

The clamp of the wheel (which is generally connected to the chassis) will now be mounted to a motor, which in turn will be fixed on the chassis. The wheels can rotate along with the motors (for general movement of the bot) perpendicular to their trivial direction, then expand as much as it is needed and then continue to move forward by re-aligning the wheels as before.

The demerit of this design is the increased complication in controls. Since two members per team are allowed to control the bot, with practice this could be easily overcome.

The other problem you might face during the making of this design is the entangling of wires while rotation of the wheel axis. But if the bot is constructed well enough with things arranged in a proper manner, this design might be a very effective one.

But in the end, it all boils down to the key point in winning any manual robotics event. That is how well you have the control of your bot. And a lot of practice on a well assembled bot will definitely take you a long way.

#### MECHANISMS FOR TRAVERSALS

Despite all the complications that you might think your bot has after loading it with all the mechanisms we discussed, the best way to traverse your bot remain unaltered. The classic differential drive

##### 1. Differential Drive Mechanism

**Design:**

When two motors are connected to wheels in one line, opposite to each other (just like a pair of wheels connected to a single shaft) the speed with which each motor rotates determines the direction of motion. When both the wheels rotate at the same speed the difference between the motors is zero. This makes the robot move forward in a straight line.The robot can move in reverse direction if the direction of rotation of both the motors are reversed. This will again be in a straight line if the speed difference is zero.

![](/img/tutorial/event/poles-apart/image_3.png){:.img-responsive}

Now changing the speed of any one motor will result in movement in a direction away from the straight line. For example, reducing the speed of the right motor will result in a speed difference and hence change in direction.The resultant force is such that the robot turns right. This direction change can be controlled to required angle by further reducing the speed of the motor.Slower is the right motor, sharper is the turn to right. This is exactly the same for Left turn.

As a conclusion, Slower right motor, sharper right turn. Slower left motor Sharper left turn. Below are some scenarios which explains working of differential drive mechanism.M1 and M2 are motors which drive wheels on left and right respectively.

**Material required:**

* Basic rectangular chassis

* Four DC Motors / Two DC Motors

* Wires

* Four Wheels / Two Wheels and One Caster Wheel

**Steps of construction:**

1. Make the Wheel Template.

2. Cut-out the wheels, and drill a hole in the middle.

3. Join the wheels to the chassis with connecting axles.

4. Join the motors to the wheels.

5. Make connections of your motor to the circuit of Differential drive.

6. Your robot is ready to work.

**Working:**

* When both the wheels turn forward with same RPM the robot goes forward

* When both the wheels turn in reverse direction with same RPM the robot goes backward.

* When left wheel turns forward and right wheel turns backward the robot takes zero radius right turn. Vice versa happens in the case of left turn.

* When left wheel turns forward but right wheel turns forward with lesser RPM than left wheel then the robot takes right turn with particular radius of curvature. Vice versa happens in the case of left turn.

**Controls:**

Three way switch

![](/img/tutorial/event/poles-apart/image_4.jpg){:.img-responsive}

![](/img/tutorial/event/poles-apart/image_5.jpg){:.img-responsive}

**Motor Connections:**

![](/img/tutorial/event/poles-apart/image_6.jpg){:.img-responsive}

![](/img/tutorial/event/poles-apart/image_7.jpg){:.img-responsive}

The motors are fixed to the chassis and the tyres are fitted to the DC Geared Motors.

#### ROBOTIC ARM MECHANISM

##### 1.Mechanical Arm

**Design:**

In this mechanism we have used a manually controlled robotic arm with 2 degrees of freedom.

**Material required :**

* 2 DC Motors.

* Rack and pinion mechanism(for the rails).

* 2 elbow joints in perpendicular planes of the arm.

**Steps of construction:**

1. Connect one motor to the base of the whole arm mechanism. This will help in turning the arm left and right.

2. Connect the other motor to the arm such that its motion causes the arm to move up and down.

**Steps of construction: (Gripping mechanism with motors)**

1. As shown in figure, keep one side of the part stationary.

2. Attach motor to the end of another part.

3. Make wire connections of the motor such that when the motor is rotated in one direction one part moves towards other part (stationary) and vice versa.

**Working:**

A simple mechanical arm consisting of two motors. The first motor controls the upward and downward movement of the arm. While the second one helps helps in rotating the arm sideways.The arm provides 2 degrees of freedom to move in horizontal as well as vertical direction, so that the arm can reach all the ends of the arena.

![](/img/tutorial/event/poles-apart/image_8.jpg){:.img-responsive}

