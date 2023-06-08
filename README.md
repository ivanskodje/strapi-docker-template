# 🚀 Getting started with Strapi

## After creating a new project from this Template

After you have created a new project from this template, you are most likely going to get an `denied: installation not allowed to Create organization package` error in the github action script. In order to solve this you need to setup appropriate repository permissions.

1. Go to your repository "Settings"
2. Open "Actions" and select "General"
3. Scroll down to "Workflow permissions"
4. Select "Read and write permissions" and hit Save.
5. Rerun Action.

### `develop`

Start your Strapi application with autoReload enabled. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-develop)

```
npm run develop
# or
yarn develop
```

### `start`

Start your Strapi application with autoReload disabled. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-start)

```
npm run start
# or
yarn start
```

### `build`

Build your admin panel. [Learn more](https://docs.strapi.io/developer-docs/latest/developer-resources/cli/CLI.html#strapi-build)

```
npm run build
# or
yarn build
```

## ⚙️ Deployment

Strapi gives you many possible deployment options for your project. Find the one that suits you on the [deployment section of the documentation](https://docs.strapi.io/developer-docs/latest/setup-deployment-guides/deployment.html).

### With Docker

#### To Production with ivanskodje-strapi:latest

Build: `docker build --file Dockerfile --tag ivanskodje-strapi:latest .`
Run: `docker run -d --restart unless-stopped -p 127.0.0.1:1338:1337 -e NODE_ENV=production --name ivanskodje-strapi ivanskodje-strapi:latest`

#### Locally with ivanskodje-strapi:dev

Build: `docker build --file Dockerfile --tag ivanskodje-strapi:dev .`
Run: `docker run -d --restart unless-stopped -p 127.0.0.1:1338:1337 -e NODE_ENV=development --name ivanskodje-strapi ivanskodje-strapi:dev`

## 📚 Learn more

- [Resource center](https://strapi.io/resource-center) - Strapi resource center.
- [Strapi documentation](https://docs.strapi.io) - Official Strapi documentation.
- [Strapi tutorials](https://strapi.io/tutorials) - List of tutorials made by the core team and the community.
- [Strapi blog](https://docs.strapi.io) - Official Strapi blog containing articles made by the Strapi team and the community.
- [Changelog](https://strapi.io/changelog) - Find out about the Strapi product updates, new features and general improvements.

Feel free to check out the [Strapi GitHub repository](https://github.com/strapi/strapi). Your feedback and contributions are welcome!

## ✨ Community

- [Discord](https://discord.strapi.io) - Come chat with the Strapi community including the core team.
- [Forum](https://forum.strapi.io/) - Place to discuss, ask questions and find answers, show your Strapi project and get feedback or just talk with other Community members.
- [Awesome Strapi](https://github.com/strapi/awesome-strapi) - A curated list of awesome things related to Strapi.

---

<sub>🤫 Psst! [Strapi is hiring](https://strapi.io/careers).</sub>
