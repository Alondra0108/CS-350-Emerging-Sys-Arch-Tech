# CS-350-Emerging-Sys-Arch-Tech
CS 350 Portfolio Reflection

Project Summary

For my final project, I developed a smart thermostat prototype using a Raspberry Pi. The thermostat reads room temperature from an AHT20 sensor over I2C, displays the current temperature and set point on an LCD, allows the user to change modes and temperature with push buttons, controls heating and cooling status using LEDs, and sends system data through UART to simulate communication with a server. This project allowed me to combine hardware and software into a complete embedded system while applying state machine design and interface programming.

What Did You Do Particularly Well?

I believe my strongest work was the software implementation and system integration. I successfully implemented all of the required thermostat functionality, including the state machine, interrupt-driven button controls, I2C communication with the AHT20 sensor, GPIO control for the LEDs, LCD updates, and UART communication. I also created a detailed state machine diagram that accurately documented the behavior of the thermostat, hardware connections, and system flow. The time I spent testing and debugging the project helped ensure that every component worked together correctly before the final demonstration.

Where Could You Improve?

One area where I could improve is the project documentation. While the thermostat itself worked correctly, I learned that technical reports should include more detailed architecture comparisons, stronger technical evidence, exact hardware specifications, and supporting references. In future projects, I will spend more time reviewing the rubric and documenting my design decisions with supporting sources so that the written documentation is just as strong as the implementation.

What Tools and/or Resources Are You Adding to Your Support Network?

Throughout this course I relied on the course resources, zyBooks, Raspberry Pi documentation, GitHub, and hardware documentation to better understand embedded systems. I also found that technical documentation, datasheets, and official hardware references are valuable resources when working with embedded devices. These are resources I will continue using in future projects because they provide reliable technical information and help solve problems more efficiently.

What Skills From This Project Will Be Particularly Transferable?

This project strengthened several skills that will transfer to future coursework and software engineering projects. I gained experience with Python programming, state machine design, debugging, hardware and software integration, GPIO programming, I2C communication, UART communication, and testing embedded systems. I also improved my troubleshooting skills by learning how to isolate problems, test individual components, and verify that the complete system worked as expected.

How Did You Make This Project Maintainable, Readable, and Adaptable?

I organized the code into logical sections, used descriptive variable names, and included comments to make the program easier to understand. I also separated the different hardware functions into clear sections so the code could be updated more easily in the future. By following consistent coding practices and thoroughly testing the thermostat, I created a project that is easier to maintain, read, and expand with additional features if needed.
