# simple-vtuber

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A lightweight, browser-based VTuber application that uses your webcam to render a simple, stylized avatar in real-time with MediaPipe Face Mesh.

## Live Demo

**[https://code4fukui.github.io/simple-vtuber/](https://code4fukui.github.io/simple-vtuber/)**

The demo renders a minimalist avatar that tracks your facial movements, including eyes, eyebrows, and mouth. You can customize the avatar's appearance and control the camera view directly in your browser.

## Features

-   **Real-Time Face Tracking:** Uses MediaPipe Face Mesh to accurately track 478 facial landmarks from your webcam feed.
-   **Stylized Avatar:** Renders a simple vector avatar with a customizable face color, eyes, eyebrows, and mouth that mimic your expressions.
-   **Customizable Overlays:** Toggle the visibility of the original camera feed, add a pair of eyeglasses, or view the underlying facial mesh for debugging.
-   **Camera Controls:** Easily switch between front and back cameras, enable mirror mode, and zoom in on the action.

## How to Use

1.  Open the [live demo link](https://code4fukui.github.io/simple-vtuber/) in a modern web browser.
2.  Grant the requested camera permissions.
3.  Use the on-screen controls to customize your avatar and stream.

To run locally, clone this repository and open the `index.html` file in your browser.

## Controls

-   **Face Color:** Opens a color picker to change the avatar's skin tone.
-   **Show Original Image:** Toggles the visibility of your webcam feed in the background.
-   **Mirror Mode:** Flips the canvas horizontally.
-   **Back Camera Mode:** Switches to your device's rear-facing camera.
-   **Show Debug:** Displays the raw MediaPipe facial landmarks and tessellation.
-   **VTuber Mode:** Toggles the main stylized avatar rendering.
-   **Draw Eyeglasses:** Overlays a pair of glasses on the avatar.
-   **Zoom:** Select a zoom level from x1 to x5.

## Credits and Technology

This project is built upon the following libraries and resources:

-   **Core Technology:** [MediaPipe Face Mesh](https://chuoling.github.io/mediapipe/solutions/face_mesh.html)
-   **Reference Project:** [mediapipe-test](https://github.com/code4fukui/mediapipe-test/)
-   **Camera Handling:** [Camera.js](https://code4fukui.github.io/Camera/Camera.js)
-   **Promotion:** [無料で気軽にバーチャル配信、みんなのライブ配信「ふわっち」](https://whowatch.tv/)

## License

This project is licensed under the terms of the LICENSE file.