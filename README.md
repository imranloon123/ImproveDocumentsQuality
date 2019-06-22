# ImproveDocumentsQuality
Designed a BOT using UiPath to validate and improvise the resolution (pixels) and quality (dpi) of the documents saved in image format.

Problem statement: There are around 45 Free Zones across the UAE which does company formation and setup. In all the cases, companies are required to provide basic documentation such as passport size photograph, passport copies and other documents. Most of the time the cases gets rejected due to poor quality (pixels & dpi value) of the scanned documents (images).

Objective: To improve customer experience by minimizing the REJECTION rate occur due to poor quality of the scanned documents (images).

Solution: Created a BOT (reusable component which can be used across all the 45 Free Zones) using UiPath to do the quality check of the scanned documents (images) by validating the pixels & dpi value against a threshold limit and enhance/improve the image quality by modifying its properties.

How to use it?

Install Paint.net.4.1.6 (https://www.getpaint.net/download.html)
Install UiPath Studio or Robot
Download the code repository from github (https://github.com/imranloon123/ImproveDocumentsQuality.git).
Copy the scanned documents (image format only) in Data/Input folder of the repository.
Run Main.xaml.
