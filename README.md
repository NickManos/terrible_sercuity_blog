# My New Blog!

I've got a lot to say, and now I have a place to say it!!!!!

Read all my amazing posts!!!!! You can load them into the app with: `rake load:blog`

Since I know you want to read them all, I designed my page to show EVERYTHING on the front page of the site!!!!!

I know it is a little slow (but totes worth it!!!!)... _Do you know how I can make it faster?_

# I'm feeling insecure...

Well, I got some requirements from marketing to make sure we distinguish between published and unpublished posts. I made some changes to the html and css.

But now QA is telling me I have some security vulnerabilities! They were able to use the strings below to hack my site!!!

What do I do to fix it???

Update
--------
Security holes have been fixed! Updating rails to the latest version really helped
with the cross site scripting and fixes in the post model and search form did the trick for the
SQL injection. Brakeman is reporting no errors and I have been unable to hack the site.
