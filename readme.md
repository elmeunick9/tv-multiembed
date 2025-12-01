# MultiEmbed Sync: Peer-to-Peer Video Synchronization

MultiEmbed Sync is a simple, single-page web application designed to synchronize the URLs of two embedded YouTube videos between a Host device (TV/display) and a Controller device (mobile/desktop). It uses PeerJS for reliable, real-time, peer-to-peer data connection, requiring no central server for synchronization once the connection is established.

This is ideal for presentations, collaborative media viewing, or managing dual-screen video displays remotely.

## 🚀 How to Use

The application operates in two modes:

### 1. Host Mode (The Display)

This device runs the primary application, displays the two videos, and provides the connection details.

1. Open the application URL (e.g., your GitHub Pages link).

2. The app will generate a unique **Host ID**.

3. The screen will display the two video players and the Host connection details (ID, QR Code, and Controller URL).

4. Wait for the Controller device to connect. Once connected, the video links will update automatically whenever the Controller changes them.

### 2. Controller Mode (The Remote)

This device connects to the Host and allows you to change the video URLs in real-time.

1. On a separate device (like your phone), use the **Controller URL** provided by the Host device.

2. Enter the desired YouTube **watch link** (e.g., `https://www.youtube.com/watch?v=dQw4w9WgXcQ`) or **embed link** into the corresponding input fields.

3. Changes are sent instantly to the Host, and the videos will refresh.
