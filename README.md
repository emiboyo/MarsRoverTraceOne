Technical test - Mars Rover

Context
We are sending a Rover to Mars, and we need to be able to move it through a series of instructions
sent from the Earth. In order to follow it, we need an interface to see the Rover’s journey in real
time.
You are the chosen one to lead this fantastic project. But please be careful, NASA pays particular
attention to the best practices and tested code!
For the moment, our Rover is on a test mission. NASA has placed the Rover on a grid as playground
to make sure all is well before we ship it off to Mars.
What needs to be set as constants in the app entry:
- The grid’s size
- The Rover’s default direction
- The Rover’s default position
- The list of commands

The grid
The grid is a 10x10 square.

The rover
Our Mars Rover’s default direction is “N” (as North). Its direction is one of four values: “N”, “S”, “E”
or “W”.
Example: If the Rover is facing North and turns left, it is now facing West.
To move the Rover around, we have to keep track of its position. Positions are represented as a pair
of coordinates: ”x” and ”y”. Their default values are both 0.
The Rover can't move and turn at the same time. This means that if the Rover wants to move to the
left, its first move must be a turn. Its next move will then be a step forward.

The Commands
The commands are the first letter of either (f)orward, (r)ight, or (l)eft.
To test it, you can use the string ‘rfflfflfrff’

Your mission

NASA waits for you to deliver a React application with the testing grid and the Rover moving in real-
time. You can choose the libraries you need and define the UX/UI you want, in you we trust!

You can send us a zip project or a Github link by email.
Good luck!