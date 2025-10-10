# Quiz 8: Design Research

## Part 1: Imaging Technique Inspiration

I am inspired by the **stroboscopic effect**, where continuous motion is broken down into a series of distinct, frozen moments. This effect is often seen when a rapidly spinning object, like a fan blade, is illuminated by a flashing light, making it appear stationary or moving in slow, rhythmic pulses. I want to apply this **"stroboscopic patterning"** to the geometric forms in Shemza's work. Instead of animating the forms with a fluid motion, I will make them appear and disappear in a **rhythmic sequence**. This technique emphasizes the artwork's underlying **grid and repetitive nature**, transforming its static pattern into a dynamic, hypnotic dance of light and shadow that is both simple to code and visually striking.

To find inspiration for this effect, I will search for:
* `stroboscopic fan gif`
* `sequential light animation`
* `strobe light effect`

## Part 2: Coding Technique Exploration

I will use **conditional rendering driven by time and a modulo operator**. I will assign each geometric component (e.g., each circle) to a specific **time group**. In the `draw()` loop, I will use `frameCount % numberOfFrames` to create a looping counter. For example, if `numberOfFrames` is 10, the loop will count from 0 to 9 repeatedly. I will then use a simple `if` statement to check if a component's group number matches the current `frameCount` value. If it does, the component is drawn; otherwise, it's not. This basic logic allows me to create a synchronized, pulsing animation with a very small amount of code, resulting in a clean and mesmerizing stroboscopic effect.

To find code examples for this technique, I will search for
* `p5js modulo operator example`
* `javascript time based grouping`
* `p5.js conditional drawing`