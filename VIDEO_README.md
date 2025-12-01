# Video Upload Instructions

## Adding Videos to the Music Page

1. **Place your video files** in the `/Users/jackson/Desktop/PersonalSite/videos/` directory
   - Use `.mp4` format for best browser compatibility
   - iPhone videos can be used directly

2. **Update music.html** to reference your video files:
   - Open `music.html`
   - Find the `<video>` element
   - Change `src="videos/sample.mp4"` to match your video filename
   - Example: `src="videos/my-performance.mp4"`

3. **Adding multiple videos**:
   - Duplicate the video container structure:
   ```html
   <div class="video-container">
       <video controls>
           <source src="videos/video1.mp4" type="video/mp4">
           Your browser does not support the video tag.
       </video>
   </div>
   <div class="video-container">
       <video controls>
           <source src="videos/video2.mp4" type="video/mp4">
           Your browser does not support the video tag.
       </video>
   </div>
   ```

## For Web Hosting

When uploading your site to a web server:
- Upload the entire `videos/` folder along with your HTML/CSS files
- Keep the same directory structure
- Video file paths will work the same way

## Video Format Notes

- Best format: `.mp4` (H.264 codec)
- iPhone videos work directly
- For large files, consider compressing videos to reduce load times
