# Members Only!

Members Only! is an exclusive clubhouse app where members can create and read anonymous posts. While anyone can read the posts, only signed-in members can see the author's name. Non-members will see the posts but will have to wonder who wrote them.

This application implements user authentication and restricts access to certain actions (like creating posts and viewing the author's identity) based on the user's authentication status.

## Features

* Authentication: Users must sign in to create new posts or see the author's name.

* Post Creation: Signed-in members can create new posts with a title and content.

### Access Control:

* Only signed-in users can see the author of each post.

* Only signed-in users can create new posts.

* Non-signed-in users can only view the content of posts but not the author’s name.

### Posts Display:

* All posts are visible to everyone, but only signed-in users can see the author.

* Non-signed-in users can only see the post content.
