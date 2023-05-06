# Reading Notes


## Code 201 - Foundations of Software Development: Readings: Audio, Video, Images 

## Overview of reading notes:

These readings are important because they will help us learn the best ways to add videos and audio to our websites. Understanding the best practices to add audio and videos to our website is crucial for creating a website that users will enjoying visiting. It'll also make sure that our media is accessible to all users and works well on different devices and browsers.

### Explain how the ability to use video and audio on the web has evolved since the early 2000s.

Since the early 200s, the ability to use video and audio on the web has evolved tremendously. The use of proprietary plug-in based technologies like **Flash** and **Silverlight** were both popular to embed video and audio. But due to accessibility limitations and security issues, these are not obsolete ways to embed video and audio. Today, we can use HTML elements like `<video>` and `<audio>` and Javascript API's to embed audio and videos.

### Describe the use of the **src** and controls attributes in the `<video>` element.

The **src** is used within the `<video>` element to specify the source (URL or file path) of the video that you want to display on your site. The **control** attributed, added to the `<video>` controls the video and audio playback.

### Why is it important to have fallback content inside the `<video>` element?

The paragraph content inside the `<video>` element is the **fallback content**. This is important as it allows you to provide a backup plan in case your browser cannot be used with the `<video>` element. You can provide a **fallback content** by providing a link to the video file, so you can have a "fallback" on the content in the case this happens.

### Write a very short story where `<audio>` and `<video>` are characters.

If I were to explain the `<audio>` and `<video>` as characters of a story, let's envision a place where two characters named Audio and Video have special powers. Video creates descriptive and vivid pictures that come to life and Audio has a wonderful singing voice. Together they work together to create magic and to bring happiness in their universe.

### How does Grid layout differ from Flex?

**Grid layout** are different from **flex** in that a **grid layout** is a two-dimensional layout system, consisting of rows and columns. Whereas **flex** is a one-dimensional layout system that arranges element in either row/column in a horizontal or vertically.

### Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.

**Grid Container:** is an element that is the direct parent of all other grid items.
**Grid item:** the *direct descendants* or children of the grid container.
**Grid Line:** it is the lines that structure the grid. It can run in either direction, vertical (or "column grid line") or horizontal (or "row grid lines").

### Besides making a site visually appealing across different screen sizes, why should developers make images responsive?


Besides making websites look visually appealing to those who visit websites, it is also important to make images responsive as it helps make the images respond well to vastly different screen sizes, resolutions, and so on. For example, depending your device, some devices might need larger images to account for the higher resolution screens.


### Define the following `<img>` attributes **srcset** and sizes. Write an example of how they are used.

The **srcset** is used to let the browser choose between a group of images and the sizes, while the **sizes** sets the media conditions. 

For example, in the case with **srcset**  and **sizes**: 
`<img
  srcset="cat.jpg 480w, cat-800w.jpg 800w"
  sizes="(max-width: 600px) 480px,
         800px"
  src="cat-800w.jpg"
  alt="picture of cat" />`

As you can see from the example above **Srcset**, you will input the file name. They add the image's intrinsic width in pixels. As for the **sizes** you will set the media conditions, by setting the width of the slot the image will take up the media condition.

### How is srcset more helpful for responsive images than CSS or JavaScript?


The **srcset** attribute is more helpful for responsive images when compared to CSS or JavaScript. This is because CSS and JavaScript are not really designed for fast and responsive image loading. While both CSS and Javascript can help reduce image load times through its' image processing capabilities, either are not well-suited for handling responsive images. This is where the **srcset** attribute proves to be more useful.

## Things I want to know more about:

* What are some other best practices for optimizing images and audio files load time for website?
* How to make sure images and audio work for all devices and browsers.