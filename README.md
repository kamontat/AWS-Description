Translate from "https://www.expeditedssl.com/aws-in-plain-english"
          by   "Kamontat Chantrachirathumrong"
          
# Amazon Web Services (AWS)
จาก amazon ที่มี services ให้มากมาย แถมคำอธิบายมันการอย่างกับ essay คะแนนเต็มล้าน ยาวโคตรๆ และแทบไม่มีสาระอะไรเลย 55555

# Content
- [App](#app-services)
- [Web](#web-developer-services)
- [Mobile](#mobile-app-developer-services)
- [Code Deployment](#ops-and-code-deployment-services)
- [Enterprise](#enterprise--corporate-services)
- [Big Data](#big-data-services)
- [AWS Management](#aws-management-services)

## App Services

| ชื่อที่เป็นทางการ | ควรเรียกมันว่า | มีสำหรับ | เหมือน/คล้ายกับ |
|:------------:|--------|-----|:----:|
| [EC2](https://aws.amazon.com/ec2) | Amazon Virtual Servers | คอมพิวเตอร์ในจินตนาการ ที่ใช้ได้จริง | digitalocean linode rackspace |
| [IAM](https://aws.amazon.com/iam) | Users, Keys and Certs  | จักการ เพิ่ม, ลบ ผู้ใช้งานต่างๆ ตั้งค่า AWS Keys และนโยบายต่างๆ | - |
| [S3](https://aws.amazon.com/s3) | Amazon Unlimited FTP Server | เก็บข้อมูลต่างๆ หรือ แชร์และแบ๊คอัพข้อมูล หรือ สร้าง static website | - |
| [VPC](https://aws.amazon.com/vpc) | Virtual Private Cloud |ตัวจัดการทุกอย่างเกี่ยวกับ network (hardware of network) | VLANs |
| [Lambda](https://aws.amazon.com/lambda) | AWS App Scripts |ตัวไว้รัน script เล็กๆ ในภาษา js, java หรือไม่ก็ python เพื่อจะจัดการหรือ ตั้งค่า AWS | - |

## Web Developer Services

| ชื่อที่เป็นทางการ | ควรเรียกมันว่า | มีสำหรับ | เหมือน/คล้ายกับ |
|:------------:|--------|-----|:----:|
| [API Gateway](https://aws.amazon.com/api-gateway) | API Proxy | test api สำหรับแอพ และ proxy แอพด้วย | 3Scale |
| [RDS](https://aws.amazon.com/rds) | Amazon SQL | ฐานข้อมูลแบบ sql เช่น Mysql, Postgres, and Oracle database | Heroku Postgres |
| [Route53](https://aws.amazon.com/route53) | Amazon DNS + Domains | สร้าง ซื้อ และจดทะเบียน รวมถึง ตั้งค่าต่างๆ เกี่ยวกับ DNS ของ domain ด้วย | DNSimple, GoDaddy, Gandi |
| [SES](https://aws.amazon.com/ses) | Amazon Transactional Email | อีเมลแบบ no-response นั้นเอง เช่น เมลที่ไว้ส่ง รหัสผ่านใหม่ หรือ การแจ้งเตือนต่างๆ | SendGrid, Mandrill, Postmark |
| [Cloudfront](https://aws.amazon.com/cloudfront) | Amazon CDN | ทำให้เว็บโหลดเร็วขึ้นได้ โดยแยกไฟล์ต่างๆ ให้ไปอยู่ที่ server ใกล้ๆ ตัวของคุณ | MaxCDN, Akamai |
| [CloudSearch](https://aws.amazon.com/cloudsearch) | Amazon Fulltext Search | นำข้อมูลจาก S3 หรือจาก database (RDS) แล้ว search ข้อมูลด้วยคำต่างๆ | Sphinx, Solr, ElasticSearch |
| [DynamoDB](https://aws.amazon.com/dynamodb) | Amazon NoSQL | ฐานข้อมูลแบบ No-Sql | MongoLab |
| [Elasticache](https://aws.amazon.com/elasticache) | Amazon Memcached | เก็บข้อมูลแบบกึ่งโครงสร้าง ([เพิ่มเติม](https://www.google.com/search?rls=en&q=Memcached+or+Redis.+8nv&ie=UTF-8&oe=UTF-8#q=Memcached+or+Redis+%E0%B8%84%E0%B8%B7%E0%B8%AD)) คือมอง ram ให้เป็น database และ เร็วมาก | Redis to Go, Memcachier |
| [Elastic Transcoder](https://aws.amazon.com/elastictranscoder) | Amazon Beginning Cut Pro | ทำเกี่ยวกับ video ต่างๆ เช่น เปลื่ยนนามสกุล | - |
| [SQS](https://aws.amazon.com/sqs) | Amazon Queue | คอนเซปคือ เก็บข้อมูลเพื่อจะได้ใช้นอนาคต โดยที่ตัวมันไม่มี email sms และ logic อะไรเลย | RabbitMQ, Sidekiq |
| [WAF](https://aws.amazon.com/waf) | AWS Firewall | ป้องกัน การเรียก (request) ที่ไม่ดี หรือ บ่อยเกินไป | Sophos, Kapersky |

## Mobile App Developer Services

| ชื่อที่เป็นทางการ | ควรเรียกมันว่า | มีสำหรับ | เหมือน/คล้ายกับ |
|:------------:|--------|-----|:----:|
| [Cognito](https://aws.amazon.com/cognito) | Amazon OAuth as a Service | สร้างการ login ได้ง่ายขึ้น ผ่าน google, facebook, ... | OAuth.io |
| [Device Farm](https://aws.amazon.com/device-farm) | Amazon Drawer of Old Android Devices | สร้าง เครื่องแบบจำลอง (Android & iOS) ขึ้นมาเพื่อทดสอบ แอพต่างๆ ในสภาพแวดล้ามต่างๆกัน | MobileTest, iOS emulator |
| [Mobile Analytics](https://aws.amazon.com/mobileanalytics) | - | ตรวจสอบวาผู้ใช้เนี้ย ทำอะไรกับแอพเราบ้าง | Flurry |
| [SNS](https://aws.amazon.com/sns) | Amazon Messenger | ส่งการแจ้งเตือนในโทรศัพท์ อีเมล และ ยังสามารถ ส่ง SMS ได้ด้วย | UrbanAirship, Twilio |

## Ops and Code Deployment Services

| ชื่อที่เป็นทางการ | ควรเรียกมันว่า | มีสำหรับ | เหมือน/คล้ายกับ |
|:------------:|--------|-----|:----:|
| [CodeCommit](https://aws.amazon.com/codecommit) | Amazon GitHub | version control (git) นั้นเอง | Github, BitBucket |
| [Code Deploy](https://aws.amazon.com/codedeploy) | - | เป็นตัวช่วยในการส่งแอพไปใช้งานจริง (deploy) จาก CodeCommit (or Github) ไปยัง EC2 | Heroku, Capistrano |
| [CodePipeline](https://aws.amazon.com/codepipeline) | Amazon Continuous Integration | ตัวเทสอัตโนมัตินั้นเอง แล้วก็จะมีรายงานบอกว่าผลเป็นยังไง | CircleCI, Travis |
| [EC2 Container Service](https://aws.amazon.com/ecs) | Amazon Docker | สามารถใช่ Dockerfile ไปยัง EC2 เพื่อจะรันเว็บได้ | - |
| [Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) | Amazon Platform | ย้ายแอพจากที่หนึ่ง ไปยังอีกที่ (เมื่อราคามันเริ่มแพงขึ้น) | Heroku, BlueMix, Modulus |

## Enterprise / Corporate Services

| ชื่อที่เป็นทางการ | ควรเรียกมันว่า | มีสำหรับ | เหมือน/คล้ายกับ |
|:------------:|--------|-----|:----:|
| [AppStream](https://aws.amazon.com/appstream/) | Amazon Citrix | สร้าง Window ขึ้นมา แล้วก็เอา application ต่างๆ ไปใส่แล้วก็เปิดให้คนอื่นมารีโมตได้ | Citrix, RDP |
| [Direct Connect](https://aws.amazon.com/directconnect/) | - | เชื่อมต่อข้อมูลแบบส่วนตัวกับ AWS และ อินเตอร์เน็ตในบริษัท | - |
| [Directory Service](https://aws.amazon.com/directoryservice/) | - | รวมแอพทั้งหมดที่จะต้องให้ Microsoft Active Directory ([เพิ่มเติม](https://www.google.com/search?client=safari&rls=en&q=Microsoft+Active+Directory+%E0%B8%84%E0%B8%B7%E0%B8%AD&ie=UTF-8&oe=UTF-8)) เข้าด้วยกัน แล้วควบคุมมันจากที่เดียว  | - |
| [WorkDocs](https://aws.amazon.com/workdocs/) | Amazon Unstructured Files | แชร์รายงานหรือเนื้อหาต่างๆ ให้ผู้ร่วมงาน | Dropbox, DataAnywhere |
| [WorkMail](https://aws.amazon.com/workmail/) | Amazon Company Email | ให้ทุกคนในบริษัท ที่ระบบอีเมลและปฎิทินเดียวกัน | - |
| [Workspaces](https://aws.amazon.com/workspaces/) | Amazon Remote Computer | ให้ Window พื้นฐานมาแล้วเราก็สามารถรีโมตมาควบคุมได้ | - |
| [Service Catalog](https://aws.amazon.com/servicecatalog) | Amazon Setup Already | ให้คนในบริษัทมาใช้งานสิ่งที่คุณได้สร้างเอาไว้ โดยที่พวกเขาไม่จำเป็นต้องมาอ่านอะไรแบบนี้ | - |
| [Storage Gateway](https://aws.amazon.com/storagegateway/) | - | การจัดเก็บแบบไฮบริดที่ไร้รอยต่อกับท้องถิ่น (local) และการเพิ่มประสิทธิภาพการถ่ายโอนข้อมูล | - |

## Big Data Services

| ชื่อที่เป็นทางการ | ควรเรียกมันว่า | มีสำหรับ | เหมือน/คล้ายกับ |
|:------------:|--------|-----|:----:|
| [Data Pipeline](https://aws.amazon.com/datapipeline/) | Amazon ETL | เปลื่ยนแปลง ย้าย และโหลดข้อมูลต่างๆจาก AWS, ตั้งเวลาและสามารถเตือนเมื่อผิดพลาดได้ | - |
| [EMR](https://aws.amazon.com/emr/) | Amazon Hadooper | อ่านข้อมูล (Iterate) ที่ขนาดใหญ่มากๆ ใน S3 | Treasure Data |
| [Glacier](https://aws.amazon.com/glacier/) | Slow Amazon S3 | ที่เก็บข้อมูลขนาดใหญ่ กว่า S3 (ระวังเรื่องราคานิดหนึ่ง) | - |
| [Kinesis](https://aws.amazon.com/kinesis/) | Amazon High Throughput | การรับข้อมูลความเร็วสูง เพื่อเอาไปจัดการต่อเช่น จะวิเคราะห์ข้อมูลคนที่แชร์เรื่อง...ใน facebook | - |
| [RedShift](https://aws.amazon.com/redshift/) | Amazon Data Warehouse | ที่เก็บข้อมูลสังเคราะห์, สามารถทำกระประมวล และ นำมันออกมาได้ | - |
| [Machine Learning](https://aws.amazon.com/machine-learning/) | Skynet | คาดเดาพฤติกรรมจากข้อมูลที่มีอยู่แล้ว | - |
| [SWF](https://aws.amazon.com/swf/) | Amazon EC2 Queue | จัดการสภาพ (state) และ งาน (task) ต่างๆ ใน cloud | IronWorker |
| [Snowball](https://aws.amazon.com/snowball/) | AWS Big Old Portable Storage | สามารถเพิ่ม harddrives ในอินเตอร์เน็ต เพื่อเพ่ิมจำนวนข้อมูลที่จะถูกส่งไป-มาจาก AWS | Shipping a Network Attached Storage device to AWS |

## AWS Management Services

| ชื่อที่เป็นทางการ | ควรเรียกมันว่า | มีสำหรับ | เหมือน/คล้ายกับ |
|:------------:|--------|-----|:----:|
| [CloudFormation](https://aws.amazon.com/cloudformation/) | Amazon Services Setup | ตั้งค่าสิ่งที่เชื่อมต่อกับการบริการของ AWS  | - |
| [CloudTrail](https://aws.amazon.com/cloudtrail/) | Amazon Logging | log ข้อมูลเกี่ยวกับใคร กำลังทำอะไรกับ AWS  | - |
| [CloudWatch](https://aws.amazon.com/cloudwatch/) | Amazon Status Pager | ตัวแจ้งเตือนเวลามีปัญหาอะไรเกี่ยวกับการบริการของ AWS (เช่น ระบบล่ม)  | PagerDuty, Statuspage |
| [Config](https://aws.amazon.com/config/) | Amazon Configuration Management | ควบคุมและตรวจสอบการตั้งค่าตางๆ เวลาที่ AWS มันใหญ่มากๆ | - |
| [OpsWorks](https://aws.amazon.com/opsworks/) | Amazon Chef | ดูแลการรันโปรแกรมของคุณเช่น auto-scaling (การขยายระบบอัตโนมัติ) | - |
| [Trusted Advisor](https://aws.amazon.com/premiumsupport/trustedadvisor/) | Amazon Pennypincher | เช็คหรือหา ว่าเราจ่ายกับอะไรมากเกินไป (EC2 ที่ไม่ได้ใช้แล้ว เป็นต้น) | - |
| [Inspector](https://aws.amazon.com/inspector/) | Amazon Auditor | เช็ดการตั้งค่าางๆ ว่ามันปลอดภัยมากพอหรือยัง | Alert Logic |
