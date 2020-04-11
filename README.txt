recommend:
    Use virtual environment 

to run requirements.txt 
type in shell: 
    pip install -r requirements.txt


You have to provide with client_secret.json
which u can make creating api on google account 
link:
    1) go to : https://console.developers.google.com/
    2) on left side you can see Credentials, click it 
    3) on upper nav-bar you can see '+ CREATE CREDENTIALS'
    4) choose OAuth client ID
    5) choose 'other', name it however you want
    6) click ok 
    7) you can see your credential and on right side of it u can see download button, thats your JSON file 
    8) download it in your project foleder 
    9) in main.py go to line 32 and put your client_secret.json file typing "client_secret_some_numbers.json"
    10) open shell in folder where is main.py and type : python main.py 
    11) In console you'll provided with link for authorization code 
    12) Its one time code, you have to generati it every time you want to use this script