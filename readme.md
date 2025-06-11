[![License][license-shield]][license-url]   [![GitHub][github-shield]][github-url]   [![Email][gmail-shield]][gmail-url]   ![Discord: ABC Status][discord-shield-static]

[license-shield]: https://img.shields.io/badge/License-GPL%20v2-5f43f2?style=for-the-badge&labelColor=0b0b0b&logo=gnu&logoColor=5f43f2
[license-url]: LICENSE

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

![VideoMoodVisualizer](https://github.com/user-attachments/assets/e3d11c25-2c3c-4c6f-ac8b-42c67077f0f3)

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

## ![Examples][examples-shield]

Source video: https://www.youtube.com/watch?v=_cMxraX_5RE

| Color | Stretch |
|:----:|:-----:|
| ![Mood_Color](https://github.com/user-attachments/assets/7e50ae9c-b2d5-4d76-8c78-ae512bae2be5) | ![Mood_Stretch](https://github.com/user-attachments/assets/74fcc6ba-0832-4c7f-abbb-1463a4436a82) | 
| Gradient | Pixel |
| ![Mood_Gradient](https://github.com/user-attachments/assets/ce3d5de7-e93a-4981-8708-69fb0d3983d0) | ![Mood_Pixel](https://github.com/user-attachments/assets/0aaf6685-24db-45ac-8c90-6c3c94dfef1f) |

[examples-shield]: https://img.shields.io/badge/Examples-5f43f2?style=for-the-badge&color=0b0b0b

## ![Privacy & Processing Shield][processing-shield]

- No cloud processing or installations.
- 100% client-side: built with HTML, CSS and JavaScript.
- Mood images are stored temporarily in your browser as blobs.

[processing-shield]: https://img.shields.io/badge/Privacy%20&%20Processing-5f43f2?style=for-the-badge&color=0b0b0b

## ![Use Cases Shield][use-cases-shield]

`creative projects`, `video analysis`, `artistic visualization`, `social media content`, `mood boards`, `color palette extraction`, `abstract art generation`

[use-cases-shield]: https://img.shields.io/badge/Use_Cases-5f43f2?style=for-the-badge&color=0b0b0b

## ![How it Works Shield][how-it-works-shield]

The tool sequentially samples frames from your video. For each sample, it calculates color data (average or specific pixel lines) and renders it onto a canvas according to the selected mode and format, building the final visualization locally.

[how-it-works-shield]: https://img.shields.io/badge/How_it_Works-5f43f2?style=for-the-badge&color=0b0b0b

## ![Feedback & Contributions Shield][feedback-shield]   [![License][license-shield]][license-url]

Contributions, bug reports and suggestions are welcome!

[![Email][gmail-shield]][gmail-url]   ![Discord: ABC Status][discord-shield-static]

[feedback-shield]: https://img.shields.io/badge/Feedback%20&%20Contribute-5f43f2?style=for-the-badge&color=0b0b0b&logo=github&logoColor=e0e6f7