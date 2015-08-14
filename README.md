# Adding Files to Nitrous

We've seen how we can add images to our websites that are hosted on the web already, but what if we want to add our own images like a selfie we took on our phone? 

Really, we need the image saved in Nitrous in the same directory (folder) where our work is. If I'm working on a website about how much I love popcorn, I want to have a directory dedicated specifically to that individually website. I might have a lot of other files and directories inside the main one, but thats okay. Any images that I personally take and want to include in my website need to be stored in my the main directory for my project. So how do I save an image in Nitrous?


+ Click the Gear button in the file browser.

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-add-image.png" alt="Click gear icon">

+ Click Upload Files

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-add-image-upload-file.png" alt="upload file">

+ Drag/Drop the Images you want to include, or use the file browser to choose them.

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-add-image-browse.png" alt="browse">

+ Click Upload

<img src="https://s3.amazonaws.com/after-school-assets/nitrous-add-image-upload.png" alt="upload">

+ Move the image to the project directory for the website you're working on

The image `IMG_8200.JPG` is saved in the main directory in Nitrous, which is named `nitrous`. Inside of the `nitrous` directory there is a directory called `code`. Both `code` and `IMG_8200.JPG` are located in the same directory. Let's say I wanted to move `IMG_8200.JPG` into the code directory.

In terminal, enter `mv IMG_8200.JPG code`. 

The `mv` command moves a file. I have to tell Nitrous what file to move (in this case `IMG_8200.JPG`) and then where to move it `code`. 

You can use the `mv` command as many times you like to continue to move a file around.
