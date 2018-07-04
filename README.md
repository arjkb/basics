# Basics
A minimal theme for those who like to keep it simple. Makes use of bootstrap.

Based on the [Elephants theme](https://themes.gohugo.io/elephants/).

## Features
* Responsive theme
* High contrast
* Focus on content and readability

## Installation
From your hugo site, run:
```
git submodule add https://github.com/arjunkrishnababu96/basics.git themes/basics
```

## Configurations
#### Add author name
Add author name to the `.Site.Params.author` parameter in your `config.toml` file.

See below for an example:
```
baseURL = ""
languageCode = "en-us"
title = "Basics Theme Demo"
theme = "basics"

[params]
    author = "Author Name"
```

#### Add Links to GitHub and GitLab
Add GitHub and GitLab usernames to `.Site.Params.github` and `.Site.Params.gitlab` parameters in your `config.toml` file. Links to these accounts would show up in the top navigation bar. If these parameters are not present or is left blank, the links would disappear.

See below for an example:
```
baseURL = ""
languageCode = "en-us"
title = "Basics Theme Demo"
theme = "basics"

[params]
    author = "Author Name"
    github = "username1"
    gitlab = "username2"
```


## License

Released under the MIT License.
