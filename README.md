# Smaple Gatsby Portfolio Website
# less UX, more speed. think Mai 1st Update...

## Primefy Sample Content Site
https://primefy.gatsbyjs.io/
![Screen Shot 2021-04-20 at 12 05 57 PM](https://user-images.githubusercontent.com/7315898/115378398-cd9fbf00-a1d0-11eb-905a-2417e104950b.png)

## Gatsby
Gatsby makes the hardest parts of building an amazing digital experience simple. 
When you build with Gatsby, you’ll have an incredibly smooth website that delights and converts visitors. But its not all about the "sex", as described above its about versatile connectivity and overall security. Gatsby is actually faster then developing a WordPress template, it just requires a different philosophy of workflow. 

## CDN (Content Delivery Network)
The new standard architecture for the web is distributed. Using Git workflows and modern build tools, pre-rendered content is served to a CDN and made dynamic through APIs and serverless functions. Technologies in the stack include JavaScript frameworks, Static Site Generators, Headless CMSs, and CDNs.

![Screen Shot 2021-04-20 at 11 40 52 AM](https://user-images.githubusercontent.com/7315898/115377688-23279c00-a1d0-11eb-9712-b524ea4e886c.png)![Screen Shot 2021-04-20 at 11 41 14 AM](https://user-images.githubusercontent.com/7315898/115377446-e9ef2c00-a1cf-11eb-9a36-37552373d75d.png)![Screen Shot 2021-04-20 at 11 41 04 AM](https://user-images.githubusercontent.com/7315898/115377450-ebb8ef80-a1cf-11eb-87aa-f394cd908e40.png)

**Save time with Prebuilds.** Gitpod continuously builds your Git branches like a CI server. This means no more waiting for dependencies to be downloaded and builds to finish. Or [builder.io](http://builder.io) because we run AWS S3.

Build Tools have been downloaded over 100 million times (what is a "[Build Tool](https://stackoverflow.com/questions/7249871/what-is-a-build-tool)") and its safe to say that every technical person today either has a GitHub (reached last year over 12 million users) or a BitBucket account
If you want to use try this out yourself, you first need to set up a project on DatoCMS which will host your data.
You can [sign up for a free account](https://dashboard.datocms.com/signup) and then you can simply click this button:

[![Deploy with DatoCMS](https://dashboard.datocms.com/deploy/button.svg)](https://dashboard.datocms.com/projects/new-from-template/static-website/gatsby-portfolio)

## Repo usage
First, install the dependencies of this project:

```
npm install
```

Add an `.env` file containing the read-only API token of your DatoCMS site:

```
echo 'DATO_API_TOKEN=abc123' >> .env
```

Then, to run this website in development mode (with live-reload):

```
npm run develop
```

To build the final, production ready static website:

```
npm run build
```

The final result will be saved in the `public` directory.

## About

The goal of this project is to show how easily you can create static sites using the content (text, images, links, etc.) stored on [DatoCMS](https://www.datocms.com). This project is configured to fetch data from a specific administrative area using [the API DatoCMS provides](https://www.datocms.com/docs/content-management-api).

You can find further information about how to integrate DatoCMS with Gatsby in [our documentation](https://www.datocms.com/docs/static-generators/gatsbyjs).

This websites uses:

- [GatsbyJS](https://github.com/gatsbyjs/gatsby) as website generator;
- [gatsby-source-datocms](https://github.com/datocms/gatsby-source-datocms) to integrate the website with DatoCMS.
