# Create, deploy and embed your bot
## Echo Bot 

Echo Bot is a simple chatbot that returns back everything the user entered in the chat.  
## Creation
You need to install Visual Studio extension **Bot Framework** if not already:    
<img src="https://github.com/Dacili/EchoBotLatest/assets/37112852/ee84e938-f952-443f-a677-3691c878f3e6" width="800">

Create new project in Visual studio, and select Echo Bot project.   

<img src="https://github.com/Dacili/EchoBotLatest/assets/37112852/1349c0d7-8b24-4d3f-8201-5a13564f7269" width="700">

After you got template, you can customize it as you wish.  
In order to test Bot locally you need to install **Bot Framework Emulator**  
![image](https://github.com/Dacili/EchoBotLatest/assets/37112852/06fb1286-6c12-44c6-8dc4-a9ac8018d909)  
Testing locally:  

https://github.com/Dacili/EchoBotLatest/assets/37112852/4febd794-2886-4307-a92d-796fc700fc97


## Deployment to Azure
### Required services
Services on Azure that you're gonna need are:  

<img src="https://github.com/Dacili/EchoBotLatest/assets/37112852/24b85c93-8030-481b-95c5-fa7ab5c869a8" width="600">      
<br/><br/>
1. App Service - for hosting the code of your chatbot (web app type). I chose the free one.   <br/>
2. Azure Bot -
   When setting up the pricing, choose Free tier.   
   
   ![image](https://github.com/Dacili/EchoBotLatest/assets/37112852/c268f207-004b-49fd-8039-de937f8dcfce)
   <br/>  

3. App Service plan - is linked to app service (you can create it while creating app service), it depends on location, zone, features, cost...   
   Note: If you need this for some real use cases, probably you will have to upgrade from free services to pay-on-demand.   

### Deploy bot code to App Service

### Connect App Service with Azure Bot
### Test bot in Web chat (Azure)
## Embedding into Web app

