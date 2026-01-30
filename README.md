# Coco Image Display
Vib Coded app to display 5000 random Coco images .  I use this script for testing yolo identification by pointing a webcam at the computer screen.  The images can be downloaded using wget http://images.cocodataset.org/zips/val2017.zip.  

Set your path to the images with IMAGE_DIR

The script will attempt to assess the size of your desktop display then scale the images to a percentage of the screen.  Set the scaling with the SCREEN_SCALE variable.

Default behavior is to display each image for 2 seconds.  Change the seconds with DISPLAY_SECONDS.
