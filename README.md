# Edge-Linking-using-Hough-Transformm
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## Output

### Input image and grayscale image
<img width="374" height="510" alt="image" src="https://github.com/user-attachments/assets/1a082441-4092-4b8c-bc3b-a466c747cb39" />

<img width="394" height="527" alt="image" src="https://github.com/user-attachments/assets/2aa1298c-62e7-4f8b-b2fd-fa4bef560432" />

### Canny Edge detector output
<img width="381" height="518" alt="image" src="https://github.com/user-attachments/assets/e53d626d-8187-4edd-90a4-61b24848dc53" />


### Display the result of Hough transform
<img width="393" height="515" alt="image" src="https://github.com/user-attachments/assets/5fcdbb50-7700-4eac-ad0c-371457435536" />

