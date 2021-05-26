# joshgebara.com [![Netlify Status](https://api.netlify.com/api/v1/badges/551428a6-c7bb-439c-8af1-e72aa8bdc5ca/deploy-status)](https://app.netlify.com/sites/joshgebara/deploys)

<h1 align="center">
  <img src="./source/img/logo.png" alt="Josh Gebara" width="300">
</h1>

<p align="center">My personal website <a href="https://joshgebara.com/">joshgebara.com</a></p>

<p align="center">
  <a href="#getting-set-up-for-development">Getting Set Up for Development</a> •
  <a href="#server-setup">Server Setup</a> •
  <a href="#branching-model">Branching Model</a> •
  <a href="#license">License</a>
</p>

---

## Getting Set Up for Development

To clone and run this application, you'll need [Git](https://git-scm.com) and [Node.js](https://nodejs.org/en/download/) (which comes with [npm](http://npmjs.com)) installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/joshgebara/joshgebara.com.git

# Go into the repository
$ cd joshgebara.com

# Install dependencies
$ npm install
```

**Note:** This is a static website and does not use an npm script to run. `npm install` is used to automatically set up a pre-commit hook to format the code with [Prettier](https://prettier.io/). Both the `master` and `develop` branches of this repo are protected and all pull requests must pass [Prettier](https://prettier.io/) validation before they can be merged.

## Deployment

This is a static website served from [Netlify](https://www.netlify.com/). Deploys happen automatically after every merged pull request into `master`.

## License

[MIT License](https://choosealicense.com/licenses/mit/)
