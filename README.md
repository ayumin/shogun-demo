# Shogun demo

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/ayumin/shogun-demo/tree/master)

[Shogun](https://getshogun.com/) is Powerful drag & drop page building for any website.

This is an example app which is able to create pages with Shogun on [Heroku](https://www.heroku.com/home).

![](https://ucarecdn.com/a0267939-466b-46e6-a650-c027f7f3f63e/)

## Demo
Here is [demo video](https://youtu.be/42EqgRC9woU)

## Deploy
Click button to deploy your app on Heroku, ***now***.

or

Clone this repository into your local machine and push it to Heroku.

````
$ git clone https://github.com/ayumin/shogun-demo.git
$ cd shogun-demo
$ heroku create
$ heroku addons:create heroku-postgresql
$ heroku addons:create shogun
$ git push heroku master
````

## Configuration

Login to [Heroku dashboard](https://dashboard.heroku.com/) and access Shogun dashboard through app setting.

or

Open Shogun dashboard by heroku command

````
$ heroku addons:open shogun
````

Then, you can ready to create new website using Shogun.

Look at [Shogun tutrials](https://getshogun.com/tutorials) to see how to build your awesome website.

## Open your website
After configuration, you can see your website soon.

Open your website from Heroku dashboard

or using heroku command

````
$ heroku open
````

## References
- [Shogun website](https://getshogun.com/)
- [Shogun tutrials](https://getshogun.com/tutorials)
- [Shogun documentations](https://getshogun.com/docs)
- [Shogun Addon page](https://elements.heroku.com/addons/shogun)

Enjoy ;)


