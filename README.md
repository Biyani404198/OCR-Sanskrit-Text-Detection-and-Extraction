# OCR-Sanskrit-Text-Detection-and-Extraction
The goal of this project is to create bounding boxes for each line in the Sanskrit text that is provided in a PDF format. The bounding boxes should encompass entire lines of text rather than individual words. Each line should be saved as a separate JPG file.

Additionally, the project requires saving the coordinates of each bounding box in a JSON format. The JSON format should follow the structure provided below:
{
    "box1": {
        "top_left": [x1, y1],
        "top_right": [x2, y2],
        "bottom_left": [x3, y3],
        "bottom_right": [x4, y4]
    },
    "box2": {
        ...
    },
    ...
}

## Project Overview
1. Load the PDF file containing the Sanskrit text.
2. Extract each page as an image.
3. Perform preprocessing on the image to enhance OCR accuracy.
4. Use OCR to identify bounding boxes and text on each page.
5. Group the bounding boxes that belong to the same line of text.
6. Create bounding boxes around entire lines and save each line as a separate JPG file.
7. Save the bounding box coordinates in the specified JSON format for each page.

## Dependencies
The project requires the following libraries and tools:
1. OpenCV (cv2) for image processing.
2. Pytesseract (pytesseract) for Optical Character Recognition (OCR).
3. Pandas (pd) for data manipulation.
4. Numpy (np) for numerical operations.
5. JSON for handling JSON data.

Please note that the script assumes that you have provided the correct path to the image folder and the preprocessed output folder. 
For any questions or discussion, please feel free to reach out.
email - jobsforishanbiyani@gmail.com
linkedin - https://www.linkedin.com/in/ishan-biyani/
