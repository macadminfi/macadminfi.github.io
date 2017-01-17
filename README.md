## macadmin.fi

This repository contains the source code of macadmin.fi. Powered by Hugo.

### How to contribute
- install [Hugo](https://gohugo.io) (```autopkg run Hugo.install```)
  - we recommend checking the docs/tutorial
- clone this repository
- **Note** you must do all your work on the ```sources``` branch! (```git checkout sources```)
- to make a new post: ```hugo new post/my-new-post```
  - edit the post in your favorite editor, e.g. ```atom content/post/my-new-post```
- commit your changes and push them to the ```sources``` branch
  - [Travis CI](https://travis-ci.org) will magically take care of the deployment, while you can enjoy your favorite beverage.
