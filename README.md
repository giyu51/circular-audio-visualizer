# :notes: AudioVisualizer

AudioVisualizer is an interactive software project that transforms audio input into captivating visualizations. It provides a visually engaging representation of sound, creating a dynamic experience for users. :sparkles:
##Features

:sound: Real-time audio processing and analysis
:art: Visual representation of audio through rotating circles
:speaker: Circle size and movement based on the volume and intensity of sound
:fast_forward: Smooth transition and responsiveness to changes in audio input
## Installation

1. Clone the repository:

   ```shell
   git clone https://github.com/your-username/AudioVisualizer.git



Code Description:
The code for the AudioVisualizer project utilizes Python and the Kivy framework to create a visually stunning application. It makes use of the numpy library for numerical computations and the sounddevice library for capturing and processing audio input. The project consists of several classes and functions, including a custom RotatingButton class that enables the rotation of buttons, a CircleWidget class that represents the main visual element, and the MyKivyApp class that builds and runs the Kivy application. The code handles audio streaming, volume analysis, and the dynamic adjustment of the circle's size and position based on the audio input. With its modular structure and clear function descriptions, the code provides a solid foundation for extending and customizing the AudioVisualizer project.


# Usage

    Run the main application:
    ```shell

    python main.py
    ```
    The AudioVisualizer interface will open, displaying a dynamic rotating circle that reacts to audio input.

    Enjoy the immersive experience as the circle's size and movement change in response to the volume and intensity of the audio.

# Customization

    Adjust the speed of rotation by modifying the angle variable in the RotatingButton class.
    Control the size limits of the circle by modifying the min_size and max_size variables in the CircleWidget class.
    Customize the appearance of the circle by replacing the circle.png image file.

# Contributing

Contributions to AudioVisualizer are welcome! If you have any ideas, improvements, or bug fixes, please submit a pull request. For major changes, please open an issue to discuss your ideas beforehand.
# License

This project is licensed under the MIT License.
# Acknowledgments

    The project was inspired by the concept of audio visualization and interactive graphics.
    Special thanks to the contributors of the numpy, sounddevice, and kivy libraries for their valuable tools and resources.
