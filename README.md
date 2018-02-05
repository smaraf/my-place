# my-place [![Build Status](https://travis-ci.org/smaraf/my-place.svg?branch=master)](https://travis-ci.org/smaraf/my-place)

"My place" is my own corner of the internet. It's my personal website and/or blog. It's the minimum necesary to get my ideas across.

The website is built with [Hexo.io](https://hexo.io/) and hosted on [GitHub Pages](https://pages.github.com/).

## Deployment

A [CI build](https://travis-ci.org/smaraf/my-place/) runs on every checkin. The build generates the static website and force pushes it to my [GitHub Page Repo](https://github.com/smaraf/smaraf.github.io).

## Running locally

* Install [Hexo](https://hexo.io/docs/index.html)

Run `npm run start-blog` to start the hexo server locally.

Run `npm run new [post|page|draft]` to create a new post/page/draft.

Run `npm run build` to generate the static site.

Run `npm run deploy` to deploy the static site.

## Theme

I created a new simple theme that I will customize to accomodate my minimum requirements.