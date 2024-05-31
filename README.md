# Oscilloscope Data Acquisition

This Python script facilitates the acquisition of waveform data from an oscilloscope and saves it to disk for further analysis or visualization. It utilizes the PyVISA library for instrument communication and Plotly for data visualization.

## Requirements

- Python 3.x
- PyVISA
- NumPy
- tqdm
- Plotly

Install the required dependencies using pip:

```bash
pip install pyvisa numpy tqdm plotly
```

## Usage

1. Clone the repository or download the `oscilloscope.py` file.
2. Ensure that your oscilloscope is connected to your computer and properly configured.
3. Update the script with the correct resource name for your oscilloscope.
4. Run the script using Python:

```bash
python oscilloscope.py
```

## Features

- Acquire waveform data from multiple channels simultaneously.
- Save acquired data to disk in NumPy binary format for easy storage and retrieval.
- Progress bars for data acquisition and file writing processes.
- Ability to plot acquired data from saved files using Plotly.

## Configuration

- `output_folder`: Specify the folder where the acquired data will be saved.
- `sources`: List of channel numbers to acquire data from.
- `source_names`: List of names corresponding to the channels for better identification.

## Customization

- You can customize the acquisition parameters such as the number of acquisitions and buffer size according to your requirements.
