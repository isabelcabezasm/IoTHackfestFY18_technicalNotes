# Connect MXChip and Remote Monitoring V2

Clone the example repository: https://github.com/jmservera/devkit-sdk/tree/master/AZ3166/src/libraries/AzureIoT/examples/RemoteMonitoringv2  

Browser to >devkit-sdk\AZ3166\src\libraries\AzureIoT\examples\RemoteMonitoringv2 
and open RemoteMonitoring.ino 

![look the RemoteMonitoring.ino](images/01_ino.png)


### Ctrl+P  <  task cloud-provision

Choose the IoT Hub of your Remote Monitoring V2 installed in your subscription.

![choose the IoT of your Remote Monitoring ](images/02_chooseIoTHub.png)

### Ctrl+P  <  task device-upload
(when the terminal ask it, press&hold buttonA, reset, release buttonA)


![uploading ](images/02_device_upload.png)

Continuing.... and Success!!

![success upload ](images/02_device_upload_success.png)

Now you can see a new device in the list:

![new device ](images/03_new_device.png)

And NOW we are sending data to the cloud!!

![sending data to the cloud ](images/03_sending_data.png)



If you browse to your Remote Monitoring portal, now you can see the device in the map (the coordinates in the repo are from Madrid)

![see my sensor in the RM portal](images/04_remote_monitoring.png)



