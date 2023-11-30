# AWS IoT Sample Code with Node.js and Javascript

This repository contains a single Javascript file that will connect to AWS IoT core using the MQTTS open protocol using certificates.

## Pre-requisites
* npm (v9.8.1+)
* Node.js (v18.17.0+)
* [AWS Account](https://portal.aws.amazon.com/gp/aws/developer/registration/index.html?nc2=h_ct&src=header_signup)

## Getting Started
1. [Create an AWS IoT Core instance](https://docs.aws.amazon.com/iot/latest/developerguide/iot-gs.html#aws-iot-get-started)
2. [Retrieve certificates for connection](https://docs.aws.amazon.com/iot/latest/developerguide/device-certs-create.html) and put them into this folder
3. Inside `index.js` replace line 5 to 8 with your own values
4. Run `node index.js` to start publishing sample data!