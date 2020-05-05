# Text-detection-model-for-vehicle-RCs

This is my project on detecting text in vehicle registration cards. I wished to take two different approaches to this. The first was to use Pytesseract and then use Amazon's excellent Textract API. I decided to use the original images, but set the dpi to 300, since that is the "golden rule" of digital image processing.

 I captured the following fields on the RC, using RegEx: 
- License plate number or Regn number
- VIN number or Chassis number
- Name
- Engine number
- Registration date
- Mfg. date
