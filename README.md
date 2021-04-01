# WOW
Please clearly describe the United Nations' Sustainable Development goal(s) AND target(s) you are looking to solve with technology. What inspired you to select these specific goal(s) AND target(s)? *
=>We have selected the 10th SGD Goal:  Reduced Inequalities. 
In Korea, there is a 'Quiet Taxi' service on going. This is a uber-like taxi service business  run by deaf taxi drivers. The drivers are provided with special equipped taxi to serve the passengers. and passengers enjoy the tranquil transportation. 
However, there are very few cases that we come across the deaf drivers in daily life. Therefore, our team, WishforWish have decided to bring the recognition of deaf driver's daily drive into a challenge. A challenge to open up their driving environment flexibility.

How does your solution address the challenge you are looking to solve for? *
=>We have created an assisting navigating application for deaf drivers. Navigation tools are widely used from drivers mobile phone. 
Paying attention on the road requires senses, not only the eye sight but also hearing. We noticed that the deaf drivers would struggle sensing the surroundings in a vehicle. Sensing the speech nearby, noticing the siren alert in vicinity. Thus, a deaf driving assistant, On-Nuri can visualize the surroundings. It is our main goal to directly deliver the speech and alerting sirens to the drivers. 

On-Nuri(온누리) means the whole world in Korean. We aim to relinquish the daily inequalities in the whole world. 

What do you see as the future / next steps for your project? How will you expand your solution to reach a larger audience? *
=>We are hoping to extend our solution by applying IoT technologies.
 This will enhance the accuracy of the surrounding detection using extra exterior sensors which can collect specific sound fragments including the blind spot of the vehicle. 
Moreover, we suggest On-Nuri could be utilized any parties that needs assistance while driving. For instance, senior drivers or other possible users response-delay could happen. 

Walk us through the steps you took to test your solution. Can you provide three specific feedback points you received from users that tested out your solution? *
=>1) Driver to non-driver communication issue: we once thought distinguishing the sound of siren would practically assist the deaf drivers. however, we received a feedback that there was a news about a deaf driver stigmatized as a police attacker during police investigation (alcohol breathing tests) for trying to remove the mask of the officer to communicate thoroughly. 
2) Various sound detection needed: As we developed a model that classifies the different sirens, there was a feedback on distinguishing the car horn sound. In urgent situation on the road, irregular sounds of the horn should be caught and responded immediately.  Our users depicted the new about the lots of rejections on car renting industry to the drivers for not able to hear the car horns. 
3) UI Interface--fading blinks of color: At first we developed the alert form as a pop-up window above the navigation bar. Then, we were illustrated the fact that even non-disordered drivers could not fully concentrate on navigation screen. There should be more effective display.

Please share the outcome of your testing strategy. What are three specific things you implemented and improved for your solution based on the feedback from users? *
=>1) Use of STTs: Accordingly, we have added the STT function to lessen the burdensome in Covid-19 interaction between drivers and others.
2) Adding the sound detection field--car horn: We added a new parameter to the machine training model that distinguishes the car horn and alongside the siren classification.
So that the deaf drivers could recognize more of the vehicle surroundings.
3) UI Interface--fading blinks of color: We have changed the pop-up UI into fading in and out of the entire display in different colors in types of sirens. Plus, blinking the colored display for several times gives an instant recognition of the surrounding environment.

Highlight one challenge you faced while building your code, including detail on how you addressed the issue and the technical decisions and implementations you had to make. *
=>The challenge were mainly connecting one function to another. Having developed each function of GPS navigation, siren detection, and STT worked smoothly in independence. However, organically linking a function to another needed further library understanding of android studio, java , and tensorflow. 
