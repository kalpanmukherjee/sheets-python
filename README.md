# sheets-python

Google sheets + Python code to modify and get data from google sheets using google developer APIs 

# requirements

1) google developer account 
2) python libraries - gspread and oauth2client
3) sharing permission for the intended google sheet

# procedure

1) create new project in your google developer console
2) add google drive and google sheets APIs
3) create google drive credentials, select "service account key" and the following configuration, give any service account name
![config](https://github.com/kalpanmukherjee/sheets-python/blob/master/1.JPG)
4) rename the downloaded json file to 'client-secret.json', place it in the same folder as the python file
5) open the json file in a text-editor and locate 'client-email' field
6) copy the email next to this field and give it shared access to your google sheets
7) run spreadsheet.py
  
# end
