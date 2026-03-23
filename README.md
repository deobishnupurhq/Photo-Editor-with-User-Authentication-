# Photo Editor DEO BPR (v.1.MAR.2026)

The **Photo Editor DEO BPR** is a specialized desktop application designed for streamlined background removal and image enhancement. Built with a focus on precision and ease of use, it features an AI-driven processing engine and synchronized viewing tools to ensure professional-grade results for official documentation.

## Key Features

* **AI Background Removal:** Automated isolation of subjects using the `u2netp` processing model.
* **Synchronized Dual Viewers:** Compare your original and processed images side-by-side. Actions performed on one viewer (zoom or pan) are automatically mirrored in the other.
* **Smart Canvas Clamping:** Intuitive navigation that prevents images from being panned out of the visible frame.
* **Real-time Image Tuning:** Manual dials for adjusting mask size, brightness, contrast, and color saturation.

---

## Authorization & Getting Started

To ensure secure access, this software requires a one-time machine authorization and an active internet connection for every session.

### 1. Requesting Access
Before you can use the Photo Editor, you must register your workstation:
1.  **Install the Auth Tool:** Run the `AuthForm-1.0-win64.msi` installer provided with your package.
2.  **Submit Request:** Open the installed application and complete the brief authentication form.
3.  **Notification:** Contact the **Election Office of the O/o District Election Officer, Bishnupur**, to inform them that your request has been submitted.
4.  **Activation:** Once the O/o DEO, BPR grants access, you will be able to launch and use the Photo Editor immediately.

---

## Important Performance & Connectivity Notes

Please keep the following in mind for a smooth experience:

* **Mandatory Internet Connection:** An active internet connection is **strictly required** every time you launch the software. The application performs a security handshake to verify your authorization before loading the dashboard.
* **First-Run Delay:** During the very first launch, you may experience a significant lag or delay. This is normal, as the software is performing a one-time setup of the AI models (`u2netp`) and initializing system files.
* **Launch Handshake:** Because the software performs user authentication every time it runs, there will always be a brief delay at startup before the GUI dashboard appears.
* **Post-Startup Performance:** Once the dashboard has loaded, the software will run smoothly for the remainder of your session.
* 

---
## How to Use

### 1. Loading Images
* **Browse:** Click the **Browse Image** button to select a file from your local directory.
* **Drag & Drop:** Drag any supported image file (JPG, PNG, BMP, etc.) and drop it directly onto the **Input Image** area to begin processing.

### 2. Navigation & Viewing
The interface uses a synchronized system to help you inspect details across both the input and output images simultaneously.

* **Zooming:** Hover your mouse over either image and use the **Mouse Scroll Wheel** to zoom in for detail or zoom out for a full overview.
* **Moving (Panning):** Click and hold the **Left Mouse Button** on the image, then drag to move the view. The "Smart Clamping" feature ensures the image always stays within reachable bounds.

### 3. Fine-Tuning the Output
After the initial AI pass, use the control panel on the right to refine the result:
* **Mask Size:** Adjust this dial to clean up edges. Positive values expand the subject area, while negative values erode the edges to remove background "halos."
* **Image Enhancements:** Use the Brightness, Contrast, and Color dials to match the required visual standards for your project.

### 4. Saving Results
Click the **Save Output Image** button to export your finished work. The application handles high-quality encoding to ensure the output remains sharp and clear.

---

## Note
_On the first launch, the application will automatically configure the AI model. An active internet connection is recommended during this initial setup to verify configuration._



