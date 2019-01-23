Research task - RMRC
====================







			![alt text](https://imgur.com/lJrRDzS)
      img src="https://i.imgur.com/lJrRDzS.jpg" title="source: imgur.com" width="373" height="672" />
			</a>

		<p>
			In this section commands, for driving the motors and also for our camera. Arduino does all of the other work. For the keyboard, we used for loop, for reading our keys but the problem arises when, I will talk about the problems we encountered. We use the  Raspberry Pi for reading keyboard we want to look at our voltage level of the battery because the battery voltage shouldn't drop below 10.4 V on 12 V battery pack.
			The problem is that the Raspberry Pi starts to take track of voltage change when you press on a key when the key isn't pressed controller doesn't take the track.
			So we came up with an idea to merch the Raspberry Pi with Arduino so that Arduino keeps track of the voltage. If the user wants to see the voltage on serial monitor in python he will have to press key V, and Arduino will send the information to the microcomputer.
			Our programmer had a lot of problems in communication between the Arduino Nano and Raspberry Pi. We used serial communication and library Pyserial that is intended for this kind of communication between these two controllers. The communication is flawless but we get a weird boxy sign along a number that presents voltage level and we don’t know how to get rid of that sign. My guess would be that this presents NL(new line).
		</p> 
		<p>
			At the moment we are developing an electronic circuit that can connect all of our outputs and inputs to the microcomputer and start testing the performance of the rescue robot.
		</p>

		<a href="https://imgur.com/UaXFZfN"><img src="https://i.imgur.com/UaXFZfN.jpg" title="source: imgur.com" width="390" height="520" /> 
		</a>

		<a href="https://imgur.com/EQs24m9"><img src="https://i.imgur.com/EQs24m9.jpg" title="source: imgur.com" width="390" height="520" />
		</a>

	</body>
</html>
