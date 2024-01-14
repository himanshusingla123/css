In CSS, the `object-fit` property is used to specify how an `<img>` or `<video>` element should behave when its content is resized within its containing box. It determines how the content of the element should be scaled and positioned to fit the dimensions of the box.

The `object-fit` property can take the following values:

1. `fill`: This value makes the content stretch to completely fill the box, potentially distorting the aspect ratio of the content.

```css
img {
  object-fit: fill;
}
```

2. `contain`: The content is scaled to maintain its aspect ratio while fitting within the box. It may leave empty spaces within the box if the aspect ratios are different.

```css
img {
  object-fit: contain;
}
```

3. `cover`: The content is scaled to cover the entire box while maintaining its aspect ratio. This may result in some of the content being cropped if the aspect ratios are different.

```css
img {
  object-fit: cover;
}
```

4. `none` or `fill-available`: This value makes the content maintain its original size, potentially overflowing the box.

```css
img {
  object-fit: none;
}
```

5. `scale-down`: The content is scaled down to fit within the box, but it won't be upscaled if it's smaller than the box.

```css
img {
  object-fit: scale-down;
}
```

The `object-fit` property is particularly useful when working with responsive design, allowing you to control how the content within an element responds to changes in size while maintaining a desired presentation.
