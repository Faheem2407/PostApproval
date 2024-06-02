This is Just a basic "Post Approval package" created by me using composer you can use it inside your laravel project to see the output.

what's inside ?
---------------
There is just two class PostApprove and PostRemove

How to use it ?
---------------
Just create a fresh laravel project : composer create-project laravel/laravel YourProjectName
---------
Then go YourProject folder : cd YourProjectName
---------
To use my package: composer require faheem2407/post-approval
---------
Then :
------
     1.create a route
     2.use Faheem2407\PostApproval\PostApprove;
     3.use Faheem2407\PostApproval\PostRemove;
     4.inside your closure just make an instance of these class : new PostApprove(); or new PostRemove();

It will show you the output like the following :

Output:
------
if you create an instance of PostApprove Class output will be:
Your post is approved by admin! you are ready to go...

if you create an instance of PostRemove Class output will be:
Your post is removed by admin! 

