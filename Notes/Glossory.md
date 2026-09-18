#### Register

- A tiny & fast storage room inside the CPU. The data stored is instant to use with limited size.

- For example, if the CPU wants to add 2 numbers together, it will first load them into **registers**, do the math, then load the result to another register. It's like a cutting board that holds on or two ingredients for a chef to work on, while the RAM is the fridge that stores all sorts of ingredients but it takes way more time to access any of them.

#### Unsigned Numbers

- An **unsigned** int can only be positive, while **signed** can be both. 

- For example, if an int is 1 byte big `0000 0000`, then an unsigned int is between 0 (`0000 0000`) to 255 (`1111 1111`), and an signed int between -128 (`1111 1111`) to 127 (`0000 0000`). Recall that for **signed** binaries, the left most bit is the *sign bit*, where 0 means positive and 0 means negative.  
