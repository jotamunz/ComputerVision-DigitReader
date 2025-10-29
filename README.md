# Computer Vision Digit Reader

A python notebook that can identify numerical digits in an A4 sheet of paper from an image. First, the edges of sheet are found and the intersection between them is used to determine the corners of the page. Next, the sheet is straightened and the digits are extracted. Last, each digit is identified using a CNN trained on the MNIST dataset.
