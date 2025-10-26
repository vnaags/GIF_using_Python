Imageio is a Python library that provides an easy interface to read and write a wide range of image data. It runs on Python 3.5 and above.Next, I imported it into VS Code Editor.
I then saved two png files of the SAME SIZE in the same folder where i created the python file.
Next I created a list that contains the locations of the image files.I also created an empty list that will be used to store the actual image data from these files.
Then, I used a for loop to go through the file paths and read the images using imageio library’s .imread() method.
The .imread() method loads an image based on the file path. So now, the images variable has all the images!
Lastly, I used the .imwrite() method to turn the images into a GIF.
The resultant gif appears in the same folder as the coded file !
