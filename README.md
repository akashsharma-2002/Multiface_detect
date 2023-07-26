# Multiface_detection

This model detects Multiple faces in an image.
This model uses opencv and google.colab.patches for building up the model

# How to run this model?

download the dependency And run this in google collab 

!pip install opencv-python

once the dependency is installed you can now run the libraries












<img width="612" alt="Screenshot 2023-07-27 at 3 40 27 AM" src="https://github.com/akashsharma-2002/Multiface_detect/assets/73756172/a602eacb-a627-4fb8-bcb0-548a4829b18d">









Now upload haarcascade_frontalface_default.xml in the current working dir which will be available in the files provided. and upload the image where Face detection needs to be done. In my case, I have named the image file as new_img.jpg and after uploading this two files it should look like this.










<img width="351" alt="Screenshot 2023-07-27 at 3 42 47 AM" src="https://github.com/akashsharma-2002/Multiface_detect/assets/73756172/40e81d82-9dfa-4f5a-9d85-66a007c731b1">






Now copy the code from the "Multiface_detection.ipynb"  And finally You shall see an output that generates rectangular figures around the faces predicted. In my case, the output looks like this.




