# Mathematical Morphological Image Processing

Implementation of mathematical morphological image processing based on the assigned research paper:

**"A Study on Image Processing Using Mathematical Morphological"**

## Paper Information

- **Authors:** Khairul Anuar Mat Said and Asral Bahari Jambek
- **Conference:** 3rd International Conference on Electronic Design (ICED)
- **Year:** 2016

## Techniques Implemented

- Manual Grayscale Conversion
- Manual Otsu Thresholding
- Binary Erosion
- Binary Dilation
- Opening
- Closing
- White Top-Hat (WTH)
- Black Top-Hat (BTH)
- Mathematical Morphological (MM) Output
- Structuring Element Comparison

## Implementation

The main image processing operations were implemented using custom functions rather than built-in morphological functions.

### Main Structuring Element

A rectangular **4 × 8** structuring element was used for the principal result.

### Input Image

- Resolution: **600 × 597 pixels**
- Otsu Threshold: **128**

## Results

The final mathematical morphological output was compared with the original grayscale input.

- Changed Pixels: **90,129**
- Changed Pixel Percentage: **25.1616%**
- MAE: **7.0548**
- MSE: **510.6635**

## Repository Contents

```text
├── Morphological_Image_Processing.ipynb
└── README.md
