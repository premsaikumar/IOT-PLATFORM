Developed a comprehensive platform aimed at simplifying the lives of IOT developers within our institute.

At our institute, we have a rich ecosystem of over 275 different sensors, including air quality, water flow, and energy monitoring. Our platform can act as a central hub, allowing users to run specific IoT applications tailored to their needs.

Analogy : In essence, our platform functions as a dynamic ecosystem, resembling a 'play store' for IoT applications, where sensor data meets user needs through a seamless and user-friendly experience

How to run?
install the requirements in requirements.txt pip3 install -r ./requirements.txt
go to in-cse file and run ./start.sh
for running the onem2m server (localhost:5089/webpage)
go to sensor_manager/onem2m_interface and run python3 onem2mapi.py python3 onem2mDatawarehouse.py to run our flask api (localhost:8069)
go to ./sensor_manager/sensor_query and run python3 query_server.py
go to ./ui/sensormanager_frontend and run npm install npm run dev to open the frontend (localhost:5173)
