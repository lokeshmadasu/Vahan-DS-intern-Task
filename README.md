# Vahan-DS-intern-Task
Extracting data from pdf file:

**A)Strategy used:**

step-1 : Downloaded the pdf file from target url.

step-2 : Splitted the main-pdf into individual pdfs where each pdf corresponds to respective page in main pdf.

step-3 : Extracted the names from all pdfs(pages).

step-4 : Cleaned the data using string operations

step-5 : Loaded the data into dataframe and converted into CSV file.

**B)Packages used:**

Below packages are need to be installed.

-->**textract**: textract is developed by amazon.it can easily extract the data from any pdf.it also uses OCR Techinique to recongnize the text in pdf.Engineers in Amazon have trained the Textract on millions of documents so that machines can virtually recognize the data from any type of pdf.it can easily extract data from scanned pdfs while other traditional packages are not.

Here in our problem also we are having Scanned pdf.

I have tried many packages but none of them worked well but textract does great job.

-->**pyPDF4** : I have used this package for doing some pdf operations.

-->**Pandas** :  Used for dataframes and to convert them into csv.

-->**re** : re stands for 'regular expression' . i have used it for some pattern matching operation.

-->**requests** : Used this to make a request to a webpage and then to get a response from the page.
in our situation i have used this for downloading the pdf file from target URL.

Out of 1063 names i have extracted 997 names.

*Note*: Before running the code make sure that you have installed all the packages which i mentioned above.



