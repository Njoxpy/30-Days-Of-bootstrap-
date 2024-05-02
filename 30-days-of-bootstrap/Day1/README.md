# Day 1

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Tools](#tools)
- [Installation](#installation)
  - [Using CDN](#using-cdn)
  - [Using Dist Files](#using-dist-files)
  - [Using Package Managers](#using-package-managers)
- [Which Installation Option To Choose](#which-installation-option-to-choose)
- [Resources](#resources)

## Introduction

- Welcome to 30 Days Of Bootstrap, On Day 1 I will work on basics installation and configuration for Bootstrap.

## Prerequisites

- Inorder to learn Bootstrap you need to have a basic understanding of HTML, CSS and JavaScript(Optional).

## Tools

- The following are the list of tools yu need to have inoredr to learn Bootstrap.

|    Tool     | Importance |
| :---------: | :--------: |
| Code Editor | [VS Code](https://vscode.dev/) |
| Browser     |  Chrome/Firefox/Edge/Brave          |
|  Extension  |  [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)          |
|  Version Control(Optional) | Git           |

## Installation

- Inorder to use bootstrap into our project requires some sort of installation procedures into it, There are about 3 ways, the first one is by using CDN, using dist files and NPM respectively.

## Using CDN

- By using content delivery network what is required into our project is just linking our bootstrap projects with bootstrap files for CSS and JavaScript.We use the link tag to link CSS claseses into HTML page and script tag to link JavaScript files into the HTML page.You have to link into the html head page into the meta tag section of the head tag.

```html
<!-- CSS Bootstrap -->
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css"
  rel="stylesheet"
  integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3"
  crossorigin="anonymous"
/>
```

```html
<!-- link to JavaScript Plugins -->
<script
  src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/js/bootstrap.bundle.min.js"
  integrity="sha384-ka7Sk0Gln4gmtz2MlQnikT1wXgYsOg+OMhuP+IlRH9sENBO0LRn5q+8nbTov4+1p"
  crossorigin="anonymous"
></script>
```

## Using Dist Files

- By using dist files which refers to distributable files what is important here you have to download a dist folder which contains the list of all files for working with CSS and JavaScript files, it's like you are downloading a styles.css for CSS and Script.js file for working with JavaScript files to include interactivity.

- So head to [Bootstrap Website](https://getbootstrap.com/docs/4.0/getting-started/download/) and download bootstrap dist for working with CSS files and JavaScript files, bootstrap dist will come as a zip file so you have to unzip it then you will see separate files for `CSS` and `JavaScript`,move those folders into where your project for learning Bootstrap is found.Inorder to link into your files it simple instead of using CDN we link them manually into your PC and that ensures when we are not having mobile data they will still work.

```html
<!-- linking to css folder -->

<!-- linking to js folder -->
```

## Using Package Managers

- By using NPM you can install Bootstrap using node package manager and you link into your project.To install bootstrap into your project use the following command.

```sh
# install latest version using NPM
npm install bootstrap@v5.3.3

# using yarn
yarn add bootstrap@v5.3.3

# using composer
composer require twbs/bootstrap:5.3.3

# using gem
gem install bootstrap -v 5.3.3
```

## Which Installation Option To Choose

- The choice of installation option to choose depends into your choice.If You have internet connection then using `CDN` is the best choose because what is required is only linking them into meta tag using link tag and for JavaScript file just linking another thing is that Using CDN is simple and easily for setting up.

- Use Bootstrap dist files if you want to work offline for your bootstrap projects also you can customize them into your project based into on your choice.

- Using NPM: If you're using a build tool like Webpack or Gulp in your project, you can install Bootstrap via npm. This allows you to manage dependencies more easily and integrate Bootstrap into your build process. It's a good option for larger projects or projects that require more customization.

- Using Sass or Less: Bootstrap also provides the source files written in Sass or Less, which allows for even more customization. You can install Bootstrap via npm and then import the Sass or Less files into your own stylesheets, making it easier to customize Bootstrap's variables and styles.

- The best option depends on factors like project size, customization needs, and your familiarity with different tools and workflows. For quick prototypes or smaller projects, the CDN option might be the best. For larger projects with more complex styling requirements, using npm and Sass or Less might be a better choice.

## Exercise

## Resources

- [Bootstrap Official Documentation](https://getbootstrap.com/)
- [bootstrap Github](https://github.com/twbs/bootstrap)

[Day 2](/30-days-of-bootstrap/Day2/README.md)
