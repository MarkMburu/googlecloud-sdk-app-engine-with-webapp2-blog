# Blog

This Blog is a simple multi-user blog web application where users can sign in and post blog posts as well as like and comment on other posts made by other users.

### Prerequisites:
The application was built on [Google App Engine platform](https://cloud.google.com/appengine/docs/standard/python/download) using [Python 2.7](https://www.python.org/downloads/).
It uses [Google Cloud Datastore](https://cloud.google.com/appengine/docs/standard/python/datastore/) as the underlying database technology.

### Features:
 - Login/Signup.
 - CRUD Post operations.
 - CRUD Comment operations.
 - Like\Dislike to other posts.
 - Elegant UI.

### Usage:
1. Clone this repository to your desktop, go to the ```myblog``` directory and run:
```python
dev_appserver.py app.yaml
```
**Note:** Ensure the you have both Python 2.7 and GAE SDK installed.

2. Go to [localhost:8080](http://localhost:8080) to see the application running and [localhost:8000](http://localhost:8000) for the admin console.


