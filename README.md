# Moonly 🌙

This is an open-source app built using [VulcanJS](http://vulcanjs.org/). It is a place for discovering and sharing useful content for web developers, designers, marketers, growth hackers etc. 
It is a web app, and it also has [Chrome extension](https://github.com/Moonly-App/moonly-extension) as part of it. 

**Technology stack**: React, GraphQL, Apollo, Meteor

**Live website**: https://moon.ly

**Some of the Features**:

- User registration
- User profile page
- Submit post option
- Commenting
- Likes, Votes
- Filtering posts by category or view (latest, popular etc)
- Tags/Categories
- Save posts to profile
- etc...

![](https://i.imgur.com/I4y7TLL.png)


## Installation


Install the latest version of Node and NPM. We recommend the usage of [NVM](https://github.com/creationix/nvm/blob/master/README.md).

You can then install [Meteor](https://www.meteor.com/install).

To get started: clone this repo

```
git clone https://github.com/Moonly-App/moonly-app

cd moonly-app

npm install

npm start

```

Then refer to the [Vulcan documentation](http://docs.vulcanjs.org/) for further information.


## Dependencies

The Moonly app depends on the following VulcanJS [packages](https://github.com/Moonly-App/moonly-app/blob/master/packages/moonly/package.js#L7-L15):

- `vulcan:core`
- `vulcan:forms`
- `vulcan:forms-upload`
- `vulcan:accounts`
- `vulcan:voting`
- `example-forum`

See also `package.json` for a list of NPM dependencies.


## Usage

Check this [video tutorial](https://www.youtube.com/watch?v=-Ndiqsoza1E) on how to use Moonly app and extension.



## Contributing guidance

**All PRs should be made to the `develop` branch, not `master`.**

Before going ahead with customizing components and creating new features, please have in mind that you should

**Never edit original core Vulcanjs packages!** You should only change what's inside the Moonly package.

Check [this part](http://docs.vulcanjs.org/example-customization.html) of documentation to see how to customize existing and create new features.


## Getting help

If you have questions, concerns, bug reports, etc, please file an issue in this repository's issue tracker. 

## Stay In Touch

- [Vanila.io community chat](https://chat.vanila.io)
- [Vulcan.js community chat](http://slack.vulcanjs.org/)

## Credits and references

- [Vanila.io](https://vanila.io) : Team which created and maintain the Moonly app.

| [<img src="https://instagram.fbeg2-1.fna.fbcdn.net/vp/5a92d144cd10f29b0922f812317f2175/5B6F166C/t51.2885-15/e35/30086970_2052232795048853_1375623066507280384_n.jpg" width="100px;"/><br /><sub><b>Jelena Jovanovic</b></sub>](https://instagram.com/plavookac)<br />[👀](https://github.com/jelenajjo) | [<img src="https://scontent.fbeg2-1.fna.fbcdn.net/v/t1.0-9/16938831_1876864695931222_8322976474409168010_n.jpg?_nc_cat=0&oh=a7ba5c1965053059d9c6d21c029f2c9f&oe=5B27E09D" width="100px;"/><br /><sub><b>Abu Taher</b></sub>](https://instagram.com/entrptaher)<br />[👀](https://github.com/entrptaher) | [<img src="https://scontent.fbeg2-1.fna.fbcdn.net/v/t1.0-9/21558004_273521776497426_8560203209024488486_n.jpg?_nc_cat=0&oh=dd03f038949aaface87e72dca5e67642&oe=5B5B2282" width="100px;"/><br /><sub><b>Stefan Smiljkovic</b></sub>](https://www.facebook.com/stefan.smiljkovic)<br />[👀](https://github.com/shtefcs) | [<img src="https://instagram.fbeg2-1.fna.fbcdn.net/vp/63502fd3a5f30409044d94806142e642/5B6F614F/t51.2885-19/s150x150/15803457_1017184685052948_5033685874022285312_n.jpg" width="100px;"/><br /><sub><b>Vijay Verma</b></sub>](https://dribbble.com/realvjy)<br /> |
| :---: | :---: | :---: | :---: |
  
- [Vulcan.js](https://vulcanjs.org) : The full-stack React+GraphQL framework which is OS as well and Moonly is built with it.
  - Sascha (Creator of VulcanJS): @SachaG [twitter](https://twitter.com/SachaGreif)
