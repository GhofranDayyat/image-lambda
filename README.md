# image-lambda

## lambda Usage
- to Trigger the event by upload file eith type img then you can find the result of triggrt the event in ``monitor``==>``view console CloudWatch``==>``Log streams``==>``you can find last console``
## Deployment Issues 
- when compress onle index and package.json files I faced error ``becaues async not defind`` and cant start the code
- after I add node-moduled with last files I faced ``width not defind`` I think we shoul add the width & hight as Metadete in S3 bu I am tring to add it in a many ways but still not working