
A simple React timer application built using useState and useRef.

Features
Start the clock
Stop the clock
Display elapsed seconds
Prevent multiple intervals from running
Hooks Used
useState: Stores and updates the seconds displayed on the screen.
useRef: Stores the interval ID without causing re-renders.
How It Works
Clicking Start Clock starts a timer that increments every second.
Clicking Stop Clock stops the timer using clearInterval().
