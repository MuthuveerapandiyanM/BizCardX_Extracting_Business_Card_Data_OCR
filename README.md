# BizCardX_Extracting_Business_Card_Data_OCR
 OCR (Optical Character Recognition) technology to extract data from business cards. OCR technology allows the software to read the text on a business card and convert it into digital text that can be easily edited and stored.
 
 With BizCardX, users can simply scan a business card using a scanner or smartphone camera, and the software will automatically extract the relevant information such as the name, company, job title, phone number, email address, and more. This saves users the time and effort of manually entering the information into a digital database.
 
 Overall, BizCardX is a useful tool for anyone who frequently receives business cards and wants to efficiently organize and manage the information on them.
 
 ## Technologies Used
 
 1. OCR
 2. streamlit GUI
 3. SQL
 4. Data Extraction

## Libraries

1. Pandas - (To Create a DataFrame with the scraped data)
2. mysql.connector - (To store and retrieve the data)
3. Streamlit - (To Create Graphical user Interface)
4. EasyOCR - (To extract text from images)

## Workflow

To get started with BizCardX Data Extraction, follow the steps below:

+ Install the required libraries using the pip install command. Streamlit, mysql.connector, pandas, easyocr.

     *pip install [Name of the library]*
+ Execute the “BizCardX.py” using the streamlit run command.

     *streamlit run BizCardX.py*
+ A webpage is displayed in browser, I have created the app with three menu options namely HOME, EXTRACTION, VIEW where user has the option to upload the respective Business Card whose information has to be extracted and view by using Search Option.
