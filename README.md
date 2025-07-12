# ☁️ Cloud-Kinetics – Take-Home QA Assessment

This repository contains the completed API Testing and Test Automation assessment

Question 1 – API Testing

For this section, I analyzed and tested 3 API requests from the [Pos Malaysia Rate Calculator](https://www.pos.com.my/send/ratecalculator) page using **Chrome DevTools** and **Postman**.

API Endpoints Tested:

1. **GET** – Retrieve country list for the "To" dropdown  
2. **POST** – Submit origin postcode  
3. **POST** – Calculate shipping rate (based on country, postcode, and weight)

Tools Used:
- [Postman (Desktop)
- Chrome Developer Tools (Network tab)

Question 2 – UI Test Automation

I created an automation script using **Katalon Recorder** (browser extension) to validate the functionality of the rate calculator UI.

Key Scenarios Covered:
- Scroll elements into view using `scrollIntoView` JS execution
- Input postcode into "from" section
- Select country from dropdown
- Click on **Calculate** button
- **Verify multiple shipping quote options** are shown

> The script is saved as a plain `.txt` file due to export limitations and can be copied into Katalon Recorder.

