# Stereo Imager Plugin

![Plugin Screenshot](![Untitled](https://github.com/user-attachments/assets/b0ff2a51-70f8-4788-a6b3-50ddc6a76f63))

A stereo imager plugin built using JUCE, featuring a 3D sphere visualization to display stereo audio data. The plugin is designed to be efficient and visually appealing, offering users a comprehensive tool for stereo imaging and phase correlation metering.

## Features

- **3D Sphere Visualization**: Real-time visual representation of stereo audio data using OpenGL and shaders.
- **Phase Correlation Meter**: Optimized meter to visualize phase relationships between audio channels.
- **Customizable Sliders**: Adjust parameters such as mid/side balance, crossfeed, and width with intuitive controls.
- **High Performance**: Optimized for minimal CPU usage while maintaining high-quality visual output.
- **Professional UI**: Components designed for depth and dynamics, blending seamlessly with the plugin background.

# Usage

## Parameters
- **Width: Start at 50% (normal width) and allow a significant increase in width up to 100%.
Mid/Side: Adjusts the balance between mid and side signals.
Crossfeed: Controls the amount of signal bleed between channels.
Stereo Visualization:
Displays a 3D representation of stereo imaging using OpenGL.
Shows a circle for maximum stereo imaging or an oval for different stereo balances.
Responsive to audio peaks and clipping, offering dynamic feedback.
Contributing

Acknowledgments

Thanks to the JUCE team for providing a robust framework for audio plugin development.
Special thanks to the OpenGL community for the resources on shaders and 3D rendering.
