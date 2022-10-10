# About Website

This website is built using [Docusaurus 2](https://docusaurus.io/), a modern static website generator.

[![Views](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fsohamsshah%2Finsight-jainism&count_bg=%23000000&title_bg=%23555555&icon=github.svg&icon_color=%23E7E7E7&title=views&edge_flat=true)](https://hits.seeyoufarm.com)
[![GitHub stars](https://img.shields.io/github/stars/sohamsshah/insight-jainism?style=flat-square)](https://github.com/sohamsshah/insight-jainism/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/sohamsshah/insight-jainism?style=flat-square)](https://github.com/sohamsshah/insight-jainism/network)
[![GitHub issues](https://img.shields.io/github/issues/sohamsshah/insight-jainism?style=flat-square)](https://github.com/sohamsshah/insight-jainism/issues)
![GitHub pull requests](https://img.shields.io/github/issues-pr/sohamsshah/insight-jainism?color=yellow&style=flat-square)

### Installation Guide

```
$ yarn
```

### Local Development

```
$ yarn start
```

This command starts a local development server and opens up a browser window. Most changes are reflected live without having to restart the server.

### Build

```
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

Using SSH:

```
$ USE_SSH=true yarn deploy
```

Not using SSH:

```
$ GIT_USER=<Your GitHub username> yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.
