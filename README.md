## Step to run MultiLanguage Invoice Extractor
- Clone google-gemini in your local machine
- Download and install Anaconda from https://www.anaconda.com/download
- Type anaconda on windows search and open anaconda command prompt
- Navigate to mcqgen progect (in step 1) from conda prompt and/by follow below commands
    * cd <basepath>/google-gemini
    * conda create -p env python=3.11 -y
    * pip install -r requirement.txt
- Create a file with name '.env' in google-gemini folder
- Add below line in .env file
    * GOOGLE_API_KEY="Supply your secret token here"
- Run MultiLanguage Invoice Extractor with below command
    * streamlit run app.py --server.port 8080
    * Access the application on http://localhost:8080 from any of your favorite browser
    * Upload any png, jpg or jpeg invoice file of any language and in prompt ask any question e.g. what is the total bill?
    * Click on 'Tell me about the invoice' to extract the information.
