## ResNet50 on Oxford Flowers-102
---

## Contributors

1) [Aditya Jadhav](https://github.com/iamjadhav)
M.Eng Robotics, University of Maryland.

## Overview

A pre-trained ResNet50 is used for classification of 102 flower classes from the Oxford Flowers-102 dataset.

## License 

```
MIT License

Copyright (c) 2023 Aditya Jadhav

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE 
SOFTWARE.
```
## Dependencies

- PyTorch computer vision libraries with other libraries mentioned in the notebook

## To Run the notebook

Arrange directory structure as given below (if using Google Colab or Jupyter Notebook)
```
/<mounted_drive_path>/data/flowers-102
```
Uncomment the following line in cell 7 if running the notebook for the very first time
```
# # create_trn_val_tst_dirs()
```
Similarly, uncomment the move() lines in cell 11 to move images into class directories
then run the notebook normally
```
# move(train_dir)
```
## Links

Video --> [Link](https://www.google.com/)

