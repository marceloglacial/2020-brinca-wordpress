![Heroku](https://pyheroku-badge.herokuapp.com/?app=brinca-2020)

# Brinca 2020 - WordPress
Brazil-Canada Community Association's website.

## Live Demo

- <a href="https://brinca-2020.herokuapp.com/">Brinca 2020 (Heroku)</a>


## Stack and Features

- CMS: <a href="https://wordpress.org/">WordPress</a>
- PHP dependency Manager: <a href="http://getcomposer.org/">Composer</a>
- Project structure: <a href="https://roots.io/bedrock/">BedRock</a>
- Deployment: <a href="https://github.com/PhilippHeuer/wordpress-heroku">WordPress on Heroku</a>
- Heroku Keep Alive: <a href='https://uptimerobot.com/'>Uptime Robot</a>
- Image CDN: <a href="https://cloudinary.com/">Cloudinary</a>
- Site Builder: <a href="https://github.com/marceloglacial/snow-blocks">Snow Blocks</a>
- Local development: <a href='https://www.docker.com/'>Docker</a>

## How to Install

1. Config your `.env` file using `.env.example` as model
2. Run composer to install dependencies: `composer update`
3. Set Wordpress permalinks to `Post Name`

NOTE: You need to setup your env variable on your server too.

## Local development

```
composer update
npm run dev
```
