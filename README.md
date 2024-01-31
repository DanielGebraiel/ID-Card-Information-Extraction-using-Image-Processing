
# ID Card Information Extraction

We saw that our faculty had a need of a quick way to record information on their system, Hence we thought of making an attempt to tackle this problem by making a traditional image processing solution which ultimately lies in 3 tasks:

- Finding the card in the image
- Extracting images of the information in the card
- Segmenting the words then the letters and using template matching to turn the words to actual text on the system

## The code in action

### Part 1: Card Detection

![App Screenshot](https://github.com/DanielGebraiel/ID-Card-Information-Extraction-using-Image-Processing/blob/main/screenshots/Part1_1.png)

![App Screenshot](https://github.com/DanielGebraiel/ID-Card-Information-Extraction-using-Image-Processing/blob/main/screenshots/Part1_2.png)

![App Screenshot](https://github.com/DanielGebraiel/ID-Card-Information-Extraction-using-Image-Processing/blob/main/screenshots/Part1_3.png)

### Part 2: Information Extraction

![App Screenshot](https://github.com/DanielGebraiel/ID-Card-Information-Extraction-using-Image-Processing/blob/main/screenshots/Part2_1.png)

![App Screenshot](https://github.com/DanielGebraiel/ID-Card-Information-Extraction-using-Image-Processing/blob/main/screenshots/Part2_2.png)

![App Screenshot](https://github.com/DanielGebraiel/ID-Card-Information-Extraction-using-Image-Processing/blob/main/screenshots/Part2_3.png)

![App Screenshot](https://github.com/DanielGebraiel/ID-Card-Information-Extraction-using-Image-Processing/blob/main/screenshots/Part2_4.png)

### Part 3: Template matching

![App Screenshot](https://github.com/DanielGebraiel/ID-Card-Information-Extraction-using-Image-Processing/blob/main/screenshots/Part3_1.png)

![App Screenshot](https://github.com/DanielGebraiel/ID-Card-Information-Extraction-using-Image-Processing/blob/main/screenshots/Part3_2.png)

![App Screenshot](https://github.com/DanielGebraiel/ID-Card-Information-Extraction-using-Image-Processing/blob/main/screenshots/Part3_3.png)

### The whole code in action

![App Screenshot](https://github.com/DanielGebraiel/ID-Card-Information-Extraction-using-Image-Processing/blob/main/screenshots/final_1.png)

![App Screenshot](https://github.com/DanielGebraiel/ID-Card-Information-Extraction-using-Image-Processing/blob/main/screenshots/final_2.png)


## Some Notes of Our Code

-Our project works accurately when given a picture that contains 1 
card, rotated by an angle less than 90 degrees clockwise or 
anticlockwise, and with the whole card visible. 

-Our project is robust in bad lighting conditions and succeeds in 
operating on cards with bad lighting most of the time.

-Template matching on the letters was very hard and challenging since 
the font is very hard to breakdown (EVEN BY HUMANS). Besides, the 
font was not found anywhere so the dataset was all taken manually 
with a snapping tool from actual IDs.

## Special Thanks

We would to give a special thanks to our amazing TA: Eng. Ziad Mansour, who supported us throughout this amazing project and being a part of how good this turned out <3
