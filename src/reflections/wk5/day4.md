Afternoon Challenge
Hackathon Prep
Students will get into groups for their hack-a-thon project and begin preparation for the next day.



Things learned if there are differences of opinion about how to implement , get it in writing.

E.G. scrpt:

Team member1: I think we will create two models a Post model and a Comment model. Later uhh ... lets ad an array to the Post model where we can put the associated Comments....

I say: Hmm if we are doing this why are we creating two models when we are just stuffing one model inside the other one?

Team member: Hmmm ....... (question to fellow student and friend not team member) are you implementing on your team?  

Fellow student not on team: No we are keeping things in two seperate models...

Team memeber now acting as tema lead: ok we will do it that way...
....

Team leader nowself appointed: Ok so now we are not pulling the data from the back end ... you will just be getting the Comments from ProxyState (all proxyState comments will be those only associated with the active Post.  Just do it this way. We will take care of it in the back-end)

much thought .....  much discussion .....

lowly me currently being ostrasized from the group: I am doing the post draw function which responds from a onclick from the page view of thumbnail posts so if there is to be a loding of poxyState from back end it would be my function that would call for that. How then are you doing this?! 

Authoritative team Lead:  Just do it this way we will be taking care of that in the back-end..

My response: who is calling for that since I am writing the function that responds to the onclick. It would have to come from my function!?

Authoritative dictator Team lead: just do it as I say I will talk to the TAs


Long pause in coding:
Long discussions with TAs....

Afer long discussions I ask another follower of leader self appointed teaam leader/dictator:  How is it that proxyState has only the comments from Post when I have communicated nothing to the back-end to load up ProxyState with that datafIter from mongoose?

other team member leader follower: Ohh it just gets put there when you add a comment from the comment service. 

After many tense conversations I realize they never agreed to keep things seperate they are just throwing them toggether in proxyState because in this hack-a-thon they know that they only have one user and one post and one set of data duplicated across two models.  

Conclusion: If you can not trust team members to do what they say and they are keeping secrets from you in an authoritative manor..  DO NOT WORK WITH THEM!  Lesson learned. 


Daily Journal
Read Servers with Node/Express > MongoDb Relationships and answer the following questions

What is a virtual property?

When might you use a virtual property?

How do you search by a virtual properties value?