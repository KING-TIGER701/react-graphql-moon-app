# Moon 🌙

This is an open-source app built using [VulcanJS](http://vulcanjs.org/). It is a place for discovering and sharing useful content for web developers, designers, marketers, growth hackers etc. 
It is a web app, and it also has [Chrome extension](https://github.com/KING-TIGER701/moonly-extension) as part of it. 

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

Prerequisites for Linux:
```bash
sudo apt install g++
```

To get started: clone this repo

```
git clone https://github.com/KING-TIGER701/react-graphql-moon-app.git

cd react-graphql-moon-app

npm install

npm start

```

Then refer to the [Vulcan documentation](http://docs.vulcanjs.org/) for further information.


## Dependencies

The Moonly app depends on the following VulcanJS [packages](https://github.com/KING-TIGER701/react-graphql-moon-app.git/blob/master/packages/moonly/package.js#L7-L15):

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
