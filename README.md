# jpeg_dct-text_encryptor 

Create a JPEG file with text embedded with Menkman's DCT encryption 

## Installation

- Create a virtual environment in the base directory

`python -m venv venv`

- install the required packages with the requirements.txt file

`pip install -r requirements.txt`

- if you get an error due to numpy not being found, install numpy separately

`pip install numpy`

- then run the above command again to install the rest of the dependencies

`pip install -r requirements.txt`

## Usage

`python3 ./jpegEncoder.py inputBMPFileName outputJPEGFilename quality(from 1 to 100) DEBUGMODE(0 or 1) inputTxtFilename`

### Example

`python3 ./jpegEncoder.py ./lena.bmp ./output.jpg 80 0 ird.txt`

## TODOs

- Luminosity of the different characters should not vary with the luminosity quantification table.
- It seems like setting the coefficient too high fails encoding in the end
- Invalid characters stops the encoding

