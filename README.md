# GenreMIDI: AI-Powered MIDI Pattern Generation by EDM Sub-Genres

## Overview

GenreMIDI is an innovative project that leverages advanced machine learning techniques, including Google's Magenta library, to generate MIDI patterns across various musical genres. By utilizing Recurrent Neural Networks (RNNs), this project aims to create unique and genre-specific musical patterns that can inspire musicians, producers, and composers.

## Features

- MIDI pattern generation for multiple EDM musical genres
- Utilization of Google's Magenta library for advanced music generation
- Genre-specific model training and generation
- Customizable output parameters (e.g., tempo, complexity, pattern length)
- Easy-to-use command-line interface and Python API
- Future plans for seamless implementation in Max MSP with Node for Max

## Installation

1. Clone the repository:
   ```
   git clone https://github.com/cvbesJulian/Performance_RNN_For_EDM_RealTime.git
   cd GenreMIDI
   ```

2. **Download MIDI files from Google Drive:**
   [Download MIDI Files](https://drive.google.com/file/d/109fG77PEiT_vQbxsDw6T1e_coJMY5Eao)

3. Create a virtual environment:
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

4. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

## Usage

1. Train a model for a specific genre:
   ```
   python train.py --genre techno --dataset_path /path/to/techno_midis
   ```

2. Generate MIDI patterns:
   ```
   python generate.py --genre techno --num_patterns 5 --output_dir ./output
   ```

3. Customize generation parameters:
   ```
   python generate.py --genre house --num_patterns 3 --tempo 120 --complexity 0.7 --output_dir ./output
   ```

## Supported EDM Genres

- House
- Techno
- Trance
- Hip-Hop
- Progressive
- Tech House
- (More genres can be added by training on appropriate datasets)

## Technical Details

GenreMIDI currently uses Recurrent Neural Networks (RNNs), which are implemented with TensorFlow and the Magenta library, to learn and generate musical patterns. The project employs the following key technologies:

- TensorFlow 2.x
- Magenta
- Python 3.8+
- Numpy
- Pretty_midi

In the future, we plan to transition to TensorFlow.js for a more seamless implementation in Max MSP with Node for Max.

## Contributing

We welcome contributions to GenreMIDI! Please see our [CONTRIBUTING.md](CONTRIBUTING.md) file for details on how to get started.

## License

This project is licensed under the Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0). See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Google's Magenta team for their incredible work on AI-powered music generation
- The open-source community for their valuable contributions to machine learning and music technology

## Contact

For questions, suggestions, or collaborations, please open an issue in this repository or contact the project maintainers:

- Ostin Solo: [contact@ostinsolo.co.uk](mailto:contact@ostinsolo.co.uk)
- Julian: [Julianda45@gmail.com](mailto:Julianda45@gmail.com)
