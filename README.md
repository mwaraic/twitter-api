# Twitter API


## **Run commands:**

docker compose build <br/>
docker compose up<br/>

## **Test:** <br/>
docker compose exec python bash<br/>
python manage.py test<br/>


## **URL:**<br/>
127.0.0.1:8000 <br/>

## **APIs:**

### **User Login and Registration**<br/>
Send a **POST** request on account/login to login<br/>
Send a **POST** request on account/signup to register<br/>

### **Message**<br/>
Send a **GET** request on messages/<:userID> to retrieve a list
of messages <br/>
Send a **POST** request on messages/<:userID> with message property
to send a message<br/>

### **Tweet**<br/>
Send **GET** request on mytweets/ to 
retrieve the list of tweets for the user <br/>
Send a **POST** request with body property on mytweets/ to 
create a tweet <br/>
Send a **PUT** request on mytweets/<:tweetID> with
updated tweet data to update the tweet <br/>
Send a **DELETE** request on mytweets/<:tweetID> to
delete a tweet<br/>

### **Retweet**<br/>
Send a **POST** request on retweet/<:tweetID>
to retweet a tweet<br/>

### **Like/Unlike**<br/>
Send a **GET** request on likes/
to retrieve list of tweets a user likes <br/>
Send a **POST** request on likes/<:tweetID>
to like a tweet <br/>
Send a **DELETE** request on likes/<:tweetID>
to unlike a tweet<br/>

### **Thread**<br/>
Send a **POST** request on thread/ to create
a new thread.<br/>
Send a **GET** request on thread/ to retrieve the 
list of threads.<br/>

### **ThreadTweet**<br/>
 Send a **POST** request on thread/<:threadID> with 
 body property to create a new tweet on a thread.<br/>
 Send a **GET** request on thread/<:threadID> to
 retrieve the list of tweets on a thread.<br/>

### <ins> **Additional:**</ins><br/>

### **Friends**<br/>
Send a **POST** request with UserID value against handle2 property
to add a friend on friends/ <br/>
Send a **DELETE** request on friends/<:userID>
to remove a friend<br/>

### **Profile**<br/>
Send a **GET** request on profile/<:userID>
to get the tweet timeline of user.

### **Home**<br/>
Send a **GET** request on home/
to get the list of tweets of user and his friends<br/>






    
