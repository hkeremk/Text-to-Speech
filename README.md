# Text-to-Speech Application on AWS

- This solution converts text into audio files by using Amazon Polly, an aws service that converts text into lifelike speech. 

- A user uploads a text file into the input folder of an Amazon Simple Storage Service (Amazon S3) bucket.

- The S3 bucket can be configured with S3 event notificaitons that invoke an AWS Lambda function whenever a text file is uploaded.

- The lambda function calls the Amazon Polly API to synthesize the provided text into a high-quality speech audio stream.

![Text-to-Speech](assets/Text-to-Speech.png)













