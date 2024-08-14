# Automatic-multiple-choice-grading
Automatic multiple-choice grading using OMR, Opencv, and Python

Environment: Python: 3.10.14 && Conda: 24.7.1
Package: cv2, imutils.perspective, imutils, numpy, argparse, random, csv, PIL, os, pandas, and pytesseract.
Using example_test to make the tests with colored multiple-choices, then put them to folder images, this can be run all images in folder.

This project follows 7 steps:
Step 1: Detect the test in an image.
Step 2: Apply a perspective transform to extract the top-down, birds-eye-view of the test.
Step 3: Extract the set of bubbles (the possible answer choices) from the perspective transformed exam.
Step 4: Sort the questions/bubbles into rows.
Step 5: Determine the marked (bubbled in) answer for each row.
Step 6: Lookup the correct answer in our answer key to determine if marked choice was correct.
Step 7: Repeat for all questions in the test.
