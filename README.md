# TCM-Security-OSINT-Course-Walkthrough
Walkthrough: Image OSINT Cyber Security Course
This walkthrough will guide you through solving an image-based OSINT challenge to determine the location, city, and hotel associated with a given photo. Through this exercise, you will learn how to use various open-source tools and techniques to gather and analyze metadata, visual clues, and other online information to answer key questions.

# Question 1: Identifying the Location from an Image

![Image 1](https://github.com/user-attachments/assets/fe02ff1f-2754-40f1-abc7-0f3e402f5d3d)


## Overview
The goal of this analysis was to identify the location where a photo was taken, given clues in the image itself. The image featured a prominent building with a sign partially reading "Westin," along with a U.S. flag visible in the left corner.

### Step 1: Initial Observations
- The presence of the "Westin" signage on the building provided a significant clue. This prompted a targeted search for locations featuring "Westin" hotels.
- Other visible signs in the image, although blurred, and the U.S. flag suggested the location might be within the United States.
![image](https://github.com/user-attachments/assets/4a263d27-11a5-43e5-b1ee-e22a5824da1f)


### Step 2: Reverse Image Search
- To begin the search, I uploaded the image to **Google Images** using the drag-and-drop feature.
- Upon scrolling through the results, I found similar images that helped confirm the location based on visual matches to the building structure.
![image](https://github.com/user-attachments/assets/db90d82d-14fd-4a6c-a651-0189ae39c06e)


### Step 3: Identifying Similar Features
- The search results highlighted images of a building with matching features:
  - The top of the building has two small glass windows.
  - The background structure and layout appeared consistent with the original image.
- One specific image linked to the **2024 SIHMA Conference** webpage, where the venue was listed as **Westin Copley Place Hotel, Boston, MA**.
![image](https://github.com/user-attachments/assets/ab380e84-063e-42a4-a5bb-06654f5102d5)


### Step 4: Confirming the Location with Google Maps
- Using **Google Maps** and switching to satellite view, I entered the address for Westin Copley Place in Boston, MA.
- This view confirmed that the **Westin Copley Place** is across from the **Fairmont Copley Plaza Hotel**.
- Based on the camera angle and positioning, it’s likely that the original photo was taken from the Fairmont Copley Plaza Hotel, looking toward the Westin.
![image](https://github.com/user-attachments/assets/0c63fa6c-0c8c-4a93-a009-64df680a22d8)


### Step 5: Final Confirmation with Street View
- By switching to **Street View** and examining the area around Fairmont Copley Plaza Hotel, I could visually confirm the positioning of the two hotels and the angle matching the original image.
- The layout and visual alignment confirmed that the image was indeed taken from the Fairmont Copley Plaza Hotel, facing the Westin Copley Place Hotel.
![image](https://github.com/user-attachments/assets/cafe6dc9-4252-44f6-97a4-de29abfafbe2)

## Conclusion
The analysis determined that the photo was most likely taken from the **Fairmont Copley Plaza Hotel** in Boston, MA, with the **Westin Copley Place Hotel** visible in the background. This conclusion was supported by multiple visual clues and confirmed with reverse image search and mapping tools.
