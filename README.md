<p align="center">
  <a href="" rel="noopener">
 <img width=200px height=200px src="themes\hugo-profile\static\images\avatar.png" alt="Project logo"></a>
</p>

<h3 align="center">Bunthai Profile</h3>

<div align="center">

<!-- [![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/kylelobo/The-Documentation-Compendium.svg)](https://github.com/kylelobo/The-Documentation-Compendium/pulls)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE) -->

</div>

---

<p align="center"> Few lines describing your project.
    <br> 
</p>

## 📝 Table of Contents

- [About Project](#about)
- [Install Hugo](#install)
- [Build & Run Project](#build)
- [Usage](#usage)
- [Built Using](#built_using)
- [Authors](#authors)

<br>

## 🧐 About <a name = "about"></a>

This is the website is all the things about my life, noting and sharing all my konwledges & experiences

<br>

## 🏁 Installing Hugo <a name = "install"></a>

In order to run in local, it's required to install [Hugo](https://gohugo.io/) 

## **Steps**

Download Hugo in here:

```
https://github.com/gohugoio/hugo/releases
```

### Installing

```
Extract files
```

```
Add path to environment
```

<br>

## Initiate project
### Command 
https://gohugo.io/getting-started/usage/

<br>

Create project
```
hugo new site profile
cd profile
git init
```

Add submodule (add Hugo template)
```
git submodule add https://github.com/DBunthai/hugo-profile themes/profile
```
**You can remove `git` from submodule to prevent nested git**

Copy configuration from submodule to main profile https://github.com/DBunthai/profile
```
https://github.com/DBunthai/hugo-profile/tree/master/exampleSite
```

<br>

## 🔧 Build & Running 

Build Project

```
hugo -D -E -F
```

Run Project

```
hugo server --navigateToChanged
```

Build and run project at the same time

```
hugo -D -E -F && hugo server --navigateToChanged
```

Deploy
```
- git add .
- git commit -m "message"
- git push origin master

git auto deploy
```

## ⛏️ Built Using <a name = "built_using"></a>

- [Hugo](https://gohugo.io/) 
- [Github](https://github.com/)

## ✍️ Authors <a name = "authors"></a>

- [@Bunthai](https://github.com/DBunthai) - Idea & Initial work
