## Magnetic Button Effect
Magnetic Buttons using React, GSAP, Framer Motion. See the difference in terms of implementation for a magnetic effect between GSAP and Framer Motion.

### Initializing the project
Let's start the project by creating a Next.js application. 

We can do that by running ``` npx create-next-app@latest ``` client inside of a terminal.
- We will use Sass for the stylesheets, so we can run ``` npm i sass ```
- We will use Framer Motion for the animation, so we can run ``` npm i framer-motion ```
- We will also use GSAP for the animation, so we can run ``` npm i gsap ```

### Framer Motion Implementation
For Framer Motion, I use the ``` setState() ``` hook with the motion tag from Framer Motion.

### GSAP Implementation
For the GSAP implementation, we use the quickTo method to move the cursor around. We also use the ``` React.cloneElement() ``` in order to return the children with a ref attached to it.
