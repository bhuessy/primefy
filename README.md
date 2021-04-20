# Smaple Gatsby Portfolio Website
https://primefy.admin.datocms.com/![Screen Shot 2021-04-20 at 11 41 14 AM](https://user-images.githubusercontent.com/7315898/115375119-c5925000-a1cd-11eb-9f13-5146d996ee40.png)
<img width="1680" alt="Project Managment over Word" src="https://user-images.githubusercontent.com/7315898/115375124-c6c37d00-a1cd-11eb-991c-8abb90b4126c.png">
![Screen Shot 2021-04-20 at 11 41 04 AM](https://user-images.githubusercontent.com/7315898/115375144-ca570400-a1cd-11eb-85c4-961e1b1f1890.png)
![Screen Shot 2021-04-20 at 11 40 57 AM](https://user-images.githubusercontent.com/7315898/115375146-caef9a80-a1cd-11eb-9bd8-ef73ae410472.png)


This repo contains a static website written with [GatsbyJS](https://www.gatsbyjs.org/), integrated with content coming from [DatoCMS](https://www.datocms.com).


Gatsby makes the hardest parts of building an amazing digital experience simple. When you build with Gatsby, you’ll have an incredibly smooth website that delights and converts visitors. But its not all about the "sex", as described above its about versatile connectivity and overall security. Gatsby is actually faster then developing a WordPress template, it just requires a different philosophy of workflow. Build Tools have been downloaded over 100 million times (what is a "[Build Tool](https://stackoverflow.com/questions/7249871/what-is-a-build-tool)") and its safe to say that every technical person today either has a GitHub (reached last year over 12 million users) or a BitBucket account

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
