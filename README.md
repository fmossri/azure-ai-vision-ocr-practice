# azure-ai-vision-ocr-practice
Practicing with Azure AI Vision Studio Text Recognition functionalities


## Introduction
In this exercise, we practiced with Azure AI Vision Studio OCR capabilities, using it's sample "Extract text from image" resource through AI Vision Studio's portal. In this sample, we can upload image files to have any text written on them extracted and returned in editable text form or JSON.

## How it works
1. With a valid Azure Signature, navigate to the Azure [portal](portal.azure.com), click "+ Resource", search for "Azure AI Services" and select "Create". Choose or create a resource group, give the resource a unique name, choose your prefferred location and set the pricing tier to "Standard S0". Review, create and wait for the deployment to be complete.
![image](https://github.com/fmossri/azure-ai-vision-ocr-practice/assets/82612595/602b4e9e-54bd-4528-808e-506ea2d26959)

2. Navigate to the Azure AI Vision Studio [portal](https://portal.vision.cognitive.azure.com/). Click "view all resources" just under "Recent resources I've worked on", and select your newly created resource as default.
![image](https://github.com/fmossri/azure-ai-vision-ocr-practice/assets/82612595/ff207727-d531-4575-aae7-a3d883b783eb)

3. Get back to Vision Studio's main page, click "Optical Character Recognition" and select "Extract text from image".
![image](https://github.com/fmossri/azure-ai-vision-ocr-practice/assets/82612595/5c2f7767-cb72-43f9-8148-322f11086c8d)

4. After checking the acknowledgment box, here we can upload images to extract any kind of text written in it. Azure AI Vision Studio uses OCR capabilities from Azure AI services, which is the capability of identify and extract printed or hand-written characters from an image file, like a photo or a scanned document.
![image](https://github.com/fmossri/azure-ai-vision-ocr-practice/assets/82612595/1e73482f-d5f5-45d5-a751-4eb43d7134b4)

## Conclusion
From an Azure AI Services resource, Azure AI Vision Studio can efficiently extract any kind of non-editable text from an image file, and transform it into an editable text file. This is a very powerful AI feature which can be sharply raise the production efficiency of any business. Be it used to convert scanned printed bills into editable tables or physical legal documents into pdfs, it has the potential to strongly speed up chores and processes from any kind of organization.
