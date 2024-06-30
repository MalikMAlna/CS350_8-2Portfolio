# 8-2 Journal: Portfolio Item

### Summarize the project and what problem it was solving.

In these projects, I demonstrated the basic functionality of setting up and handling GPIO interrupts in a bare-metal environment without an operating system (NoRTOS). 
Specifically, in the first project, I created a simple state machine to cause lights on a microcontroller to flash the Morse code for SOS and with a button press switch to flash the Morse code for OK.
In the second project, I was working on a prototype of the functionality that could go into a smart thermostat that would later be built to include functionality for WiFi access.
Ultimately, the primary problem these projects that I was working to solve was providing clear, functional examples of interrupt handling on specific Texas Instruments hardware, 
which is critical for developers working on embedded systems where interrupt management is a common task.

### What did you do particularly well?

In particular, I did a good job simplifying the state machine for the first project and keeping the smart thermostat functionality focused on the minimum viable functionality necessary for the prototype to work. 
I also kept the initial boilerplate for both projects well-structured with a consistent layout.

### Where could you improve?

One area for improvement could be the documentation I wrote within the code itself. 
While this README file provides an overview of both projects, more detailed comments within the source code (specifically in gpiointerrupt.c for both projects) could help to clarify the flow and specific implementation details of both projects. 
Including unit tests or examples of how to test the interrupt functionality could be another improvement for both projects.

### What tools and/or resources are you adding to your support network?

Tools such as Code Composer Studio (CCS) for IDE support, and resources such as Texas Instruments's documentation and SDK for detailed hardware and API references are helpful tools and resources I could keep handy for the future.

### What skills from this project will be particularly transferable to other projects and/or course work?

The skills I demonstrated in these projects, such as setting up and handling interrupts, managing GPIO configurations, and working within a NoRTOS environment, are highly transferable for embedded systems work. 
These are fundamental skills for any embedded systems developer and can be applied to other projects involving microcontroller programming, real-time systems, and hardware interfacing.

### How did you make this project maintainable, readable, and adaptable?

I made these projects maintainable through their clear directory structure and use of standardized project files. 
I made them readable through straightforward, well-named/organization functions and variables. 
Furthermore, I made them adaptable by leveraging the modular nature of the boilerplate code, which allowed for easy modifications and extensions to support additional features or different hardware configurations, both by myself and for anyone in the future.
