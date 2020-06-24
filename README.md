# qrcodereader

### Prerequisites

I followed [this](https://www.pyimagesearch.com/2018/05/21/an-opencv-barcode-and-qr-code-scanner-with-zbar/) guide for making the QR Code reader.

Install the following:

`sudo apt-get install libzbar0`
                                                            
`pip3 install pyzbar`

`pip3 install imutils`

For OpenCV, you can either use the following command to get it through pip:

`pip3 install opencv-contrib-python`

*Make sure you are doing this through pip3, not pip and also make sure you only get opencv-contrib-python and no others*.

Or you can compile from source (takes ~1-2 hours) using the instructions [here](https://pimylifeup.com/raspberry-pi-opencv/).

To use `barcode_scanner_image` run:

`python3 barcode_scanner_image --image qrcodetest.png`

To use `barcode_scanner_video` run:

`python3 barcode_scanner_video`

