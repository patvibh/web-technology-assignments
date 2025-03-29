## Exercise 6: Embedding YouTube Videos using `<iframe>`

### Question
Create a webpage that embeds a YouTube video using an HTML5 `<iframe>`.  
Ensure the video is **responsive**, so it adjusts to different screen sizes.

### Solution
The solution uses an HTML5 `<iframe>` to embed a YouTube video:  
* The `<iframe>` tag loads the video from YouTube using the `src` attribute.  
* `width="100%"` and `height="auto"` make the video responsive.  
* CSS is used to maintain the **16:9 aspect ratio**:
  * A `.video-container` div with `position: relative;` and `padding-bottom: 56.25%;`
  * The `<iframe>` is set to `position: absolute;` and `width: 100%; height: 100%;` to scale properly.

### Output
The webpage displays a **"Embedded YouTube Video"** section with a fully responsive video player.

![Screenshot of the webpage](Q6.png)

