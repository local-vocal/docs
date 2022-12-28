### Tutorial

{{< alert icon="👉" text="The Tutorial is intended for novice to intermediate users." />}}

Step-by-step instructions on how to start a new Doks project. [Tutorial →](https://getdoks.org/tutorial/introduction/)

### Quick Start

{{< alert icon="👉" text="The Quick Start is intended for intermediate to advanced users." />}}

## Go further

Recipes, Reference Guides, Extensions, and Showcase.

### Recipes

Get instructions on how to accomplish common tasks with Doks. [Recipes →](https://getdoks.org/docs/recipes/project-configuration/)

### Reference Guides

Learn how to customize Doks to fully make it your own. [Reference Guides →](https://getdoks.org/docs/reference-guides/security/)

### Extensions

Get instructions on how to add even more to Doks. [Extensions →](https://getdoks.org/docs/extensions/breadcrumb-navigation/)

### Showcase

See what others have build with Doks. [Showcase →](https://getdoks.org/showcase/electric-blocks/)

## Contributing

Find out how to contribute to Doks. [Contributing →](https://getdoks.org/docs/contributing/how-to-contribute/)

## Help

Get help on Doks. [Help →]({{< relref "how-to-update" >}})

- [Git](https://git-scm.com/) — latest source release
- [Node.js](https://nodejs.org/) — latest LTS version or newer

{{< details "Why Node.js?" >}}
Doks uses npm (included with Node.js) to centralize dependency management, making it [easy to update]({{< relref "how-to-update" >}}) resources, build tooling, plugins, and build scripts.
{{< /details >}}

## Start a new Doks project

Create a new site, change directories, install dependencies, and start development server.

### Create a new site

Doks is available as a child theme and a starter theme.

#### Child theme

- Intended for novice to intermediate users
- Intended for minor customizations
- [Easily update npm packages]({{< relref "how-to-update" >}}) — **including** [Doks](https://www.npmjs.com/package/@hyas/doks)

```bash
git clone https://github.com/local-vocal-child-theme.git my-doks-site
```

#### Starter theme

- Intended for intermediate to advanced users
- Intended for major customizations
- [Easily update npm packages]({{< relref "how-to-update" >}})

```bash
git clone https://github.com/local-vocal.git my-doks-site
```

{{< details "Help me choose" >}}
Not sure which one is for you? Pick the child theme.
{{< /details >}}

### Change directories

```bash
cd my-doks-site
```

### Install dependencies

```bash
npm install
```

### Start development server

```bash
npm run start
```

Doks will start the Hugo development webserver accessible by default at `http://localhost:1313`. Saved changes will live reload in the browser.

## Other commands

Doks comes with commands for common tasks. [Commands →]({{< relref "commands" >}})
