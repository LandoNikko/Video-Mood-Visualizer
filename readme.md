Video Mood Visualizer
The Video Mood Visualizer is a web app that locally transforms a video into a single image that reflects its overall tone or "mood" by sampling and blending frame colors, featuring different output styles and formats.

Getting Started
1. Any modern computer and browser will work. Processing speed depends on how good your hardware is.
2. Simply open the index.html and have fun!

How to use:
1. Open the index.html
2. Upload a video file
3. Optional: Crop off the start and/or end segments
4. Select your desired output format
5. Press "Create Mood" -button
6. Wait
7. Once complete, click on the image to open it in a new tab for a full view or download

Features

Video Upload
- Drag-and-drop or upload a video file
- .mp4, .webm, .mov, .avi, .mkv... (support depends on your browser)

Crop Adjustment
Black bars are detected and removed automatically by checking several points [0.3, 0.5, 0.7] throughout the video's length [1.0].
Optional crop setting to define custom start and end points, allowing to exclude unwanted segment, such as intro sequences or outro credits from the final output.

Output visualization: Color
Divides the video timeline into vertical slices; for each slice, the average frame color is calculated and rendered as a vertical color stripe.

Output visualization: Stretch
Extracts a 1-pixel-wide slice from the center of each video frame with each column processed sequentially and scaled to fill the canvas. The scaling has no smoothing filtering enabled, which yields a crisp result.

Output visualization: Gradient
Same as Stretch, but leverages the browser’s native bilinear (or similar) filtering to soften the transitions between sampled colors, yielding a smooth result.

Output visualization: Pixel
Same as Color, but organizes the average frame colors into a grid of cells, emulating a pixelated effect.

Output Customization
Presets for Desktop, Phone, Square aspect ratios at high resolutions, and allowing custom values for desired output.
Optional Film Grain effect can be applied to add texture to the end result.

Output
The final “Mood” image is rendered on a canvas. Clicking the output image opens it in a new tab, allowing users to view the full resolution image and save it if desired.
Below the generated image is a timer that shows time left in seconds and percentage complete.

Everything works locally on your machine.

Processing videos:
- Calculations like averaging pixel values (using getImageData) are done in JavaScript on the CPU.
Video Decoding:
- The browser uses dedicated video decoding hardware (like NVIDIA’s NVDEC or Intel Quick Sync) on your GPU to decode compressed video streams. This is why you see a spike in “Video Decode” usage.
Canvas Rendering:
- Once the video is decoded, drawing and scaling operations on the canvas are accelerated by the GPU.

Roadmap
- Explore more creative effects and customization options.
- Enhance processing efficiency for larger video files.
- Add ARIA attributes to improve accessibility.

Contributing
Contributions are welcome! Please fork the repository and open pull requests for any improvements or bug fixes. For major changes, consider opening an issue first to discuss your ideas.

License
This project is licensed under the MIT License. See the LICENSE file for details.

Feel free to open issues for any questions, suggestions or improvements!