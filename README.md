## How to Use EZsheet?

### Step 1. Set up the service account on Google Cloud and download the credentials.json
[Google Docs for Service Account setup](https://cloud.google.com/iam/docs/service-accounts-create "Go to Google")  

### Step 2. Share access to the service account of your google sheets 
-   Service account  looks like your-service-account@your-project.iam.gserviceaccount.com
- Send the access of sheet to this 

### Step 3. Download the credentials.json
-   Add key first in your service account.
-   Download the credentials.json and upload it to drive or the location from where you are accessing in code.
-   I am running this script on google colab so add credentials.json in keys of Colab and name it GEMINI_API

### Step 4. Add sheet id
-   From the link of google sheets you can take id of sheet and add in keys of Google Colab and name it sheet_id.

### Step 4. Create images folder
-   Create images folder and put your cropped image containing column of roll numbers marked manually (handwritten).

I am running this script on google colab.

### Carefully check the locations in the script.
## You are ready to go.

### Step 5. Run the script
-   Ctrl+F9 for running all cells
-   if running locally:
    ```bash
    python ezsheet.py
    ```     

### Will ask for one input date or column in the sheet that you want to mark attendance for.
