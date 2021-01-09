# PHP OCR

Optical character recognition helps software recognize patterns within an image. It is common to read image and convert it into text format. Using this example, you can write [PHP OCR code to convert images into text programmatically](https://www.veonconsulting.com/get-to-know-to-use-ocr-within-php-to-convert-image-to-text/). Let us look at the program in more details so check the following aspects. 

**Set up / Pre-requisites / how to use** 

We will be using a PHP library to read an image. In this case we will be using a matured library called Tesseract. To be able to use this example, you should have the following.
* 	Working knowledge of how PHP works. 
* [Download the Tesseract library from here.](https://github.com/tesseract-ocr/tesseract) 
* Should have basic set up to write and test a PHP program. This would mean that you have a WAMP / LAMP set up. Having a IDE is recommended but not mandatory. 

## How to execute PHP OCR example
To execute the sample program, please follow the step-by-step instruction given below. They are detailed in sequence.
 * **a.**	Set up environment ( WAMP / LAMP)
 * **b.**	Download and install Tesseract library. You can use sudo and brew command respectively depending on whether you are using Ubuntu or macOS.
 * **c.**	Add reference to Tesseract library within PHP. You can use the following statement for the same. $ composer require ….. tesseract_ocr
 * **d.**	Save any image containing text at a path accessible on your machine. 
 * **e.**	Use the code provided in the repository to parse the image into text.

## PHP OCR Business Case / When to use
There are many real-life examples where OCR may be needed within the PHP Code. Some of the examples are given below. 
* (i)	**Document parsing** – In many cases a document may need to be uploaded and parsed. In many cases they may be a scanned image instead of a readable document. Using OCR helps recognize the text in the document and support further processing. 
* (ii)	**Document tagging and search relevance** – Using relevant keywords in the document, it could be tagged or indexed and its relevance could be ascertained for further use. For example while processing scanned resumes of the candidates while hiring for a CAD Specialist, you could process and score them as per their relevance. 
* (iii)	**Mobile Check Deposit** – Many banks enable their customer to upload check via Mobile APP. This uses advanced concept called [MICR to recognize the Bank Account Number and Routing Number during check deposit.](https://en.wikipedia.org/wiki/Magnetic_ink_character_recognition)
* (iv)	**Credit Card Number** – Many companies like Amazon, enable companies to take a picture of their credit / debit card instead of entering them manually. This saves time and eliminates manual errors while putting in the card details as well. 
* (v)	**Fleet and Parcel tracking** – When tracking fleet and parcel, users can take picture of the bar code and process the same within a PHP application. 

## Conclusion and further learning
While using OCR within PHP, please take note that you will have to handle exceptions in an elaborate manner. This is because the image format may not always be the same. 




# Veon Consulting


Veon brings best in consulting and integration solutions on Salesforce, SugarCRM, and SAP. It is an innovative company which deals best of the breed solution using integration solutions on the above platforms. making small and medium enterprise become smarter.

 [Veonconsulting Pvt Ltd](https://www.veonconsulting.com/).
