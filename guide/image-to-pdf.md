# Convert images into PDF

- To covert images from CLI, we need **[ImageMagick](http://www.imagemagick.org/)** installed. If your machine doesn't have it, then you can [find it here](http://www.imagemagick.org/script/download.php). 
- Next, we will use **Git Bash** for Windows; if your machine doesn't have it, get it [from here](https://git-scm.com/downloads).   
  Linux/Unix or macOS users can use their default terminal. In case that doesn't work, please install [Git Bash](https://git-scm.com/downloads).
- Now, for better practice, open Git Bash or terminal in the same directory where your image(s) are located.
- Use any of the commands listed below to suit your needs. 


## Convert a single image into a pdf
```
magick convert img_name.jpg mydoc.pdf
```
Replace `img_name.jpg` with your desired file name. 


## Convert all images in a directory into a pdf
```
magick convert *.jpg mydoc.pdf
```
This will convert every files with `.jpg` extension into a single file `mydoc.pdf`.


## NOTE
- You can also use other image extensions, like:
  `.png`
  `.jpeg`
- You can give any name for the output pdf, i.e. instead of `mydoc.pdf`, you can use `output.pdf`, `new.pdf`, etc.
