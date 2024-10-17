# Instagram-Stateless
Lets talk about Instagram Authorization Authentication and Private and Public Api and Its stateless API first Let us know what these things are:

<h2>Stateless Api </h2>
These are the Api which does not store any kind of the data of the user . It doesn,t know who send him request etc he didn't store anything .He just when get request give response and then cut his all types of connection and then when we want thta again we will call them again.

<h2>Authentication </h2>
Authentication means that are are eligble to enter to the page or not like you are logging in in any social media the process he is checking your password is called Authentication.Thats mean you are a authentic person so you logged in.

<h2>Authorization</h2>
Authorization means that you have the authority to do this work or not .Like a user can delete or change his post but cannot change or delete the post of his friend because he doesnot have that authority to do that work so this is called authorization like you are authorize to do that work.

<h2>Public API</h2>
Public Api  are that which you can see and view data with out authorization and authentication .

<h2>Private API</h2>
You can see the public API but in Private API you are bound to login first to use that function.

<h4>Now lets starts about Instagram where these all are used according to the concepts i tell you.</h4>

<h2>Login</h2>
Login involves authorization its checks that the user and passwordyou send are right it send the data to a end point where the BE access that data and send it to DB and then match that data if its match then give access to next page . Then that BE API will give you a token which will in future tells that you are authentic or not and then break connection.

<h2>After Login</h2>
After login the token which you recieved is again send to the Api because you want your data in your feed now it will check and decide you are authorize to do this work this is called authorization like some accounts are business private every accout has its own limit.

<h2>Actions on Instagram</h2>
Actions like post like comment etc are done by stateless Api also it send it token and then the action is performed.

<h2>Public Key</h2>
Like you are searching some one account on goggle and you can see his profile if he is not private this is called Public Api like Public can see your data etc.

<h2>Private  Key</h2>
Like now you want to do comment on his post but now he will ask that login first now that is private Api that you can do that work after login.

<h2>Content Feed</h2>
Now Instagram will you contant according your area trending things which are also store in some DB but the api will get that data according to your area.