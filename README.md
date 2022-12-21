# Smart-Album-based-on-AWS
Project update here:
https://github.com/yizhoushen/ECE1779-Project/tree/main/A3

1. Introduction
Our product is a personal smart album that supports photo upload, storage, display, analysis, and recommendation. Our server tags each image uploaded by the users, and generate word cloud based on tags of user’s own photos. Users get recommendations of the most popular tags labelled by other users. They can also preview all the related public photos by selecting tags that they are interested in.

2. Use Description
To use our application, users need to sign up personal accounts with their emails. Users need to login their own account otherwise the access to our application’s web page will be denied. Users are free to upload photos from their local file systems to the server, but any photo containing inappropriate contents detected by the server will be rejected, and a reminder email will be sent to the user’s mailbox. Users may choose whether they want their uploaded photos to be public or not. Public photos may be recommend to other users, but non-public photos will remain private and cannot be retrieved by any other users. Users are able to see their uploaded photos using corresponding image keys. Each photo successfully uploaded by the users will be detected with several categories and labelled by our server. If users go to their profile page, they can generate a word cloud picture showing the categories of photos in their albums. Our application also provides public photo recommendations that are popular among other users. If the users are interested in the tags recommended by our server, they may click on the tag to see public photos that are categorized by the tags they selected. 
