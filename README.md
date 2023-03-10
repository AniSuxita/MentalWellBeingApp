Our application "Mental wellbeing" serves “healing” purposes. It helps the users post about their thoughts and make checklists about the things they want to do.
People who struggle with their mental health can use our app to relax and make plans to improve their mental health. 
Our app is very easy to use and it’s very accessible.
You enter the login fragment which gives you an opportunity to create a new account or reset your password if you’ve forgotten it, using firebase services.
You can create an account using your name, last name, username, email and password. 
Once you register, you’re redirected to the login fragment, where you enter the email and the password which you used to register in the first place. 
Then you’re directed the second activity, which offers you our main services. 
First fragment offers a posting feed, where you can post whatever you feel like, which can be therapeutic for some people.
These are the people, who’ll probably be interested in our app, who’ll post their thoughts.
As we already mentioned, the users will also be able to make lists(checklists) of the things they want to do, 
things they want to improve about themselves and once they complete the tasks given to themselves, they’ll have the satisfaction of checking the checkbox.
If the users don’t like the task they’ve made, or if they made a spelling error, we give them the option to delete for their comfort. 
The next fragment allows you to see your personal information: your username, name and last name.
We also offer our users the service of setting and changing their profile pictures, which will be remembered even after you exit the app.
Users can log out using the log out button and can also change their password with the service given on this fragment. 
The last fragment also displays the option to view the 24-hour hotline for psychological counselling services if you’re even in need. 
This is a short explanation of the uses of this app, how or why you should use it and we hope you’ll be interested.
We created this app to help people feel calm and comforted and we certainly hope that it helps.

Technical side:
Our app has two activities. When the app is opened, the user is able to see the  first activity, which displays LoginFragment. The user can navigate to other fragments (register,password reset) with the navigation component. After a successful log in, second activity is displayed on screen. The second activity uses tablayout and viewpager, so the user can easily go from one fragment to another by simply swiping or tapping icons on tablayout.  The second activity has three fragments. The first fragment is where users can write their posts. On the second fragment users can add their tasks. Both fragments use recycler view so posts and tasks are added as items. On the third activity, the user is able to change the profile photo. Profile photo is saved in FirebaseStorage and its name is saved on FirebaseRealtimeDatabase. Moreover, users can check the checkbox which then shows hotline numbers. The app uses sharedpreferances to remember if the checkbox is checked or not. This fragment also has a logout button which shows the user a dilog after being clicked.
