# Talend Job Example
- Talend, ETL Tool, was used for inhouse project.
- You can use this source to develop simple ETL Program. Also, you can build .bat or .sh file.




## Types of Jobs

- Truncate/Insert or Delete Insert
  <br> *e.g., job name: truncate_insert
<div>
  <img src = "https://user-images.githubusercontent.com/4458815/78332219-8abd7a00-75c2-11ea-84e1-3f01b64b87ca.png">
</div>

- Watching and file transfer
  <br> *e.g., job name: watching_fileinput_fileoutput
<div>
  <img src = "https://user-images.githubusercontent.com/4458815/79188325-b3166580-7e59-11ea-9fa1-a0724ce59951.png">
</div>

- Watching and transfer GCP
<br> *e.g., job name: watching_output_GCP
<div>
  <img src = "https://user-images.githubusercontent.com/4458815/79188382-d214f780-7e59-11ea-9074-8ba7371e6408.png">
</div>

- email notify in case of error happening.
<br> *e.g., job name: error_handling
<div>
  <img src = "https://user-images.githubusercontent.com/4458815/79188421-e953e500-7e59-11ea-82be-865fcdf2ff5f.png">
</div>

- move transferred file from source to backup folder.
<div> 
  <img src = "https://user-images.githubusercontent.com/4458815/79424386-070c8000-7ffb-11ea-814b-843f383b87e5.png">
</div>


## Settings
- Down Talend Open Studio for Data Integration
https://www.talend.com/download/thankyou/data-integration-windows/
- Import item from job design level.
- Configure DB Connection in Metadata. (Currently, Set Garbage data.)

## Requirements

 - Java Version : above 1.8 
 - JDBC Driver(Mysql, Postgresql) :
    squirrel-6.0.0.jar
    sqlexplorer-6.0.0.jar
    postgresql-42.2.11.jar
    mysql-connector-java-8.0.19.jar


## Etc (Reference)
- What is Talend.
https://medium.com/@top100itw/etl-talend-%EC%86%8C%EA%B0%9C-%EB%B0%8F-%EC%82%AC%EC%9A%A9%EA%B8%B0-d8ea38d424ba

- TroubleShooting for Talend
https://medium.com/@top100itw/etl-talend-%EC%98%A4%EB%A5%98-%ED%95%B4%EA%B2%B0-%EA%B8%B0%EB%A1%9D-5c02d51f3750




