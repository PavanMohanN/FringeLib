# FringeLib: Python Library for Main Context Extraction from Holographic Images

FringeLib is a Python library designed for extracting the main context from holographic images that require amplitude or phase correction. This library provides functionalities to enhance the quality and interpretability of such images, catering to both amplitude and phase correction needs.

## Features

- **frng_a**: Function to extract main context from images requiring amplitude correction.
- **frng_p**: Function to extract main context from images requiring phase correction.
- Synthetic Datasets: Includes two synthetic datasets:
  - **Amplitude Dataset**: 100 images requiring amplitude correction.
  - **Phase Dataset**: 100 images requiring phase correction.
 
## Installation

You can install FringeLib using pip:
<code>pip install FringeLib</code><br>

## Usage
### Example Usage
<code>
import FringeLib
from FringeLib import frng_a, frng_p

# Example usage for amplitude correction
amplitude_image = load_amplitude_image()  # Replace with actual loading code
main_context_a = frng_a(amplitude_image)

</code>
