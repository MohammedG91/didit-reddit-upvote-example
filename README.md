I made it a lot harder than I needed too. I knew all I had to do was update the github app with the vercel link, however I did this and everytime I tried to login I kept getting an error. It took me most of the day to realise I had a double // in the url when I changed it which was throwing it off and causing the error! Something I should've done in 10 minutes took me hours. A lesson learned!

EDIT!!

logging in on my localhost stopped working, i realised i didn't need to change the callback url on github app but i could just add one! had i seen the add callbark url button in the first instance, it would've saved me hours! So both localhost url callback and vercel url callback added and both working.

Stretch Goals:

Users can vote an infinite number of times on the same post. We’d like to prevent this happening. It should be enforced at the Schema level with the UNIQUE constraint but it isn’t working. We’d like you to try and fix this, either by correcting the schema (preferable) or if not by implementing the restriction in the application code when the user tries to upvote.

Updated the schema, and implemented the unique constraint.
