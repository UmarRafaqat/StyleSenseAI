# StyleSense: AI-Based Fashion Design System for New Clothing Styles

## 1. Project Title
**StyleSense**: AI-Based Fashion Design System for New Clothing Styles

## 2. Introduction
**StyleSense** is an AI-driven system designed to generate innovative and unique clothing designs based on trending fashion styles. The system scrapes images of popular clothing items from online sources, processes them, and leverages advanced AI models to blend and generate fresh clothing styles.

### Key Features:
- Scrapes images of trending clothing from e-commerce platforms.
- Allows users to upload custom clothing images and descriptions for design generation.
- Enables blending of selected clothing images to create new, unique fashion designs.
- A Gradio-powered web interface for seamless interaction with the system.

## 3. Installation Instructions

### Prerequisites:
- A Google account (required to run the project in Google Colab).
- The setup is entirely managed within the Google Colab environment, so no local installation is required.

### Steps to Run the Project in Google Colab:
1. **Open the Project in Google Colab:**
   - Open the project in Google Colab by following this [link](https://drive.google.com/file/d/1q0_rN7gIFLVEpRupvBKAn-WLsRgFQ1oi/view?usp=drive_link).

2. **Run Setup Cells in Colab:**
   - In the Colab notebook, run each of the setup cells step by step. The setup will include:
     - Installing the required libraries.
     - Configuring the scraping script to fetch clothing images from trending sources.
     - Setting up the AI pipeline for generating new clothing designs.
     - Launching the Gradio interface for easy interaction.

3. **Dependencies will be automatically installed:**
   ```bash
   !pip install -r requirements.txt
   !pip install selenium webdriver-manager torch torchvision diffusers gradio beautifulsoup4 requests Pillow

# 4. Usage Guide
Running the Web Interface in Colab:
After completing the setup and scraping steps, you will receive a link to the Gradio app.

Open the link in your browser to access the StyleSense fashion design interface.

**App Features:** 

Image Gallery: View scraped trending clothing images or your uploaded images.
Upload Your Own Clothing Image: Upload an image of clothing you want to use for design generation and provide a description.
Select Images for Blending: Choose up to two images from the gallery to blend and generate a new clothing design.
Adjust Alpha Sliders: Control the influence of each selected image using alpha sliders.
Generate New Fashion Design: The system will use AI to generate a new clothing design based on the blended images and the provided description.
# 5. Results and Visuals
After running the app:

Input: You can select images from the gallery or upload your own clothing image along with a description.
Output: The system will generate a new fashion design based on the selected images and your description. This design will blend elements from the input images and apply AI creativity to generate a new style.
Example Flow:

Select two images (either from the gallery or uploaded).
Adjust sliders to control how the images should be blended.
Generate a new design using the blended result and the description you provide.
# 6. License Information
This project is licensed under the MIT License. You are free to use, modify, and distribute the project as long as you include the original license.