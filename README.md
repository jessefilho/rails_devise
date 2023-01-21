# Re-do Tutorial about Devise 7 publish at DigitalOcean
The initial publish may be found here:
https://www.digitalocean.com/community/tutorials/how-to-set-up-user-authentication-with-devise-in-a-rails-7-application

I am not suggest to you to do the ocean tutorial in develop or production mode.
Try a new project first, and take your own conclusion.

### What I did?

- Step 1 — Creating a New Rails Application

    You can follow. It works fine.
- Step 2 — Creating a Landing Page

    Don't do like their tutorial, because it is not in the best practice of rails.
    Create a controller using `$ rails g controller Home` or `$ rails generate scaffold Home`
    See the difference here https://guides.rubyonrails.org/v3.2/getting_started.html
    - So, I did `$ rails g controller Home`. Then you can create the index.html.erb file
    - And set `root "home#index"`
    If chose scaffold you may use `root "homes#index"`

- Step 3 — Installing and Configuring Devise
    
    It works fine, here it is only devise installation.
- Step 4 — Creating the User Model with Devise

    Late, make sure that you have a clean migration using
    `$ rails db:drop db:create db:migrate`
    use SQLite for seek of simplicity
- Step 5 — Linking Authentication to the Landing Page

    Don't explore anything until the end.
    If you did the sign in, don't touch, because you we get lost
    in the follow instructions.
    
    After copy, the buttons, refresh your page then sign out the session
    
    if you click on sign in button you will see that devise
    did not the linking between pages.

 
# Such tutorial does not works on DigitalOcean, And was created only to Generate traffic with how to install devise on Rails 7
