# GrowersBrainsBackend

GrowersBrains is an app designed to solve the problems that growers globally are Facing and to bring expert growing techniques to everyone. Grow Green and Grow Clean.

As a community project that will enable collaborators to:

:heavy_check_mark: Sharpen their skill sets

:heavy_check_mark: Learn new languages

:heavy_check_mark: Work in a team environment

:heavy_check_mark: Get real world experience

:heavy_check_mark: Make something that helps the world

:heavy_check_mark: learn all about the process of taking an app from idea to product

:heavy_check_mark: and most importantly, have fun along the way.

# Motivation

The way that I came up with the idea is that I have 15 years of experience of growing plants. Starting in middle school Horticulture class at 11 up to now at 26, I've learned a lot from books and the internet but the place that I have always learned the most was from other growers teaching me the techniques that took them years to develop and perfect.

This lead me to the idea of creating an app that brings a collective consciousness of **growers** together to change the way the world grows. Growing plants can be expensive and can lead to great losses if not done properly. When done properly it can be a fun, exciting and relaxing way to control the quality of the food or medicine that you are growing and ensure that it is as clean and pure as possible.

### Tech Stack

:rocket: React

:flying_saucer: Node

:artificial_satellite: MongoDB

:airplane: Express

# Features & Designs

The current design that I have for the app is to have eight different sections.

### Sections

All of these features would allow for great data to be collected and machine learning to be created to diagnose plant problems, and make elite growing accessible to everyone no matter their experience level.

# To Contribute here (version control)

1. Click on Fork at the top right corner
2. Clone your forked repository
3. `cd` into the cloned folder | GrowersBrains
4. `git remote add upstream https://github.com/nicholashindy/GrowersBrains.git`
5. `git pull upstream` <YOUR_BRANCH>
6. Check out to the task branch by `git checkout -b` <NAME_OF_THE_TASK>

# To run the app in development

1. Run `npm install` from the **root**
2. run `npm run server:dev` from the root

## Set environment variables

You can create a .env file in your root project folder and add theses configurations. Be sure to modify the values beforehand. **_Never commit .env file to github._**

```bash
PORT=5000
NODE_ENV = development
MONGO_URI = <YOUR_MONGO_URI> (Only for hosted Database)

JWT_SECRET= <JWT_SECRET>
JWT_EXPIRES_IN=<JWT_EXPIRATION_DATE> (Ex : 90d )

COOKIE_EXPIRES_IN = <COOKIE_EXPIRATION_Date> (Ex : 90)

//For MailTrap. You will need to create a MailTrap account
EMAIL_HOST=smtp.mailtrap.io
EMAIL_PORT=2525
EMAIL_USERNAME=<YOUR_MAILTRAP_EMAIL_USERNAME>
EMAIL_PASSWORD=<YOUR_MAILTRAP_EMAIL_Password>
```

# To import/delete development data to/from your database

**To Import Data** Run `npm run import-data`
**To Delete Data** Run `npm run delete-data`

# Creating a pull request (when done with your code/changes)

1. Run `git add .`
2. Run `git commit -m` <COMMIT_MESSAGE>
3. `git push origin` <BRANCH_NAME>

Go to the repository https://github.com/nicholashindy/GrowersBrains.git.

As soon as you get there, you are going to see a green **Compare and Create a pull request**.

Click on it and type your message then click on **Create pull request**.

Thanks to: **@chisombiri** :heart:

# Getting Started / Installation

If you want to join send **@nah** a message in Discord.

Trello board: https://trello.com/invite/b/1VgFXdo7/0135f2a7507e6062eb03f23bcf76ae3c/growers-brains

# Team

:computer: Project Lead: **@nah**

:briefcase: Project Manager: **@Kael0527**

:bar_chart: front end Lead: @natalie_p

:rocket: React Lead: **@Gajendra**

# Handy Resources

- [React.js official documentation](https://reactjs.org/docs/getting-started.html)
- [Why indoor plants make you feel better](https://www.google.com/amp/s/www.nbcnews.com/better/amp/ncna781806)
- [Finally, really good advice on how to stop killing your houseplants](https://www.google.com/amp/s/www.vox.com/platform/amp/the-highlight/2019/12/30/21031913/how-to-keep-houseplants-alive-masterclass-plants-swiss-cheese-millennials-plantfluencer)
