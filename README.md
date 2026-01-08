
#  Flare Africa

Welcome to **Flare Africa**, the decentralized home for the next generation of African builders on the Flare Network. This project is entirely content-driven and open-source. We believe that by documenting our journey, we empower the entire continent to lead the data revolution.

First off, thank you for considering contributing to Flare Africa! It’s people like you that make the Flare ecosystem thrive.

We follow a structured process to ensure all content is technically accurate, SEO-optimized, and helpful for developers.


##  How to Contribute

We use a "Blog-as-Code" approach. Our entire blog system is powered by **Astro Content Collections** and GitHub. You don't need to be a developer to contribute, you just need to know a little Markdown.

### 1. The Workflow

1. **Fork** this repository to your own GitHub account.
2. **Clone** your fork to your local machine.
3. **Create** a new branch for your article: `git checkout -b blog/your-post-title`.
4. **Add** your content (see the "Writing the Post" section below).
5. **Push** and open a **Pull Request (PR)**.



### 2. Writing your Post

All blog posts live in the `src/content/blog/` directory. Your file should be named with a slug format: `my-awesome-post.md`.

### The Critical "Frontmatter"

Every post **must** start with a block of metadata called Frontmatter. This tells the website how to display your post in the grid. If this is missing or incorrect, the build will fail.

**Example Template:**
Copy this exact block to the top of your `.md` file:

```markdown
---
title: "Beginner’s Guide to Writing Markdown"
author: "Monday Ese"
date: "2026-01-06"
description: "A 160-character summary that tells developers what they will build or learn."
summary: "A brief 2-3 sentence overview of the technical concepts covered."
image: "/blog-placeholder.png" # Optional: path to your post thumbnail
---

## Your Content Starts Here
Write your article body here...

```



### 3. Content Requirements

* **Images:** Place images in the `public/blog/` folder and reference them using `/blog/your-image.jpg`.
* **Tone:** Technical but accessible. We are building for everyone from beginners to pros.
* **Code:** Use triple backticks (```) for code blocks to enable syntax highlighting.
* **Code Blocks:** Always include the language (e.g., ````solidity` or ````typescript`).
* **Flare Network Specs:** If referencing RPCs, specify if you are using **Mainnet**, **Coston**, or **Coston2**.





##  Pre-Submission Checklist

Before submitting your Pull Request, ensure:

1. [ ] You have run `npm run build` locally to check for build errors.
2. [ ] Your description is between 50 and 160 characters (for SEO).
3. [ ] You have included your name in the `author` field.
4. [ ] All code snippets are tested on-chain (if applicable).



##  The Review Process

1. **CI Check:** Our GitHub Action will automatically run an **SEO Audit**. If it fails, please check the logs and update your metadata.
2. **Technical Review:** A maintainer will review the code logic for Flare Network compatibility.
3. **Merge:** Once approved, your post will be live at `flareafrica.xyz/blog/your-post`!




##  Local Development

If you want to see how your post looks before submitting, you can run the site locally:

1. **Install dependencies:**
```bash
npm install

```


2. **Start the development server:**
```bash
npm run dev

```


3. **View the site:**
Open `http://localhost:4321` in your browser.



##  Recognition

Once your PR is merged, you will:

* Be listed as an official **Author** on the website.
* Be featured across our **X (Twitter)** and **Telegram** channels.
* Contribute to the collective knowledge of the African Web3 ecosystem.

**Questions?** Join our community on [Telegram](https://t.me/+_y55Rvcl3fY1ODk0) or follow us on [X](https://x.com/FlareAfrica_) and ask the maintainers!












