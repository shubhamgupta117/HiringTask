# HiringTask
# HiringTask1
Design a nodejs server or any other server technology your are comfortable with & client react/other framework application to interact with your youtube channel: (By default, everyone has a channel on youtube using google login) 


### Application Specs: 
1. It should allow updating/modifying an existing video on youtube channel. Fields such as title, description and video privacy settings can be updated. Video to update should be identified using youtube video unique id. (https://developers.google.com/youtube/v3/docs/videos#properties)

(optional but would earn you extra points)
2. It should allow uploading a video to youtube channel (https://developers.google.com/youtube/v3/docs/videos/insert). Please keep fields such as title, description, video privacy settings(private, public, unlisted - https://support.google.com/youtube/answer/157177?co=GENIE.Platform%3DDesktop&hl=en) & video 


### Technical requirements: 
* React/other frontend framework client side code must not access youtube apis directly. It should only access nodejs/other server framework application apis which can access youtube apis. This is required for security purposes as you want prevent the misuse of youtube credentials by hackers.
* Any user of the system should ideally be able to change the credentials of the YouTube API by using a config file. 

### API Spec: 
* API's between React/other framework Client and Node/other server is appericiated to be GraphQL. Rest will also do. 
* API's between Node/other server and YouTube data API can use REST. 
 
### Useful Link: 
* https://developers.google.com/youtube/v3/quickstart/nodejs
* https://www.howtographql.com/
* https://graphql.org/learn/

### Assessment criteria:
* For code: our primary focus will be code readability and architecture, the code should be clean and organized. i.e make seperate module for oauth, video upload and edit(if attempting), keep server and client module seperate.
* once done with the project , make a private git repo with a proper readme and a video demo of the working project and send access to this account. video on drive with shared link would do.
* we hihgly encourage writing test cases, though aren't mandatory for this hiring task but would definitely earn the candidate extra points.

