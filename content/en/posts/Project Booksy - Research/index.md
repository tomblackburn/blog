---
title: Project Booksy - Research
date: 2025-01-27
author: Tom Blackburn
description: Diary of a project being built as part of the Boot.dev course
---

![Hero Image](https://images.unsplash.com/photo-1501504905252-473c47e087f8?q=80&w=1974&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)


# About Discord **🎧**

I've spent the majority of this morning diving deep into Discord! 🕵️‍♂️ They have a fascinating history and maintain a very transparent blog that details many of the technical decisions they've made during critical times in the company's development. For example, they discuss their choices around database technology 📊 and their decision to implement Rust 🦀 to help them scale efficiently.

If you're interested in checking out some of my research, here are a few useful links:

- [About Discord](https://tomblackburnblog.netlify.app/posts/discord-developer---about-discord/)]
- [Technology at Discord](https://tomblackburnblog.netlify.app/posts/discord-developer---technology/)]

# Popular Discord Apps **🚀**

Discord offers **thousands** of apps that can be invited to servers (also called Guilds). These range from games 🎮 and utilities 🛠️ to moderation 🛡️ and productivity tools. Discord even hosts its own [App Directory](https://discord.com/discovery/applications), which acts like a marketplace where users can browse different apps and get a brief understanding of what they do.

For instance, [MEE6](https://mee6.xyz/en), one of the most popular bots, is installed on more than **21 million** servers! 😲

While exploring, I looked for Book Club apps 📚 but surprisingly, I didn't find any that met my expectations. However, I did come across some apps that sparked a few exciting ideas:

- **📖 Book Reviews** – Members can provide book reviews and ratings, potentially linking them to popular platforms like Goodreads.
- **🔍 Recommendation System** – Personalized book suggestions based on members' unique preferences.
- **⏱️ Reading Sprints "Game"** – Fun challenges that encourage readers to reach new milestones.
- **👤 Custom Profiles** – Members can showcase their favorite books, authors, and genres to express their literary persona.

# Installing and Testing Apps **🛠️**

I installed several of these apps on a new test server I created. Some of the book-related apps were quite underwhelming 😞, which made me realize that I would need to carve my own path rather than rely on existing solutions. In a way, this is a positive thing – it allows me to think outside the box and create something truly unique. 🌟

## Support Discord Server **🔗**

One cool feature I noticed when executing the **/help** command was that many apps provide an invitation to join the developer's Discord support server. This is a nice touch and could be important if I decide to build and productionize my own bot. 👥

## Dashboards **📊**

Bigger, more established Discord apps often provide a dedicated dashboard website 🌐 to help users configure settings with a clean and intuitive interface. While this is convenient, I found that Discord's built-in features are more than enough to meet my current needs. Although not as visually appealing as a web dashboard, they should suffice for now, allowing me to focus more on bot development instead of creating a separate web app.

## Third Party Services **🔄**

A major downside of some book-related apps was their poor integration with third-party services 😕. I searched for popular books and received irrelevant or inaccurate results. For example, one app that supposedly used Google's Book API 📚 often failed to provide responses.

If I struggle with integrations like this, I might need to explore alternative services or even consider developing my own book database solution. Or use none at all and just don’t build the feature 🤔

# Conclusions 🍷

Honestly, this pretty quick research session into existing Discord apps felt like enough for me to get started on design and development.