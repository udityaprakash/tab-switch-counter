# Test Your Browser Activity

This is a **simple web app** that demonstrates two features:

1. **Tab Switch Counter**  
   - Tracks how many times a user switches between tabs/windows.  
   - Uses multiple detection methods (Visibility API, window focus/blur, lifecycle events, requestAnimationFrame gaps, mouse leave events).  
   - Displays a live counter and logs the detection reason with timestamps.  

2. **Camera & Audio Test**  
   - Lets users test their **webcam** and **microphone** directly in the browser.  
   - Video feed is displayed on the page.  
   - Microphone input levels are visualized using an animated bar (Canvas API).  

---

## 🚀 Features
- Responsive layout:
  - On **desktop**: Left = Tab counter, Right = Camera/Audio test.  
  - On **mobile (<500px)**: Left section stacks on top, Right section below.  
- Smooth styling with shadows, rounded corners, and modern UI.  
- Works directly in browser — no external libraries required.  
- Error handling if camera/microphone permissions are denied.  

---

## 🛠️ Tech Stack
- **HTML5** (semantic structure)  
- **CSS3** (Flexbox + Responsive design with media queries)  
- **JavaScript (Vanilla)**  
  - Page Visibility API  
  - Focus/Blur events  
  - RequestAnimationFrame  
  - WebRTC (`navigator.mediaDevices.getUserMedia`)  
  - Web Audio API (for mic visualization)  

