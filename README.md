# Canadian Linear Nutrition Facts Label Generator

A web-based tool for creating Canadian-compliant linear format nutrition facts labels with PNG export capability.

## Features

- **Interactive Form** - Easy-to-use interface for entering nutrition information
- **Real-time Generation** - Instantly generates nutrition labels as you input data
- **Automatic Calculations** - Calculates % Daily Value (%DV) for all applicable nutrients
- **PNG Export** - Save your nutrition labels as high-quality PNG images
- **Canadian Format** - Follows Canadian nutrition labeling regulations for linear format
- **Responsive Design** - Works on desktop and mobile devices

## Supported Nutrients

The generator supports all required Canadian nutrition label components:

- **Serving Information**
  - Serving Size (customizable)
  - Calories

- **Macronutrients**
  - Total Fat (with %DV)
  - Saturated Fat
  - Trans Fat
  - Cholesterol
  - Sodium (with %DV)
  - Total Carbohydrate (with %DV)
  - Dietary Fiber (with %DV)
  - Total Sugars
  - Protein

- **Micronutrients**
  - Potassium (with %DV)
  - Vitamin D (with %DV)
  - Calcium (with %DV)
  - Iron (with %DV)

## How to Use

1. **Enter Nutrition Information**
   - Fill in the form fields with your product's nutrition data
   - Use decimal values where needed (e.g., 2.5g)
   - Enter 0 for nutrients not present in your product

2. **Generate Label**
   - Click "Generate Label" to create the nutrition facts label
   - The label updates automatically with your entered values
   - %DV percentages are calculated automatically

3. **Save as PNG**
   - Click "Save as PNG" to download the label as an image
   - The image is exported at 3x resolution for high quality
   - File is saved as "nutrition-facts-label.png"

## Daily Value Reference

The tool uses the following Canadian Daily Values for calculations:

| Nutrient | Daily Value |
|----------|-------------|
| Total Fat | 78g |
| Saturated + Trans Fat | 20g |
| Cholesterol | 300mg |
| Sodium | 2300mg |
| Potassium | 4700mg |
| Total Carbohydrate | 275g |
| Dietary Fiber | 28g |
| Total Sugars | 50g |
| Protein | 50g |
| Vitamin D | 20mcg |
| Calcium | 1300mg |
| Iron | 18mg |

## Label Format

The generated label follows Canadian linear format specifications:

- **Line 1:** Nutrition Facts header, serving size, and calories
- **Line 2:** Fat, saturated fat, trans fat, cholesterol, and sodium (continuous)
- **Line 3:** Carbohydrate, fiber, sugars, protein, potassium, vitamin D, calcium, and iron (continuous)
- **Line 4:** "Not a significant source of" statement for zero-value nutrients
- **Line 5:** %DV explanation and reference guide

## Technical Requirements

- Modern web browser (Chrome, Firefox, Safari, Edge)
- JavaScript enabled
- Internet connection (for html2canvas library)

## Dependencies

- **html2canvas** (v1.4.1) - For PNG export functionality
- Loaded from CDN: `https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js`

## Installation

No installation required! Simply:

1. Download the HTML file
2. Open it in any modern web browser
3. Start creating nutrition labels

## Tips for Best Results

- **Accuracy**: Double-check all values before generating the final label
- **Rounding**: Follow Canadian rounding rules for nutrition values
- **Zero Values**: Enter 0 for nutrients not present (they'll be listed as "not a significant source")
- **Serving Size**: Be specific with serving size descriptions (e.g., "1 cup (250mL)" or "1 package (50g)")
- **Export Quality**: The PNG export is high resolution (3x scale) - suitable for print and digital use

