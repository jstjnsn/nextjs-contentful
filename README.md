# NextJS Contentful

I wanted to see how NextJS works in combination with Contentful. At work we also use Contentful but we don't use NextJS and I thought it would be interesting to try, so here goes.

## Project setup

1. Create the NextJS project: `npx create-next-app --example cms-contentful nextjs-contentful`
1. Create a Contentful account
1. Create a Contentful Space
1. Create a Contentful Personal Access Token
1. Run the setup command to export the example Content Model to your Contentful space: `npx cross-env CONTENTFUL_SPACE_ID=YourSpaceId CONTENTFUL_MANAGEMENT_TOKEN=PersonalAccessToken npm run setup`
1. Create 1 Author Entry and 2 Post Entries in Contentful
1. Create a Space API Key and add the Delivery and Preview keys to the .env.local file

This got me to a point where I can run the app locally.

## Deployment to Vercel

1. TODO
