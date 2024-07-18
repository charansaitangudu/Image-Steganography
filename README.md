# Image-Steganography
Image steganography is a technique used to hide secret information within digital images. It leverages the characteristics of digital images to embed data in a way that is not easily noticeable to human eyes or detectable without specific tools or knowledge.
# Key Concepts:  
Carrier Image: The image that will carry the hidden data. This image should look like any ordinary image and its primary purpose is to serve as the medium for hiding information.

Payload: The secret information that needs to be hidden. This could be text, another image, audio, or any other data type.

Stego-Image: The resulting image after the payload has been embedded into the carrier image. Ideally, this image should appear identical to the original carrier images.

# Methods:

* Least Significant Bit (LSB) Insertion:
This is the most common and simplest method of image steganography.
It involves modifying the least significant bit of each pixel in the carrier image to embed the payload.
For example, if the original pixel value is 10010110 and you want to hide 1, the new pixel value might be 10010111.
* Masking and Filtering:
This technique hides information by marking the image with a watermark that can be detected or extracted by special methods.
It's often used for robust watermarking rather than fragile data hiding.
* Transform Domain Techniques:
These methods embed information in the frequency domain of the image.
Common techniques include Discrete Cosine Transform (DCT), Discrete Wavelet Transform (DWT), and Discrete Fourier Transform (DFT).
These methods are more robust against image processing operations like compression and scaling.
* Spread Spectrum Techniques:
These techniques distribute the payload across multiple frequencies or across the entire image.
It makes the embedded data more resistant to noise and other disturbances.
* Adaptive Steganography:
This approach adapts the embedding process based on the carrier image content.
It usually embeds data in the more complex areas of the image where changes are less noticeable.

# Applications
Confidential Communication: Sending secret messages hidden within images to avoid detection by unauthorized parties.
Digital Watermarking: Protecting intellectual property by embedding copyright information within digital images.
Steganographic File Systems: Creating file systems where data is stored in an embedded form within other files.
Authentication and Integrity Checking: Embedding information that can be used to verify the authenticity and integrity of an image.






| man.jpeg | encrpted.png |
|:--------:|:-------:|
| <img src="man.jpeg" alt="Original Image" height = "300" width="400"/> | <img src="encrpted.png" alt="Encoded Image" height = "300" width="400"/> |
| Original | Encoded |
