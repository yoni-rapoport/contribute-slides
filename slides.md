---
theme: apple-basic
layout: intro
---
# Contribute to Remult 🚀

<div class="absolute bottom-10">
  <span class="font-700">
    Yoni Rapoport
  </span>
</div>

<!--
- Ask audience - Who's working on / contributing to open-source?
  - Who's published his own library to other users?
- Let's make this interactive - stop me when you have a question
-->
---

# Dive into Remult's World 🌍

- 🌐 **Repo Magic:** [github.com/remult/remult](https://github.com/remult/remult)

- 📚 **Engage with Docs:** [Remult.dev](https://remult.dev)

- 🎉 **Join the Community:** [Remult Discord](https://discord.gg/GXHk7ZfuG5)

<!--
- Start by getting to know remult
  - Tutorials
  - Examples
  - Videos
  - Docs
-->
---

# Spot the Opportunities 🕵️‍♂️

- 📝 **GitHub Conversations:** Dive into issues, discussions, and more.

- 💬 **Discord Dialogues:** Share, learn, innovate!

<!-- 
- Interestingly most feedback starts on the Discord channel
- Also check out discussions
-->
---

# It's Not Just About the Code 🖥️

- 📖 **Docs Do Matter:** Share your insights.

- 🛠️ **Project Prototypes:** Showcase what's possible.

- 🖋️ **Blog About It:** Tell your Remult tales.

- 📣 **Every Idea Matters:** We're listening!

<!-- 
- While the library itself is relatively complete, the Docs and content around it partial and lacking
- If you ask us what's the most important thing one can contribute at this point in time - it's content
-->
---
layout: statement
---

# Backlog? What's That? 😂

Why wait? Core maintainers here are always on the move.

<!-- 
- Bugs are usually fixed and patched within 24 hours
- Feature requests for stuff that users need are acted on quickly
- That doesn't mean you can't contribute - it just means you'll have to find work on your own...
-->
---

# Gear Up for Action 🔧

- 🍴 **Fork to Learn:** Your very own Remult sandbox.

- 🔧 **Setup Locally:** `git clone`, then `npm i`.

- 📈 **Vitest for Tests:** Just `npm test`.

- 📘 **Docs Adventure:** Dive in with Vitepress in the "docs" folder: `npm i` and `npm run dev`. 

<!-- 
- Forking and developing locally is (now) pretty easy to do 
  - Some tests won't run if you don't have DBs installed, but that's fine
    - All tests run during CI
- Let's see the repo I cloned on this PC
  - Let's run the tests
  - Let's try editing the docs
-->
---
layout: section
---

# Deep Dive into the Architecture

Compact. Powerful. ~12K lines of TypeScript complemented by ~14K of tests.

---

## 🧠 Core Constructs:

- **Remult Object:** Interaction central.

- **Repository:** Entity central.

- **Entity & Field Decorators:** Model definers.

- **Query Objects:** The bridge.

- **Relations:** Relationship handlers.

<!-- 
- I'll try do divide Remult's code base into 3 conceptual areas
- Joke about "don't touch this!"
- Seriously you probably won't start with touching these
-->
---

## 🛠️ Ready-Made Implementations:

_Grow Remult with your touch!_

- **Field Types**: Every field is special.

- **Validators:** Precision in data.

<br/><br/>

To Consider...
- React (Hooks, Suspense, etc.)
- State Management (TanStack query and beyond)
- Forms

<!-- 
- This is basically stuff that starts with identifying repetitive code while using remult
- Examples (show code):
  - Field types - autoIncrement, createAt, updatedAt, uuid
  - Validators - required, unique
-->
---

## 🔌 Pluggable Infrastructure:

_Open doors to new realms._

- **Data Providers:** Postgres, MongoDB, Knex, JSON...

- **Framework Integrations:** Express, Fastify to SvelteKit and more.

- **Live Query Flavors:** SSE, Ably, you name it.

- **GraphQL:** Some people like it.

<br/><br/>

- **New Frontiers:** Integrate Nuxt, SolidStart, Qwik...

<!-- 
- This can be a good area for adding value to Remult without messing with the core code
- Data Providers - we published with just PG and JSON, then added Knex, then Mongo...
- BE/FS frameworks - at the beginning we we're sure Express is all we need... 
  - Someone asked for Deno so we did that
  - Recently released Next.js App Router
  - As more are added - the underlying abstraction becomes more powerful (show code for 'remultNext','remultFastify')
- Examples - the story about jean-yeaves and SvelteKit and GraphQL
  - Show PRs
-->
---

# Your Roadmap to Contributing 🛤️

1. 🎮 **Play as a User:** Get familiar with Remult.

2. 🧩 **Encounter an Issue or Dream Up a Feature:** Inspiration can strike anytime!

3. 🛠️ **Demo Project:** Illustrate the issue or feature.

4. 🔧 **Craft the Solution:** Start in your sample project.

5. 🔀 **Integrate into Remult:** Make your mark!

<br/><br/> 

## 💬 **Stay Connected:** Reach out anytime. We're here to help!

---

# PRs & Issues: Our Simple Rules 📜

- 🔄 **Code & Value:** If it works and adds value, we're listening.

- ✅ **Tests:** Keep them green.

- 🖋️ **Just Prettier It:** Before hitting that PR button, run 'prettier'.


---
layout: statement
---

# Let's Build Remult Together

Every contribution pushes Remult to new horizons. Join the journey! 🌱🌟