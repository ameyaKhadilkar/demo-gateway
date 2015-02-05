Demo Gateway Application
--------------------------------------
The Application is RESTful API Gateway communicating with Twitter.

The application uses twitter's Post , User Info, Tweet Search and Trending APIs.

*Post Api tweets to @AmeyaKhadilkar. ( https://twitter.com/AmeyaKhadilkar )

Features :
 - Blocking/Unblocking specific IP addresses.
 - Crude analytics , viz, Which is maximum used api, number of failed request etc.
 ( The figures returned are current session based )
 - oAuth
 - Caching.
 
To Dry Run :

- gradle build
- java -jar build/libs/demoGateway-0.0.1-SNAPSHOT

Things I learned :

- oAuth
- etags
- 

Things I plan to do :
- Throttling
- Cross session Analytics.
