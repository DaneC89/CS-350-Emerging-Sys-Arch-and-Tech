# CS-350-Emerging-Sys-Arch-and-Tech

•	Summarize the project and what problem it was solving.

For this final project we were tasked with creating a prototype thermostat that would use the TMP006 temperature sensor 
to read the room temperature (via I2C), an LED to indicate the output to the thermostat where LED on = heat on (via GPIO), 
two buttons to increase and decrease the set temperature (via GPIO interrupt), and the UART to simulate the data being sent 
to the server.

•	What did you do particularly well?

I thought I was able to use the GPIO interrupts very well. The button programming was implemented well and functioned properly. 
I felt the most comfortable coding his portion of the project. 

•	Where could you improve?

As with anything more practice would go a long way. I have a general understanding of how the system works and 
what each function should do. However, more time is needed to get a firm grasp on how to use the board with many different 
combinations. I think I could improve in every category overall. A good place to start would be using I2C since this was the 
first time using it for this project. 

•	What tools and/or resources are you adding to your support network?

Reading through CCS documentations to better understand how the program works has helped me out a lot throughout this project. 
I also added in TI documentations for this CC3220S board. Learning more about what this board can do and how to implement the 
other peripherals are ways I am trying to stay sharp with tinkering with this board.

•	What skills from this project will be particularly transferable to other projects and/or course work?

I think the most important thing that I have learned from this project is how to better problem solve issue that come up. 
Since this was my first time working with a physical system it was easy for other things to go wrong. For example, USB connections 
not working properly. This project showed me the importance of troubleshooting the hardware side as well as the software side.

•	How did you make this project maintainable, readable, and adaptable?

Using comments to make sure that the code is easily readable and understandable is an important step to ensuring the longevity of the code.
Additionally, separating my code into sections makes it easy for the code to be transferable to other projects I may work on in the future. 
Simple changes to naming conventions is really all that would be needed to implement sections of this code into other projects. It also makes 
debugging much easier as it is easier to find where a problem may be.
