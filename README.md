# Ye Old Sale Manager
> A basic sales management/CRM app.

This app allows you to track sales, products, orders, categories, customers, and contacts. A highlight of this application is the polymorphic table association between addresses and and the aforementioned datasets. A bonus as well is the main dashboard for metric information.

## Screenshots

![Dashboard](https://imgur.com/chckGDe.png)
![List](https://imgur.com/vcGUQch.png)
![Card](https://imgur.com/rqGnu0y.png)

## Installing / Getting started

A quick introduction of the minimal setup you need to get this setup:

First, clone the repo

```shell
git clone git@github.com:limsammy/project_cws.git
```

Next, run

```shell
bundle install && bundle update
```

Note: You may have to run with `bundle exec`

After you've bundled you will need to create the database and migrations

```shell
rake db:create
rake db:migrate
```

If you would like an example set of data and a premade admin account, run
```shell
rake db:seed
```
This seed will create an administrator account with the username `admin@admin.com` and password `password`

Finally, launch the server with `rails s`

You can visit the application locally at http://localhost:3000/

## Developing

To develop the project simply clone the repo and follow the installation steps above.

### Deploying / Publishing

To deploy this to Heroku, simple create a new Heroku app with
```shell
heroku create
```

And upload the master branch
```shell
git push heroku master
```

After that, migrate, and seed if you so wish.

## Contributing

What we would like to implement:
* Testing coverage
* UI improvements
* Email setup documentation
* Product images

Please make a PR to this repo with your code. 

Thank you!

## Licensing

All rights belong to Samuel Lim.
