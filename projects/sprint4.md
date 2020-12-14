---
title: stackoverflow-cli
layout: page
---


<div align="center">
	<b>Search any query on Stack Overflow without leaving your IDE</b>
	<br>
	<img src="https://img.shields.io/npm/v/cli-stackoverflow?color=%23f48024" alt="version">
	<img src="https://img.shields.io/npm/dt/cli-stackoverflow?color=f48024" alt="downloads">
	<img src="https://img.shields.io/npm/l/cli-stackoverflow?color=f48024" alt="license">
</div>

# 💥 stackoverflow-cli

- Search any query inside your terminal
- Top 10 threads
- Order the results in ascending/descending order
- Sort the results via relevance/votes/activity/creation

## ↓ INSTALL

```sh
# install the cli globally
npm i -g cli-stackoverflow

# use it via npx
npx cli-stackoverflow
```

## ⚡️ USAGE

You can run the CLI by executing the following commands inside the terminal:

```sh
stack
```

### 📃 Guide

- <kbd>Right →</kbd> key – Next thread
- <kbd>Left ←</kbd> key – Prev thread
- <kbd>Up ↑</kbd> key – Next Answer
- <kbd>Down ↓</kbd> key – Prev Answer

### 🏳 Flags

```sh
# CLI help
stack --help
```

```sh
# Order results in ascending order
stack --asc

# Sort results according to the most activity
stack --activity

# Sort results according to  votes
stack --votes

# Sort results according to the creation
stack --creation
```

## 👨🏻‍💻 Teammates

I are from Pod 1.1.0.

- [Saad Irfan](https://github.com/msaaddev)
- [Aneesh Kodali](https://github.com/aneeshkodali)
- [Angelina Gasharova](https://github.com/angelinag)

## How I built it

I used Node.js to bring this CLI to life. I also used several open-source packages available on npmjs.com to implement certain functionalities. While building this CLI, I made sure the CLI has the following characteristics:

- Clean user interface
- Great user experience
- Easy to use

## Challenges I ran into

None of us had previous experience with writing tests. So it was one of the blockers for us. Also, it was quite difficult to implement navigation between threads and answers.

## Accomplishments that I proud of

I are proud of the following:

- Have a production-ready MVP that is published on npmjs.com
- Figuring out how to implement the navigation functionalities in terminal
- The tests I wrote
- Cleaning the API result body that had a lot of irrelevant stuff

## What I learned

Working with Node.js to build CLIs are quite easy. So I learned how to build a production-ready CLIs in Node.js and then how to publish them on npmjs.

## What's next for stackoverflow-cli

I are open for suggestions and would love some constructive criticism.
