# Audio Video, Images
## Video and Audio Content
### Explain how the ability to use video and audio on the web has evolved since the early 2000s.
In the early 2000s we plugins like Flash and Silverlight were used. Now HTML native elements with JavaScript APIs are used.
### Describe the use of the src and controls attributes in the <video> element.
Similar to the \<img> element the source (\<src>) attribute contains the path to the embedded video. The controls attribute allows the user to at a minimum start/stop the video and control the volume.  
### Why is it important to have fallback content inside the <video> element?
Certain browsers might not be compatabile with the provided video format. Fallback content can redirect the user to a working link or at least inform them the video is not working.
### Write a very short story where <audio> and <video> are characters. 
Once upon a time there were two friends, \<audio> and \<video>. They both travelled the world together. They realized that when they were together more people were drawn to them. By themselves, they felt incomplete.
## A Complete Guide to Grid
### How does Grid layout differ from Flex?
Grid layout has a two-dimensonal flow as opposed to the one-dimensonal flow of of Flexbox.
### Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
The grid container is where the grid is applied. Grid items are the children of a grid container. Grid lines are the dividing lines that divide up the grid. There are vertical (column) grid lines and horizontol (row) grid lines. 
## Responsive Images
### Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
It also improves performance. 
### Define the following <img> attributes srcset and sizes. Write an example of how they are used.
Srcset "defines the set of images we will allow the browser to choose between, and what size each image is."
https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images
Sizes  defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true — these are the hints we talked about earlier.  

### How is srcset more helpful for responsive images than CSS or JavaScript?
It allows the browser to be more flexible and pick the best image that's best for the user base don their screen. 

