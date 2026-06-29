Repository made to document the Software Process of the IoT based Temperature and Humidity monitoring process at Aspire Systems.
- mosquitto.conf - Contains the configuration to be used for the Eclipse Mosquitto message broker that handles the incoming messages from the IoT server and publishes them to the Ingestion Agent.
- telegraf.conf - Contains the configuration to be used for the Telegraf ingestion agent that collects the messages from the broker and appends them to the VictoriaMetrics Time-Series Database.
- IoT_Device_Program.txt - Contains the Embedded C++ code to be used to program the IoT devices to send the sensor data to the AWS Server
- Server and Software Configuration AWS EC2 Ubuntu - Contains documentation about the exact process to be followed to replicate the existing server structure and to enable streamlining.
