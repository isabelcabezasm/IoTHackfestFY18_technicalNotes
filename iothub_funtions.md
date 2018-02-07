# IoT Hub -> Azure Functions

## Scenario or premise
I have an **IoT Hub** and I want to connect it with an **Azure Function**

![This is my IoT Hub](images/01_iothub.png)

*Note: a good practice for facilitate the correct scalation -> Create a new  and its own consumer group*

![Change de consumer group](images/01_consumergroup.png)


Here, copy the connection string (because you will use it later)
![Change de consumer group](images/02_connectionstring.png)


1. Let's **create a Azure function App:**

![Steps for creating an azure function](images/02_createAzureFunction.png)


Write a name, use a existing Resource Group or a create a new one… And create a new storage:
![Steps for creating an azure function](images/02_createAzureFunction2.png)


Click in "+" icon (blue):
![Steps for creating an azure function](images/02_createAzureFunction3.png)


Click in the link "Custom function":
![Steps for creating an azure functionp](images/02_createAzureFunction4.png)


Choose the IoT Hub  (Event Hub) as the service that delivers messages to the Azure Function, and select the language (C# in my case):
![Steps for creating an azure function](images/02_createAzureFunction5.png)


Write a name and create a NEW event hub connection:
![Steps for creating an azure function](images/02_createAzureFunction6.png)


Select the IoT Hub:
![Steps for creating an azure function](images/02_createAzureFunction7.png)




And when is already created… Click in "Application Settings":
![Add a new app setting](images/03_appsettings.png)


We are going to add a setting with the Connection String of the IoT Hub.
I named this seeting iothubc2d (IoT Hub Cloud to Device) but, of course, you can name it how you want:
![Add a new app setting](images/03_appsettings1.png)

