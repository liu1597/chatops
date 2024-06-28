

## Setup Instructions

> Note: Node version 18 is required 

### Netlify

Netlify is used as a live tunnel for testing the application. 

1. Visit https://www.netlify.com
2. Click **Sign Up** to create a new account.

The Netlify CLI is also required for the course. 

1. Install the Netlify CLI: `npm i -g netlify-cli`
2. Login to your Netlify account: `ntl login`
3. Initialize the project: `ntl init`
4. Start the dev server: `ntl dev --live`

### Slack

A free Slack account and workspace is required:

1. Visit https://slack.com
2. Create a new account or sign in


1. Visit https://api.slack.com
2. Click **Create new App** and choose to create it from scratch
3. Name the application Food Fight and choose to deploy it to your test workspace

**Long description for the application **

Is your workday going too smoothly? Everyone is being productive and that makes you suspicious? Why not derail the whole team by starting a heated argument about food?

- Is sous vide an acceptable way to cook a burger?
- Does mayonnaise go on chips?
- Want to convince everyone that pineapple belongs on pizza?

Make your spiciest assertions and watch your team devolve into culinary fisticuffs. With Food Fight, remind your coworkers that you are an agent of chaos!

### Notion

Notion is used to store data from the Slack application. You'll need to create a free Notion account:

1. Visit https://notion.com
2. Create a new account if you don't already have one.
3. [optional] Create a new workspace


A new integration is created during the :

1. Visit https://www.notion.so/my-integrations
2. Click the New Integration button
3. Select the workspace you want to use for the application
4. Add the basic information and an image from the `assets` directory.
5. Visit the Food Fight Database you duplicated into your workspace and add the Food Fight connection.
6. From the integrations section, copy the secret into a `NOTION_SECRET` environment variable
7. Copy the database ID into a `NOTION_DATABASE_ID` environment variable
