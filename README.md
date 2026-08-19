Pomodoro Timer

A simple, browser-based Pomodoro timer built with vanilla HTML, CSS, and JavaScript to help stay focused during study/work sessions.

Features:
25-minute countdown timer using the Pomodoro Technique
Start, Pause/Resume, and Reset controls
Live display that updates every second
Alert notification when time is up
Hover effects on buttons and timer for a bit of visual feedback

How it works
The countdown is driven by setInterval, ticking down timeLeft (in seconds) once per second and updating the display.
isPaused and timerInterval track state so Start/Pause/Reset don't interfere with each other or start multiple timers at once.
When the timer hits zero, the interval clears and the user gets an alert to take a break.
Tech stack
HTML5
JavaScript (DOM manipulation, setInterval, event listeners)
