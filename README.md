![image](https://github.com/PavanMohanN/FringeLib/assets/65588614/8b668e1c-3abf-4a00-9f34-f4c9b9842030)


# FringeLib: Extracting Key Features from Holographic Images

FringeLib is a Python library designed for extracting the main context from holographic images that require amplitude or phase correction. This library provides functionalities to enhance the quality and interpretability of such images, catering to both amplitude and phase correction needs.

## Features

- **frng_a**: Function to extract main context from images requiring amplitude correction. (both the functions can be called from FringeLib.pyc)
- **frng_p**: Function to extract main context from images requiring phase correction.
- Synthetic Datasets: Includes two synthetic datasets:
  - **Amplitude Dataset**: 100 images requiring amplitude correction.
  - **Phase Dataset**: 100 images requiring phase correction.
 
## Installation

You can install FringeLib using pip:
<code>!git clone https://github.com/PavanMohanN/fringe_pack.git</code><br>

## Usage
### Example Usage
<code>
import FringeLib
from FringeLib import frng_a, frng_p

# Example usage for image needing amplitude correction
result_a = FringeLib.frng_a(img)
plt.imshow(result_a,cmap='gray') 

# Example usage for image needing phase correction
result_p = FringeLib.frng_p(img)
plt.imshow(result_p,cmap='gray') 

</code>

## Project Directory Structure

<code>
  FringeLib/
├── dist/
│   └── fringe_pack-1.0-py3-none-any.whl  # Distribution package (example)
└── src/
    └── fringe_pack/
        ├── __init__.py                   # Package initialization
        ├── frng_a.py                     # Module for amplitude correction
        ├── frng_p.py                     # Module for phase correction
        └── fringe_pack.egg-info/         # Package metadata
            ├── dependency_links.txt
            ├── PKG-INFO
            ├── requires.txt
            ├── SOURCES.txt
            └── top_level.txt

</code>

**dist/**: Contains distribution packages (whl files) generated for deployment.

**src/**: Directory containing the source code for the project.

**fringe_pack/**: Package directory where your library's modules and initialization reside.

**fringe_pack.egg-info/**: Directory containing metadata generated by packaging tools (setuptools, wheel). It includes dependency information and other package details.


## Contact
For any questions or inquiries about FringeLib, please contact.

`Created in Jul 2024`

`@author: Pavan Mohan Neelamraju`

`Affiliation: Indian Institute of Technology Madras`

**Email**: npavanmohan3@gmail.com

**Personal Website 🔴🔵**: [pavanmohann.github.io](https://pavanmohann.github.io/)


---
