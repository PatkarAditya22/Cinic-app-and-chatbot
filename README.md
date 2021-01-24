# Hack NITP

### Link to the Project Video:   [https://youtu.be/mKuSS_M2EzI](https://youtu.be/mKuSS_M2EzI)

### Link to the Powerpoint presentation :   [Click here](https://docs.google.com/presentation/d/1jYOAtZrql_PuGEm9hZTvksJGGKlZAHqZaPcWHtREK4g/edit#slide=id.g78c90a5a0c_0_82)

### Link to hosted website(hosted on heroku):  [https://chatbot-clinicapp.herokuapp.com/](https://chatbot-clinicapp.herokuapp.com/)

### Link to the Google drive link:  [Click here](https://drive.google.com/drive/folders/1kBUredfaoz3tD9NYG2zi38_Qv0nV-5PV?usp=sharing)

### Instructions to run the application

Place .env file in root dir with the required URLs and API keys

```bash
cd chatbot-hackwithcw
npm install
node app.js
```




### Steps to setup the flask server:
1) Host the flask server on NGROK server.
2) This will enable us to use the machine learning model in the chatbox.
3) Install NGROK using the command  **npm i ngrok**.
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

###  Step to setup Dialogflow:
1)Go to Dialogflow website.<br>
2)Import the zip file **Boctor.zip**.<br>
3)Go to fullfillment and add the deployed website(heroku) url.<br>
4)Go to chatbot-hackwithcw\app.js line no 1103 and line no. 963 and add the ngrok link of flask Api.


![](https://lh4.googleusercontent.com/cihDo07aPETA372dEgG0kORnhHJEZGAQecMd80YhO6uzy08MpMHQ-XTEmqjByng=w1200-h630-p )
![](https://cdn.discordapp.com/attachments/799613539866116120/800416205243416626/unknown.png)
![](https://cdn.discordapp.com/attachments/799613A539866116120/800416205243416626/unknown.png)
![](https://cdn.discordapp.com/attachments/799613539866116120/800416516121296897/unknown.png)
![](https://cdn.discordapp.com/attachments/799613539866116120/800416958507253780/unknown.png)
![](https://cdn.discordapp.com/attachments/799613539866116120/800417405993615381/unknown.png)
![](https://cdn.discordapp.com/attachments/799613539866116120/800417819446607892/unknown.png)
![](https://cdn.discordapp.com/attachments/799613539866116120/800418858157735986/unknown.png)
![](https://cdn.discordapp.com/attachments/799613539866116120/800419294461689896/unknown.png)
![](https://cdn.discordapp.com/attachments/799613539866116120/800425328279158785/unknown.png)
![](https://cdn.discordapp.com/attachments/799613539866116120/800426536078802954/unknown.png)
![](https://cdn.discordapp.com/attachments/799613539866116120/800426536078802954/unknown.png)
![](https://cdn.discordapp.com/attachments/799613539866116120/800415913941401670/unknown.png)
