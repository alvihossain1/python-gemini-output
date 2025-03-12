# Python Gemini output and predictions.
### **RUN THE FOLLOWING COMMANDS BELOW ONLY
#### Follow the steps
#### Step 1:
```
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
```
#### Step 2:
Download the test_dataset from this [Google Drive Link](https://drive.google.com/file/d/1aC6PQzE8Dnf_BkYYerLG06IVj2rqpReq/view?usp=sharing) and extract it on root directory.
#### Step 3:
Create a .env file with variable <br>
GOOGLE_API='Your gemini api key'
#### Step 4:
You're done!


### NOTES (Don't run these commands below):
```
python -m venv .venv
.venv\Scripts\activate
pip install Pillow pandas google-generativeai python-dotenv tqdm
pip install scikit-learn
pip freeze > requirements.txt
```