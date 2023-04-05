# Spectrometer

This Python script uses PyAudio and Matplotlib libraries to create a real-time spectrometer that displays the frequency spectrum of an audio input stream in decibels (dB). The script reads audio input data in chunks of BUFFER length, applies the Fast Fourier Transform (FFT) to the data, and converts the FFT output to dB. The script then uses Matplotlib to plot the data on a logarithmic scale.

## Dependencies

    PyAudio
    Numpy
    Matplotlib

## Usage

1. Clone the repository to your local machine.
2. Install the dependencies using pip.
3. Run the script.

    git clone <https://github.com/jinumi/pythonaudiospectrum.git>
    cd spectrometer
    pip install -r requirements.txt
    python spectrometer.py

## License

This project is licensed under the MIT License - see the LICENSE file for details.
