# bridge_workshop_ms_iothub_cloud
Bridge workshop connecting MS Azure IoTHub with mbed Cloud

Updates:

    10/3/2017: Initial checking with v2.2 workshop release content

Links for the workshop

- Azure Portal: 
      https://www.azure.com 

- Windows USB Driver for mbed:
     https://os.mbed.com/media/downloads/drivers/mbedWinSerial_16466.exe

- Windows Putty Serial Terminal: 
      http://www.putty.org/ 

- Docker Toolbox for Windows 7: 
      https://github.com/docker/toolbox/releases/tag/v1.12.2

- MS DeviceExplorer for Windows 7: 
      https://github.com/Azure/azure-iot-sdks/blob/master/tools/DeviceExplorer/doc/how_to_use_device_explorer.md 
      
- mbed Developer IDE:
      https://os.mbed.com
      
- mbed Cloud Portal Dashboard:
      https://portal.mbedcloud.com
      
- K64F Sample Project used in Workshop:
      https://github.com/ARMmbed/mbed-sample-cloud/
      
- Bridge Configuration Panel (local)
      https://192.168.99.100:8234 
      
"Git" command used to import the bridge container installer:

      git clone https://github.com/ARMmbed/connector-bridge-container-installer

JSON sample used as command to send to device:

      {"path":"/311/0/5850", "ep":"ENDPOINT_NAME_GOES_HERE", "new_value":"0","coap_verb":"put"}