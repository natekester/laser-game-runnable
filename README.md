# Laser Click Game (Runnable)

**Windows Only**

This is the standalone runnable version of the Laser Click application written in golang. It allows you to control your computer mouse using a physical laser pointer and a webcam.

## How to Run

1.  **Download**: Clone this repository or download the ZIP.
2.  **Run**: Double-click `laser-click-game.exe`.
    *   *Note: All included DLLs must remain in the same folder as the executable.*

## Normal Setup Flow

1.  **Environment**: 
    *   Keep the room relatively dark (not bright).
    *   Low light is fine, but ensure the lighting remains constant. 
    *   **Changing light conditions will interfere with laser detection.**
2.  **Auto Calibration (`a`)**: 
    *   Once the app is running, press `a` on your keyboard.
    *   The app will automatically detect the corners of the projector/screen and adjust the camera exposure levels.
3.  **Start Playing**:
    *   Use `m` to enter Click Mode or `f` to enter Follow Mode.

## Modes & Controls

-   `a`: **Auto Calibrate** - Automatically find screen corners and set exposure.
-   `t`: **Test Mode / Settings** - Fine-tune thresholds, offsets, and dilation. Use this if the laser isn't being detected reliably.
-   `m`: **Click Mode** - Standard mode for clicking elements on screen.
-   `f`: **Follow Mode** - Mouse cursor follows the laser without clicking.
-   `s`: **Save Settings** - Save your current configuration.
-   `ESC` / `q`: **Exit**

## Troubleshooting

If the mapping between your laser and the screen is slightly off, enter **Test Mode (`t`)** to adjust the offsets and parameters until the detection is perfect.
