Certainly! Here are some common scroll effects you can achieve using CSS:

1. **Fixed Navigation Bar:**
   ```css
   nav {
     position: fixed;
     top: 0;
     width: 100%;
     background-color: #333;
     padding: 10px;
   }
   ```

2. **Parallax Background:**
   ```css
   .parallax {
     background-image: url('background.jpg');
     background-attachment: fixed;
     background-position: center;
     background-repeat: no-repeat;
     background-size: cover;
     height: 100vh;
   }
   ```

3. **Fade-in Elements on Scroll:**
   ```css
   .fade-in {
     opacity: 0;
     transition: opacity 0.8s ease-in-out;
   }

   .fade-in.is-visible {
     opacity: 1;
   }
   ```

4. **Sticky Element on Scroll:**
   ```css
   .sticky {
     position: sticky;
     top: 0;
     background-color: #f1f1f1;
     padding: 10px;
   }
   ```

5. **Scale Element on Scroll:**
   ```css
   .scale-on-scroll {
     transform: scale(1);
     transition: transform 0.5s ease-in-out;
   }

   .scale-on-scroll.is-scrolling {
     transform: scale(1.2);
   }
   ```

These effects can be applied by adding and removing classes through JavaScript based on scroll events or by utilizing the `:hover` or `:active` pseudo-classes for simpler effects.
