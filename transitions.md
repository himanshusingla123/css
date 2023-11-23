In CSS, transitions are used to create smooth animations when a property changes its value. Transitions provide a way to control the duration, timing function, and property being animated. Here are the main aspects of CSS transitions:

1. **Property Transition:**
   - Specifies the CSS property that will be animated.
   - Example:
     ```css
     transition: width 0.5s ease-in-out;
     ```

2. **Duration:**
   - Defines the time it takes for the transition to complete.
   - Can be specified in seconds (s) or milliseconds (ms).
   - Example:
     ```css
     transition: width 1s; /* 1 second duration */
     ```

3. **Timing Function:**
   - Specifies the speed curve of the transition.
   - Common values include `ease` (default), `linear`, `ease-in`, `ease-out`, `ease-in-out`, and custom cubic-bezier functions.
   - Example:
     ```css
     transition: width 0.5s cubic-bezier(0.42, 0, 0.58, 1);
     ```

4. **Delay:**
   - Specifies a delay before the transition starts.
   - Can be specified in seconds (s) or milliseconds (ms).
   - Example:
     ```css
     transition: width 0.5s ease-in-out 0.3s; /* 0.3s delay */
     ```

5. **Shorthand:**
   - Combines the property, duration, timing function, and delay in a single line for brevity.
   - Example:
     ```css
     transition: width 0.5s ease-in-out 0.3s;
     ```

6. **Multiple Transitions:**
   - You can apply multiple transitions to different properties, separated by commas.
   - Example:
     ```css
     transition: width 0.5s ease-in-out, color 0.3s linear;
     ```

Transitions make it easy to add subtle animations to your web pages without the need for complex keyframe animations. They enhance the user experience by providing visual feedback for state changes.
