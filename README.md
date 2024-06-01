## Picture to ASCII

I thought converting a picture to ASCII art looked really cool, so I wanted to learn how it's done.

### What I Learned

- **Learning to Convert an Image to ASCII:** 
  - **PIL Library:** I learned how to use the Python Imaging Library (PIL) and the `Image` module from it.
  - **Grayscale Conversion:** To convert an image to ASCII, the first step is turning it to grayscale.
  - **Image Tiling:** You need to break the image into tiles based on its width and height, ensuring specific dimensions so the image isn't too small.
  - **ASCII Generation:** By creating a list of character strings, you can generate the ASCII image. This involves calculating dimensions and returning the text image.
  - **File Path Specification:** The program requires a specific input for the image file path to convert it to ASCII.

To use the program, open the command line or console and run the following command (ensure the program is open and replace `"FILEPATH"` with your actual image file path):

```bash
python ImageTOASCII.py --file "FILEPATH"/image.jpg --scale 0.5 --cols 100 --out ascii_art.txt --morelevels
```
