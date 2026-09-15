## 👋🏽 Hello, I'm Angelo

I'm a 🇵🇪 Peruvian developer and university student.

- 💬 My native language is Spanish, and I later learned English. You might sometimes see me participating in translation projects.
- 🎓 Currently studying **Informatics Engineering** at [PUCP](https://www.pucp.edu.pe/en/).
- 💻 Focused on OOP development with **[TypeScript](https://www.typescriptlang.org/)** on [Node.js](https://nodejs.org/en/), and [Java](https://www.java.com/es/). When it comes to APIs, I'm mostly experienced with the [Discord API](https://discord.com/developers/docs/reference) and the [SpigotMC](https://www.spigotmc.org/)/[PaperMC](https://papermc.io/software/paper) plugin APIs.

---

<details>
<summary><h2>✨ Featured Projects...</h1></summary>

### [🏭 nyx](https://github.com/nyx-discord/nyx)
A Typescript framework for developing [Discord.js](https://discord.js.org/) bots.
#### Features
- OOP based.
- Fully extensible via [constructor dependency injection](https://en.wikipedia.org/wiki/Dependency_injection?oldformat=true), adhering to [SOLID](https://en.wikipedia.org/wiki/SOLID?oldformat=true) design principles.
- High usage of native Discord.js objects, unlike other frameworks that wrap or completely replace their objects in their own implementations.
- Designed with type safety in mind, for example, [typing on event subscription](https://nyx-discord.github.io/nyx/docs/features/events/event-overview#-event-type-safety).
#### Tech Stack
- [PNPM](https://pnpm.io/) - Managing packages and the monorepo.
- [Jest](https://jestjs.io/) - Testing. Currently being rewritten with [Vitest](https://vitest.dev/).
- [ESLint](https://eslint.org/), [Prettier](https://prettier.io/) - Linting and formatting.
- [Lerna](https://lerna.js.org/) - Building, [semantic versioning](https://semver.org/) and publishing to [NPM](https://www.npmjs.com/) and [GitHub Packages](https://docs.github.com/en/packages/learn-github-packages/introduction-to-github-packages).
- [Husky](https://typicode.github.io/husky/) - Running git tasks before committing.
- [TSUp](https://github.com/egoist/tsup) - Bundling with [esbuild](https://github.com/evanw/esbuild).
- [Nx](https://nx.dev/) - Improving upon Lerna's building, with caching and more advanced tasks. Currently being rewritten with [Turborepo](https://turbo.build/).
- [Typedoc](https://typedoc.org/) - Automatic type documentation at https://nyx-discord.github.io/nyx/typedoc/.
- [Docusaurus](https://docusaurus.io/) - Manual documentation at https://nyx-discord.github.io/nyx/docs/.
- [GitHub Actions](https://github.com/features/actions) - CI/CD.

---

### [💬 enki-bot](https://github.com/Amgelo563/enki-bot)
A data-driven Discord bot for creating message tags.

#### Features
- Completely custom commands, subcommands and options.
- Advanced weighted searching by tag content and keywords.
- Tag linking or extra messages via buttons.
- Tag discovery by glob patterns.
- Automatic tag synchronization with a git repo.

#### Tech Stack
- [PNPM](https://pnpm.io/) - Managing packages.
- [Valibot](https://valibot.dev/) - Configuration files' schema validation.
- [semantic-release](https://github.com/semantic-release/semantic-release) - Versioning and releasing.
- [ESLint](https://eslint.org/), [Prettier](https://prettier.io/) - Linting and formatting.
- [GitHub Actions](https://github.com/features/actions) - CI/CD.

---

### [💹 hermes-bot](https://github.com/Amgelo563/enki-bot)
A Discord bot for publishing service request and offers in a guild.

#### Features
- Completely customizable messages and commands.
- User blacklisting, either temporal or permanent.
- CRUD commands for services, tags and blacklists.
- Service searching by filters like tag and recency.
- Advanced placeholder system, allowing nested placeholders and property querying.
- Automatic service moderation via entirely user-configurable requirements.

#### Tech Stack
- [PNPM](https://pnpm.io/) - Managing packages.
- [Zod](https://zod.dev/) - Configuration files' schema validation.
- [Prisma](https://www.prisma.io/orm) - Type safe database ORM.
- [Vitest](https://vitest.dev/) - Testing.
- [semantic-release](https://github.com/semantic-release/semantic-release) - Versioning and releasing.
- [Husky](https://typicode.github.io/husky/) - Running git tasks before committing.
- [Docker](https://www.docker.com/) - As a supported deployment option.
- [ESLint](https://eslint.org/), [Prettier](https://prettier.io/) - Linting and formatting.
- [GitHub Actions](https://github.com/features/actions) - CI/CD.

---

### [🔍 javadocs-scraper](https://github.com/Amgelo563/javadocs-scraper)
A TypeScript library to scrape Java objects information from a Javadocs website.

#### Features
Scrapes:
- [Packages](https://github.com/Amgelo563/javadocs-scraper/blob/main/src/entities/package/PackageData.ts)
- [Classes](https://github.com/Amgelo563/javadocs-scraper/blob/main/src/entities/class/ClassData.ts)
- [Interfaces](https://github.com/Amgelo563/javadocs-scraper/blob/main/src/entities/interface/InterfaceData.ts)
- [Object Type Parameters (Object Generics)](https://github.com/Amgelo563/javadocs-scraper/blob/main/src/entities/object/ObjectTypeParameterData.ts), on classes and interfaces
- [Enums](https://github.com/Amgelo563/javadocs-scraper/blob/main/src/entities/enum/EnumData.ts)
    - [Enum Constants](https://github.com/Amgelo563/javadocs-scraper/blob/main/src/entities/enum/constant/EnumConstantData.ts)
- [Annotations](https://github.com/Amgelo563/javadocs-scraper/blob/main/src/entities/annotation/AnnotationData.ts)
    - [Annotation Elements](https://github.com/Amgelo563/javadocs-scraper/blob/main/src/entities/annotation/element/AnnotationElementData.ts)
- [Fields](https://github.com/Amgelo563/javadocs-scraper/blob/main/src/entities/field/FieldData.ts)
- [Methods](https://github.com/Amgelo563/javadocs-scraper/blob/main/src/entities/method/MethodData.ts)
    - [Return Type](https://github.com/Amgelo563/javadocs-scraper/blob/main/src/entities/method/return/MethodReturnData.ts)
    - [Parameters](https://github.com/Amgelo563/javadocs-scraper/blob/main/src/entities/parameter/ParameterData.ts)
    - [Type Parameters (Method Generics)](https://github.com/Amgelo563/javadocs-scraper/blob/main/src/entities/method/type/MethodTypeParameterData.ts)

#### Tech Stack
- [Cheerio](https://cheerio.js.org/) - Parsing and manipulating fetched HTML.
- [TSUp](https://github.com/egoist/tsup) - Bundling with [esbuild](https://github.com/evanw/esbuild).
- [PNPM](https://pnpm.io/) - Managing packages.
- [semantic-release](https://github.com/semantic-release/semantic-release) - Versioning and releasing to NPM.
- [Husky](https://typicode.github.io/husky/) - Running git tasks before committing.
- [Typedoc](https://typedoc.org/) - Automatic type documentation at https://amgelo563.github.io/javadocs-scraper/.
- [ESLint](https://eslint.org/), [Prettier](https://prettier.io/) - Linting and formatting.
- [GitHub Actions](https://github.com/features/actions) - CI/CD.

</details>

---

## ☎ Contact

[![Mail](https://img.shields.io/badge/mail-email%40amgelo563.me-dd4336?style=for-the-badge&logo=gmail)](mailto:email@amgelo563.me)
[![Discord](https://img.shields.io/badge/amgelo563-%235662f6.svg?style=for-the-badge&logo=discord&logoColor=white)](https://discordapp.com/users/235428738748121088)
[![Reddit](https://img.shields.io/badge/Amgelo563-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/user/Amgelo563/)

## 📊 Stats

Powered by [Wakatime](https://wakatime.com/) and [anuraghazra/github-readme-stats](https://github.com/anuraghazra/github-readme-stats).

<table cellspacing="0" cellpadding="0">
  <tr>
    <td style="border: none;"><img src="https://github-readme-stats-fawn-tau-63.vercel.app/api/wakatime?username=@84d4f8dc-edb7-4aaf-a6d3-39a0bf3fed51&theme=algolia&layout=compact&custom_title=🌌%20Last%20365%20days"></td>
    <td style="border: none;" valign="top"><img src="https://github-readme-stats-fawn-tau-63.vercel.app/api?username=Amgelo563&show_icons=true&theme=algolia&include_all_commits=true&custom_title=🌐%20Total%20stats&include_all_commits=true"></td>
  </tr>
</table>
