AutoCrop
========

Library that allows automatic cropping of white borders according to LAB colour space deltas. Includes extended ImageView that automatically crops images. This is my first library, sorry for any mistakes/ bugs/ design flaws/ general teribbleness!

Usage
=====

1. Import as library project.
2. Add com.AutoCrop.AutoCropImageView to your XML 
3. Use setImage() to set image, it will automatically be cropped.
4. XML attributes disable_crop and tolerance do what they say on the tin, remember to use custom XML namespace.
