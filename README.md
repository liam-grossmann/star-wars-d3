# star-wars-d3

STAR WARS scrolling text from the 1977 movie.

D3 and CSS3 are used to animate images and text. Project built using webpack 5.0.



## Installation 


    git clone https://github.com/liam-grossmann/star-wars-d3.git

    npm install




## Build and Run 

Development

    npm run build

    npm run start

    npm run watch 


Production

When code is checked into github a [workflow job](https://github.com/liam-grossmann/star-wars-d3/blob/main/.github/workflows/azure-static-web-apps-nice-bush-0e3f23110.yml) is automatically run to build and deploy the application to Azure.


## Hosted

| Environment | Description                          | Url                                                |
| ------------| ------------------------------------ | -------------------------------------------------- |
| Dev          | Hosted by Webpack                   | http://localhost:3000/                             | 
| Production   | Hosted by Azure as a static web app | https://nice-bush-0e3f23110.2.azurestaticapps.net/ |



## Dependencies

| Component     | Use                              | Documentation |
| ------------- | -------------------------------- | ------------------------------------------------ |
| Webpack v5.0  | Building and bundling the assets | [Webpack Guides](https://webpack.js.org/guides/) | 
| D3            | Data visualisations library      | [Data Driven Documents](https://d3js.org/)       |



## Webpack

Webpack configured 
* Bundle html, js, css, images into the distribution folder
* Automatically cleans the distribution folder betweeen builds
* Includes a watcher to aid development by auto building when files change
* Includes a rudimentary development server

Not covered
* Code splitting (on demand loads etc)
* Source maps removed because package bundle was too big.


