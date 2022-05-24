# Digital Bussiness Cards #
### Nahdet Misr AI, heraqi@aucegypt.edu ###

**Steps to generate or editing Digital Cards for employee with ID <span style="color:red">5</span> for example:**

1. Verify the infomration for employee number <span style="color:red">5</span> in present in row number <span style="color:red">5</span> in Business Cards.CSV file in data folder. The data items are separated with | symbol.
2. Generate the QR code that will be printed with on the physical card:
	1. Visit this website or similar QR code genertor websites: https://www.logodesign.net/qrcode-generator (You can use this front color which represents the company identity #24317E and add/or the company logo image, it can be found at assets\images\logo\logo.png)
	2. Add this link/URL: https://rawcdn.githack.com/heshameraqi/bussiness-cards/main/card.html?employee_number=5 and generate the QR to be printed (Please note to change <span style="color:red">5</span>.html according to the employee number)
3. Create or edit the data in X-vcard.vcf file in the folder vcards (You can open it was any text editor as Notebad)

(This rebosatory is for developers who are willing to continue development or changes to this project: https://github.com/heshameraqi/bussiness-cards-nahdetmisr)

![sample](./assets/Sample.png)