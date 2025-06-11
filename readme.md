[![Try it][demo-shield]][demo-url]   [![GitHub][github-shield]][github-url]   [![Email][gmail-shield]][gmail-url]   ![Discord: ABC Status][discord-shield-static]

[demo-shield]: https://img.shields.io/badge/Try_it-0b0b0b?style=for-the-badge&color=0b0b0b
[demo-url]: URL

[github-shield]: https://img.shields.io/badge/GitHub-5f43f2?style=for-the-badge&color=0b0b0b&logo=github&logoColor=5f43f2
[github-url]: URL

[gmail-shield]: https://img.shields.io/badge/Email-5f43f2?style=for-the-badge&color=0b0b0b&logo=gmail&logoColor=5f43f2
[gmail-url]: URL

[discord-shield-static]: https://img.shields.io/badge/Discord-landomrandom-5f43f2?style=for-the-badge&labelColor=0b0b0b&messageColor=e0e6f7&logo=discord&logoColor=5f43f2

# Video Mood Visualizer

The Video Mood Visualizer is a web app that locally transforms a video into a single image that reflects its overall tone or "mood" by sampling and blending frame colors, featuring different output styles and formats.

Try it here: https://landonikko.github.io/Video-Mood-Visualizer

## ![Features Shield][features-shield]

- **Automatic Black Bar Removal:** Intelligently crops out letterboxing/pillarboxing.
- **Optional Trimming:** Define start/end points to process specific video segments.
- **Output Modes:**
    - `Color`: Vertical stripes of average frame colors.
    - `Stretch`: Crisp, 1-pixel wide stretched frame slices.
    - `Gradient`: Smoothly blended stretched frame slices.
    - `Pixel`: Grid of average frame colors for a pixelated look.
- **Format Customization:** Presets (Desktop, Phone, Square) & custom dimensions.
- **Film Grain Effect:** Optional toggle for added texture.
- **Instant Preview & Download:** Click the generated image to open/save.

[features-shield]: https://img.shields.io/badge/Features-5f43f2?style=for-the-badge&color=0b0b0b

## ![Privacy & Processing Shield][processing-shield]

- No cloud processing or installations.
- 100% client-side: built with HTML, CSS, and JavaScript.
- Mood images are stored temporarily in your browser as blobs.

[processing-shield]: https://img.shields.io/badge/Privacy%20&%20Processing-5f43f2?style=for-the-badge&color=0b0b0b

## ![Use Cases Shield][use-cases-shield]

`creative projects`, `video analysis`, `artistic visualization`, `social media content`, `mood boards`, `color palette extraction`, `abstract art generation`

[use-cases-shield]: https://img.shields.io/badge/Use_Cases-5f43f2?style=for-the-badge&color=0b0b0b

## ![How it Works Shield][how-it-works-shield]

The tool sequentially samples frames from your video. For each sample, it calculates color data (average or specific pixel lines) and renders it onto a canvas according to the selected mode and format, building the final visualization locally.

[how-it-works-shield]: https://img.shields.io/badge/How_it_Works-5f43f2?style=for-the-badge&color=0b0b0b

<!-- Optional: Add a Demo video like in the example if you have one -->
<!--
## ![Demo Shield][demo-section-shield]

<video src="URL_TO_YOUR_DEMO_VIDEO" controls width="600"></video>

[demo-section-shield]: https://img.shields.io/badge/Demo-00c6ff?style=for-the-badge&color=121727
-->

## ![Feedback & Contributions Shield][feedback-shield]

Contributions, bug reports and suggestions are welcome!

[![Email][gmail-shield]][gmail-url]   ![Discord: ABC Status][discord-shield-static] <!-- Update or remove Discord -->

[feedback-shield]: https://img.shields.io/badge/Feedback%20&%20Contribute-242c44?style=for-the-badge&color=121727&logo=github&logoColor=5f43f2

MIT License
