Afternoon Challenge
Hackathon Prep
Students will get into groups for their hack-a-thon project and begin preparation for the next day.



Things learned if there are differences of opinion about how to implement , get it in writing.

<H1>E.G. scrpt to a hack-athon play:</h1>

<b>Team member1:</b>    I think we will create two models a Post model and a Comment model. Later uhh ... lets add an array to the Post model where we can put the associated Comments....

<b>I say:</b> Hmm if we are doing this why are we creating two models when we are just stuffing one model inside the other one?

<b>Team member:</b> Hmmm .......  <em>(question to fellow student and friend not team member)</em> are you implementing on your team?  

<b>Fellow student not on team:</b> No we are keeping things in two seperate models...

<b>Team memeber now acting as team lead:</b> ok we will do it that way...
....

<b>Team leader now self appointed:></b> Ok ... so now we are not pulling the data from the back end ... you will just be getting the Comments from ProxyState (all proxyState comments will be those only associated with the active Post.  Just do it this way. We will take care of it in the back-end)

much thought .....  much tense discussion .....

<b>lowly me currently being ostrasized from the group:</b> I am doing the post draw function which responds from a onclick from the page view of thumbnail posts so if there is to be a loding of poxyState from back end it would be my function that would call for that. How then are you doing this?! 

<b>Authoritative team Lead:</b>  Just do it this way we will be taking care of that in the back-end..

<b>My response:</b>  Who is calling for that since I am writing the function that responds to the onclick. It would have to come from my function!?

<b>Authoritative dictator Team lead:</b> just do it as I say I will talk to the TAs


Long pause in coding:
Long discussions with TAs....


<em>Afer long discussions I ask another follower of leader self appointed teaam leader/dictator:  How is it that proxyState has only the comments from Post when I have communicated nothing to the back-end to load up ProxyState with that data-fiter from mongoose?</em>

<b>Other team member leader follower:</b> Ohh it just gets put there when you add a comment from the comment service...... 

After many tense conversations I realize they never agreed to keep things seperate they are just throwing them toggether in proxyState because in this hack-a-thon they know that they only have one user and one post with many fake unimportant posts and one set of data duplicated across two models.  A Post model and a PostComments model. All other orphaned dissenfranchised posts have no comments!

<H4>Conclusion: If you can not trust team members to do what they say and they are keeping secrets from you in an authoritative manor..  DO NOT WORK WITH THEM!  Lesson learned. </h4>


Daily Journal
Read Servers with Node/Express > MongoDb Relationships and answer the following questions

# What is a virtual property? 

This question is not part of MongoDb Relationships as described above. It appears that virtuals are addressed later in "Virtuals in Mongoose" So for this Daily journal I think I will pass on the question until I can  read that section. I did a cntrl-F search of the above and the word virtual is not even in the document at all. If you expect high precision from me the student ... then you should also deliver the same. Sorry not trying to be mean.

# When might you use a virtual property?

Same as above but I believe this is a link between related data that is made clearer by by a virtual naming. Have not read yet. TBD

# How do you search by a virtual properties value?

No Idea please see above TBD.