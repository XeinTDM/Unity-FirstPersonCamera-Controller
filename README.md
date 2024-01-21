# Unity First Person Camera Controller

This Unity script provides a comprehensive first-person camera experience, suitable for use in first-person shooter games, exploration applications, or any project requiring a first-person perspective. The script features mouse-controlled camera look, head bobbing, dynamic field of view adjustments, and camera sway.

## Features

- **Mouse Look**: Camera rotation control with adjustable sensitivity.
- **Head Bobbing**: A realistic head bobbing effect, with customizable speed and amplitude.
- **Dynamic Field of View**: FOV changes when sprinting, enhancing the sense of speed.
- **Camera Sway**: Subtle camera sway motion for added realism.

## Getting Started

### Prerequisites

Ensure you have the following prerequisites installed:
- [Unity](https://unity.com/) (Version 2019.4 or later recommended)

### Installation

1. Clone the repo or download the script file directly.
   ```bash
   git clone https://github.com/XeinTDM/Unity-FirstPersonCamera-Controller.git
   ```
2. Add the FirstPersonCamera.cs script to your camera object in your Unity project.
3. Assign the necessary public fields in the Unity Inspector, particularly the playerBody and playerCamera.

### Usage

Adjust the public fields in the Unity Inspector to suit your game's needs:

- mouseSensitivity: Sensitivity of the camera's rotation based on mouse movement.
- playerBody: The Transform component of the player's body, for body rotation.
- playerCamera: The Camera component the script is attached to.
- Additional settings for head bobbing, FOV, and camera sway can be adjusted to achieve the desired effect.

### Contributing

Contributions to enhance the FirstPersonCamera script are welcomed. Please follow these steps to contribute:

1. Fork the Project
2. Create your Feature Branch (git checkout -b feature/AmazingFeature)
3. Commit your Changes (git commit -m 'Add some AmazingFeature')
4. Push to the Branch (git push origin feature/AmazingFeature)
5. Open a Pull Request

### License

This project is distributed under the MIT License. See the [LICENSE](https://github.com/XeinTDM/Unity-FirstPersonCamera-Controller/blob/main/LICENSE) file for more information.

### Contact

Discord - @xeintdm
Project Link: https://github.com/XeinTDM/Unity-FirstPersonCamera-Controller
