# Evoke Marketplace

An open source community engagment platform that uses Stripe for payment processing. This repo is for the backend API which is built on top of [Strapi Headless CMS](https://strapi.io).

## Goals

- Easily manage membership accounts
- Allow members to easily pay subscription fees (if any)
- Offer free programs for general public
- Offer paid programs for members
- Send Notifications to all members
  - Email, Mobile (SMS)
  - Allow members to manage notifications

## Getting Started

1. Create a new folder and change directories.<br/>
   `$ mkdir evoke-marketplace && cd evoke-marketplace`
1. Clone this project.<br/>
   `$ git clone [REPO_URL] server`
1. Change into the server directory.<br/>
   `$ cd server`
1. Install dependencies using `yarn` or `npm`.<br/>
   `$ yarn install`
1. Copy `.env.sample` to a new file `.env`.<br/>
   `$ cp .env.sample .env`
1. Update `.env` with the proper values.<br/>
   `$ vim .env`
1. Start the development server.<br/>
   `$ yarn dev`
1. Create the first Administrator account by visiting:<br/> http://localhost:1337/admin
