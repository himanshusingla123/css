Flexbox, or the Flexible Box Layout, is a layout model in CSS that allows you to design complex layouts more efficiently and with less code. The properties associated with flexbox are applied to a container (parent element) to control the layout and positioning of its child elements. Here are some of the key properties of flexbox:

1. **`display` (flex | inline-flex):**
   - Defines a flex container. It can take two values: `flex` and `inline-flex`. The `flex` value creates a block-level flex container, while `inline-flex` creates an inline-level flex container.

   ```css
   .flex-container {
     display: flex;
   }
   ```

2. **`flex-direction` (row | row-reverse | column | column-reverse):**
   - Determines the direction in which the flex items are placed in the flex container. The values can be `row` (default), `row-reverse`, `column`, or `column-reverse`.

   ```css
   .flex-container {
     flex-direction: row;
   }
   ```

3. **`flex-wrap` (nowrap | wrap | wrap-reverse):**
   - Specifies whether the flex items should wrap onto multiple lines. Values include `nowrap` (default), `wrap`, and `wrap-reverse`.

   ```css
   .flex-container {
     flex-wrap: wrap;
   }
   ```

4. **`justify-content` (flex-start | flex-end | center | space-between | space-around | space-evenly):**
   - Aligns the flex items along the main axis of the flex container. It controls the distribution of space between and around the items.

   ```css
   .flex-container {
     justify-content: center;
   }
   ```

5. **`align-items` (flex-start | flex-end | center | baseline | stretch):**
   - Aligns the flex items along the cross axis of the flex container. It defines how items are aligned in the container.

   ```css
   .flex-container {
     align-items: center;
   }
   ```

6. **`align-self` (auto | flex-start | flex-end | center | baseline | stretch):**
   - Allows the individual flex items to override the `align-items` property for themselves.

   ```css
   .flex-item {
     align-self: flex-end;
   }
   ```

7. **`flex` (flex-grow flex-shrink flex-basis):**
   - A shorthand property that combines `flex-grow`, `flex-shrink`, and `flex-basis` to specify the flexibility of a flex item.

   ```css
   .flex-item {
     flex: 1 0 auto;
   }
   ```

8. **`flex-grow`:**
   - Specifies how much a flex item should grow relative to the other flex items in the container.

   ```css
   .flex-item {
     flex-grow: 2;
   }
   ```

9. **`flex-shrink`:**
   - Specifies how much a flex item should shrink relative to the other flex items in the container.

   ```css
   .flex-item {
     flex-shrink: 1;
   }
   ```

10. **`flex-basis`:**
    - Specifies the initial size of a flex item before the remaining space is distributed. It can be set as a length, a percentage, or `auto`.

    ```css
    .flex-item {
      flex-basis: 20%;
    }
    ```

These flex properties provide a powerful and flexible way to create responsive and dynamic layouts in CSS. The combination of these properties allows you to control the arrangement and sizing of elements within a flex container.
