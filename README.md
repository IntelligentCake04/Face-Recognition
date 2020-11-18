# Face-Recognition
A python face recognition program using the opencv library

<h2>Setup</h2>

- Make sure you are running python 3.6 and above (this is what I have tested)
- Run `pip install requirements.txt` to install required packages
- This program works by encoding pre-defined faces into a file and then reading that file for values to decide whether or not the image you want to scan has someone known in it.
- For this to work, your images need to be put into the `Images/<PERSON NAME>/` folder where `<PERSON NAME>` is replaced with the person's name.

<h2>How to use</h2>

- Put some images into the `/Images/<PERSON NAME>/` folder
- Then run `main.py` to encode the images into the `face_enc` file
- After this you can either run `face_rec_images.py` and type in the path of the image file you want to detect faces for or you can run `face_rec_webcam.py` to utilise your webcam and detect faces on your live webcam feed.
