# jpeg_dct-text_encryptor 

Example:
Ceate a JPEG file with text embedded with Menkman's DCT encryption 

### **Usage:**

install the required packages with the requirements.txt file

https://pip.pypa.io/en/stable/cli/pip_install/#cmdoption-r

run 

`python3 ./jpegEncoder.py inputBMPFileName outputJPEGFilename quality(from 1 to 100) DEBUGMODE(0 or 1) inputTxtFilename`


#### Example

`python3 ./lena.bmp ./output.jpg 80 0 ird.txt`

## TODOs

- Luminosity of the different characters should not vary with the luminosity quantification table.
- It seems like setting the coefficient too high fails encoding in the end

