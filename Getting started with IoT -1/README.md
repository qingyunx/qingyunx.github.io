Getting started with IoT - 1
=================

![](https://media.licdn.com/dms/image/C5112AQGJ64q5bETd2g/article-inline_image-shrink_1000_1488/0?e=2125267200&v=beta&t=JbnZ49wdquWHnWI5apbjc3XK_gn6DacMx4ipB_HQSQc)

## Setting up AWS IoT ##
Sign up for a new AWS IoT account by logging in with your existing Amazon account or creating a new one by visiting [https://aws.amazon.com/iot/]( https://aws.amazon.com/iot/)

Click to start the interactive tutorial after you log in.

![](images/image1.png)

Read through the first part of the tutorial that explains the different parts of the solution (Steps 1–6).  When you are done with that you will be prompted to create a thing:

![](images/image2.png)

Click on View Thing

![](images/image3.png)

Click on Connect a device:

![](images/image4.png)

Choose the NodeJS SDK and then click Generate certificate and policy

![](images/image5.png)

Click to download the public key, private key and the certificate to your local computer.  Place them in a directory where you can find them in a future step.  These certificates are what authenticate the IoT gateway and allow it to send data to the AWS IoT cloud.  They will be used later.

![](images/image6.png)

Leave this tab in your browser open and in another browser tab navigate back to the Intel® IoT Gateway Developer Hub.  You will need this information for AWS IoT to configure your gateway in the later steps.

![](images/image7.png)
