# Output

* [Image](#image)
* [GPIO](#gpio)
* [TCP/IP client](#tcp-ip-client)
* [Webhook](#webhook)

If the heuristic determined that the evaluation was valid, one or more IO operations can be executed. You configure which IO operations that will be executed, by modifying the configuration file or using the web interface.

<a name="image"></a>
## Image
This will save an image to disk. The directory where the images will be saved to, can be set in the configuration file or by using the webinterface.

<a name="gpio"></a>
## GPIO
You can trigger a specific GPIO pin on the Raspberry Pi.

<a name="tcp-ip-client"></a>
## TCP/IP client
The TCP/IP client will send a TCP packet to a server. 

<a name="webhook"></a>
## Webhook
Detailed information (a JSON object) is send as a POST request to a webhook. The JSON object contains the number of changes, the region, the URL of the image, etc. 