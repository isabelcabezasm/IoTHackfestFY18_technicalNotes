# Connect MXChip with IoT Hub

Let's install an application example and learn how to connect to Azure IoT Hub <br /> (https://microsoft.github.io/azure-iot-developer-kit/docs/projects/connect-iot-hub/)

Open Get Started project: 

![Open Get Started project](images/01_MXChipGetStarted.png)



## 1. Ctrl + P     <-  Task cloud-provision

		
Provisioning the required Azure services:

![Executing task](images/02_MXChip_cloudProvision.png)


Login on the device:

![Login on the device](images/03_login.png)



Successfully login:

![Successfully login on the device](images/03_login2.png)


Select a subscription:

![Select a subscription](images/04_selectSubscription.png)


![Subscription selected](images/05_subscriptionselected.png)



Select the IoT Hub (remember!! copy your OWN connection string!!)

![IoT Hub connection string](images/06_iothub_connstring.png)



## 2. Ctrl + P <- task device-upload	
(the terminal ask you enter en configuration mode with button A + reset)


![device-upload task](images/07_task_device_upload1.png)
![device-upload task process](images/07_task_device_upload2.png)
![device-upload task process successfully](images/07_task_device_upload3.png)

### TEST
A icon with the "COM" appears in Visual Studio Code.
Select the port:

![look this information](images/08_Port.png)

click in the "plug" icon.
choose 115200:

![click in this icon](images/08_plug.png)

Look the terminal. The result should be "IOTHUB_CLIENT_CONFIRMATION_OK

![terminal picture](images/08_terminal.png)


Now let's See your sent data.
(Install if you don't have it yet this extension: Azure IoT Toolkit) 
Open Azure IoT Toolkit (VS Extension)

![select this extension called Open Azure IoT Toolkit](images/08_extension)


Start  Monitoring  D2C message -> 

![data we are sending to the cloud from the device](images/08_data.png)



### Other interesting links (offical documentation)


To continue getting started with Azure IoT Hub and to explore other IoT scenarios, see:
	• [Manage cloud device messaging with iothub-explorer](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-explorer-cloud-device-messaging)
    
	• [Save IoT Hub messages to Azure data storage](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-store-data-in-azure-table-storage)

	• [Use Power BI to visualize real-time sensor data from Azure IoT Hub](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-live-data-visualization-in-power-bi)

    
	• [Use Web Apps to visualize real-time sensor data from Azure IoT Hub](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-live-data-visualization-in-web-apps)

	• [Weather forecast using the sensor data from your IoT hub in Azure Machine Learning](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-weather-forecast-machine-learning)

	• [Device management with iothub-explorer](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-device-management-iothub-explorer)

	• [Remote monitoring and notifications with ​​Logic ​​Apps](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-monitoring-notifications-with-azure-logic-apps) 
