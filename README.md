# Make Scalable Image.jsx

## installation

On a Mac, with CS6 and below, drop the script into `/Applications/Adobe Photoshop CS6/Presets/Scripts/`

I don’t know where to put it on a PC, or if anything has changed with the move to Creative Cloud. I bet Google does.

## execution

File » Scripts » Make Scaleable Image

## output

Given a 1024x768 image titled `piles-of-cash.jpg`, the script will render the following files in that image’s directory:

```
piles-of-cash.html
piles-of-cash/full.jpg [1024x768]
piles-of-cash/half.jpg [512x384]
piles-of-cash/quarter.jpg [256x192]
piles-of-cash/thumb.jpg [96x72]
```

Copy the `piles-of-cash.html` markup fragment into your page and upload the images, and you’ll be good to go.