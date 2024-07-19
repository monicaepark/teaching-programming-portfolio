# Teaching Programming Portfolio

This repository was created to showcase the projects I've created to teach programming to beginners. All projects are inspired from the UCSD EDS 124BR (Teaching Computational Thinking for Everyone) course curriculum, which I took over the summer of 2024 with Dr. Amy Eguchi and Dr. Beth Simon.

## (Module 1: Course Orientation)

## Module 2-3: Computational Thinking and Sequencing
Exercise: [Show What You Know: Explain Your Program](https://drive.google.com/file/d/1tjNx8lQaYlel7A3gLto-HLlDvkDts2Yp/view?usp=sharing) | `Snap`

In this exercise, students will explain their own `Snap` code step-by-step through a video, highlighting 1) the purpose of their code, and 2) what happens when the code runs. This exercise helps educators to see if their student understands how their code works.

## Module 4-5: Repeats
Exercise: [Let's dance!](https://drive.google.com/file/d/16Ps4hDjKPVM__x40imGJtkPKZB6iAUx6/view?usp=sharing) | `Snap`

Here, students will use the concept of repeats to emulate a breakdancer's dance using [these](https://docs.google.com/presentation/d/1bqlijPZWJLNByw8xqjSNAwBiC_wigLFMJ59T49YgYMQ/edit#slide=id.p) step by step instructions. If students want to explore further, they can write their own program using the concept of repeats.


Exercise: [Animal Parade](https://drive.google.com/file/d/1bF6SyrSvgg9mY5MahdOElxH0GNinjiu2/view?usp=sharing) | `Scratch`

In this exercise, students will play with animal spites on `Scratch` using [this](https://scratch.mit.edu/projects/428258614/) starter code along to this [worksheet](https://docs.google.com/presentation/d/111ar9NiouOq5KzZDPYm6z3_6yi_A3aPdou49fr_sABI/edit#slide=id.g40f3bba36c_0_157). Students will create repeat blocks for the kangaroo, grasshopperm and bee sprites to practice using repeat blocks to automate processes in their code.

## (Module 6: Equity & Pedagogy)

## Module 7-8: Nested Repeats
Exercise: [Mouse's Octagon](https://drive.google.com/file/d/1fj6Bwaphx_2KgJzQifOrBtZLs9oRNzdk/view?usp=sharing) | `Snap`

Now, we'll explore "nested" repeats ([tutorial](https://docs.google.com/presentation/d/13bEzhRNj80CD0LC7Wvi87OAp5uDGmugU0FjsnCYC4Pc/edit#slide=id.p)), where we place a repeat block inside another repeat block (aka nested loops). In effect, we are repeating a set of instructions that already contains at least one repeating set of instructions.

## Module 8-9: Events
Exercise: [Catch the bananas!](https://drive.google.com/file/d/1bRQwIL9-sRhcreVtnHnoPkT4M0of2Dfu/view?usp=sharing) | `Snap`

The next concept is events. We want our program ([tutorial](https://docs.google.com/presentation/d/1tbNxOKTPL_YlmywncLeoagH0eIMmeTNu5tCHpnrTeJI/edit)) to interact with real life "events" that will signal the next sequence of events, such as moving left when the left key is pressed, or waving when another character says hello. We will create these events using the "broadcast..." (send a signal) and "when I receive..." (receive a signal) blocks in snap.

## Module 9-10: Variables
Exercise: [Shapes and Variables](https://drive.google.com/file/d/1x36uv0JgWbk99UcTC91mgMAef_qpvMAi/view?usp=sharing) | `Snap`

In this exercise ([tutorial](https://docs.google.com/presentation/d/1YrmOVNtmuV5ceOQ1c5YZOKTBxygId1ybK_hmSB53FKc/edit#slide=id.g38c37d85b4_1_58)), we will draw 3 different polygons (triangle, square, pentagon) with equal side lengths, but a different numbers of sides. Both of these parameters (side length and number of sides) will be stored as variables that are used throughout the program. For example, to calculate the angle that the sprite must turn to get to the next line, we will always take 360º and divide it by the number of sides (e.g. a triangle has 3 sides, so the sprite turns 360º/3=**120º** degrees before each new line) rather than "hard-coding" (e.g. setting angle = 120, rather than angle = 360/num_sides) the number of degrees.

## (Module 11: (Equity & Pedagogy))

## Module 12-13: Conditional Loops
Exercise: [Catch the soccer ball!](https://drive.google.com/file/d/12agc8QT0PNAKx3C3W0nf-9E2PgTMkJDb/view?usp=sharing) | `Snap`

Students will now further explore the idea of repeats in the context of fixed vs conditional repeats ([tutorial](https://docs.google.com/presentation/d/1KOzzsWnF4degMaABS0sJ5aq5c0vpf_RM4Hwig2RNuzA/edit#slide=id.p)). We will be writing a program using a "repeat until" block in Snap, which runs like a while loop with a boolean condition. When our true/false condition (touching mouse pointer?) is false, the loop continues to run, but the moment it evaluates to true, we will exit the loop and the ball stops gliding across the screen.


## Module 14-15: If Statements
Exercise: [Blue ball on target](https://drive.google.com/file/d/1TBErTGV2AGA3EDaSgsMhBWOxzhBTwUZE/view?usp=sharing) | `Snap`

In this exercise ([tutorial](https://docs.google.com/presentation/d/1EIT2hgYVM8Yd0YlwYF4scEXfn05p4JR2Y6qeqy2N2EE/edit#slide=id.g3cb4cf9de0_3_32)), a user "catches" a blue ball floating around the screen by clicking on the ball, which will reward a different amount of points depending on the *condition* of what color the ball is touching on a target. The program also uses if/else statements to evaluate the user's final score and to say the appropriate response (better luck next time vs good game!).
