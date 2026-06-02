ShapeLab

ShapeLab is a browser-based motion graphics tool that converts uploaded videos into animated black-and-white shape systems. Instead of displaying a video normally, ShapeLab samples the video frame by frame and redraws it using graphic shapes such as circles, squares, triangles, diamonds, stars, crosses, rings, and lines.

The project is built with HTML, CSS, JavaScript, and the Canvas API. Video processing happens locally in the browser, and the final result can be exported as a WebM video.

Features
Upload or drag and drop a video
Convert video frames into black-and-white shape graphics
Choose from multiple shape styles
Adjust shape spacing, size, and threshold
Resize and reposition the source video
Use a solid colour or transparent background
Export the animated result as a WebM file
Choose export sizes such as 720p, 1080p, square, or vertical
Fully client-side video processing
Why This Project Exists

ShapeLab was created as an experimental browser tool for generating motion graphics from ordinary video footage. It turns video into a more abstract visual system, making it useful for posters, social media loops, live visuals, music visuals, and design experiments.

The goal is to make video feel less like footage and more like a flexible graphic material.

How It Works

ShapeLab uses an HTML video element and draws each frame onto a canvas. The frame is sampled at a lower resolution, and each sampled point is converted into a black or white shape based on its brightness value.

The result is a live animated grid of shapes that reacts to the video’s motion, contrast, and composition.

When exporting, the app records the canvas output using the browser’s MediaRecorder API and saves the result as a WebM file.

Tech Stack
HTML
CSS
JavaScript
Canvas API
MediaRecorder API
Browser File API

No external libraries or frameworks are required.

Usage

Open the app in a modern browser, upload a video, adjust the visual controls, then export the result.

Recommended browsers:

Chrome
Edge
Firefox

Transparent WebM export works best in Chromium-based browsers.
