----
# parcel boilerplate
<p align="center">
<strong><a href="#link1">Link 1</a></strong>
|
<strong><a href="#link2">Link 2</a></strong>
|
<strong><a href="#link3">Link 3</a></strong>
|
<strong><a href="#link4">Link 4</a></strong>
|
<strong><a href="#link5">Link 5</a></strong>
</p>
----
## table of contents
- [Installation](#installation)
  - [sub1](#sub1)
  - [sub2](#sub2)
- [Usage](#usage)
  - [sub3](#sub3)
  - [sub4](#sub4)
- [License](#license)
- [Links](#links)


## Installation

System Prerequisites:

- Node.js
- Package manager can be npm pmpm or yarn
- Router (default  will be Express.js)
- Preferred IDE (vim, VSCode, etc)
- Any modern browser

Clone this repository:

(Master Boilerplate)[https://github.com/ColorInCodeMe/DefaultParcelBoilerplateBP.git]

```

echo "# DefaultParcelBoilerplateBP" >>
git init
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/ColorInCodeMe/DefaultParcelBoilerplateBP.git
git push -u origin main

```

First steps

- Run your package manager install on your local environment (we are using npm here)
- Add yarn 

~~~

npm install yarn

~~~


- Add parcel

~~~

yarn add parcel

~~~

- If you get a transformer sass error, update the SCSS transformer-sass dependency (with yarn or pkg manager):

~~~

yarn add @parcel/transformer-sass

~~~

- A successful build should give you a build time and cached files

- Initiate yarn start command in the terminal. This should open and render your skeleton template in the default browser.

## Code Structure and Abstraction

└─.parcel-cache

└─css

└─dist

└─js

└─node-modules

└─scss

└─src

Package specific files for this boilerplate

- .gitignore
- action.yml
- package.json
- yarn.lock
- .postcssrc
- cssnano.config.js
