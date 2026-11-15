# Student Appreciation Website

A static, five-page appreciation and memory website for Mr. David's students. It uses only HTML5 and CSS3; there are no scripts, frameworks, external libraries, or build steps.

## Project structure

```text
index.html
memories.html
speech.html
video.html
thank-you.html
style.css
README.md
images/
  1000127502.jpg
  1000127516.jpg
  1000127519.jpg
  1000128212.jpg
  1000131288.jpg
  1000131291.jpg
videos/
  student-appreciation.mp4
```

All six available photographs are preserved in `images/` and displayed in the gallery. The original appreciation video is extracted to `videos/student-appreciation.mp4` and plays on `video.html` in the browser's native video player.

The shared header and footer use a CSS-styled Dave Timi monogram and wordmark. Each photo shown on the home, memories, and video pages has a download link to its original image file.

## Preview locally

Open `index.html` in a browser. The pages use relative links and assets, so they also work when served from a subdirectory on GitHub Pages.

## Publish with GitHub Pages

1. Open the repository on GitHub and select **Settings**.
2. Select **Pages** in the **Code and automation** section.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose the `main` branch and the `/(root)` folder, then select **Save**.
5. After GitHub Pages finishes deploying, the project site URL format is:
   `https://oluwagbohund-ship-it.github.io/Birthday-website-/`

The site files are already at the repository root. GitHub account or repository settings must be enabled by someone with repository access.
