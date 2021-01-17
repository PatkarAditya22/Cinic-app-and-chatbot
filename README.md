# chatbot-hackwithcw

## Instructions to run the application

Place .env file in root dir with the required URLs and API keys

```bash
cd chatbot-hackwithcw
npm install
node app.js
```

### Link to the Project Video:   [https://youtu.be/mKuSS_M2EzI](https://youtu.be/mKuSS_M2EzI)

### Link to the Powerpoint presentation :

### Link to hosted website(hosted on heroku):  [https://chatbot-clinicapp.herokuapp.com/](https://chatbot-clinicapp.herokuapp.com/)


### Steps to setup the flask server:
1) Host the flask server on NGROK server.
2) This will enable us to use the machine learning model in the chatbox.
3) Install NGROK using the command  **npm i ngrok** <br>.
4) To run the flask server ,go to the root directory of flask folder and run the command **ngrok http 5000**.
 
```bash

npm i ngrok
ngrok http 5000
virtualenv myenv
cd myenv
Scripts\activate
cd ..
cd chatbot-hackwithcw
cd FlaskApi
pip install -r requirements.txt
python predict.py
```

###  
