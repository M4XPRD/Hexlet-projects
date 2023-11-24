# Hexlet Projects

  1. [Brain Games](#bg)
    * [Description](#bg-desc)
    * [Installation](#bg-inst)
    * [Commands](#bg-com)
    * [Demonstration](#bg-demo)

  2. [Difference Calculator](#dc)
    * [Description](#dc-desc)
    * [Installation](#dc-inst)
    * [Commands](#dc-com)
    * [Demonstration](#dc-demo)

  3. [RSS Reader](#rss)
    * [Description](#rss-desc)
    * [Installation](#rss-inst)
    * [Demonstration](#rss-demo)

  4. [Online Chat](#chat)
    * [Description](#chat-desc)
    * [Installation](#chat-inst)
    * [Demonstration](#chat-demo)

## Brain Games
<a name="bg"></a>

## Hexlet tests, CodeClimate check and linter status:
[![Actions Status](https://github.com/M4XPRD/frontend-project-lvl1/workflows/hexlet-check/badge.svg)](https://github.com/M4XPRD/frontend-project-lvl1/actions)
[![linter-check](https://github.com/M4XPRD/frontend-project-lvl1/actions/workflows/linter-check.yml/badge.svg)](https://github.com/M4XPRD/frontend-project-lvl1/actions/workflows/linter-check.yml)
[![Maintainability](https://api.codeclimate.com/v1/badges/021cbf28f84e6d29945d/maintainability)](https://codeclimate.com/github/M4XPRD/frontend-project-lvl1/maintainability)

## What is this all about?
<a name="bg-desc"></a>

«Brain games» is a set of 5 different games which are similar to popular mobile applications for brain pumping. Each game asks questions that need to be answered correctly. 

The game is finished, if you answer correctly three times in a row. If the answer is wrong the game stops, and you'll have a message asking to try to play again once more. The list of games:


**• Calculator.** It's about arithmetic expressions that need to be calculated.

**• Progression.** It's about finding missing numbers in a sequence of numbers.

**• Determining an even number.**

**• Determining the greatest common divisor.**

**• Determining a prime number.**

## Installation
<a name="bg-inst"></a>

To run this game make sure you have [Node.js v.16.8.0](https://nodejs.org/en/) or later.

Here's the quick guide, if everything is set up:

```sh
# Step 1 — clone my repository
$ git clone https://github.com/M4XPRD/frontend-project-lvl1.git

# Step 2 — proceed to my folder
$ cd frontend-project-lvl1

# Step 3 — install the dependencies
$ make install

# Step 4 — install the packages
$ sudo npm link

# Step 5 — use the special command to run the game
$ brain-games
```

The list of all commands:
<a name="bg-com"></a>

```sh
#This first command just welcomes you
$ brain-games

#These 5 commands below start the actual games
$ brain-calc

$ brain-progression

$ brain-even

$ brain-gcd

$ brain-prime

```
## Games demonstarions via asciinema:
<a name="bg-demo"></a>

• **Calculator**: use ***brain-calc*** command 

[![asciicast](https://asciinema.org/a/445228.svg)](https://asciinema.org/a/445228)

• **Progression**: use ***brain-progression*** command

[![asciicast](https://asciinema.org/a/446259.svg)](https://asciinema.org/a/446259)

• **Determining an even number**: use ***brain-even*** command

[![asciicast](https://asciinema.org/a/444554.svg)](https://asciinema.org/a/444554)

• **Determining the greatest common divisor**: use ***brain-gcd*** command

[![asciicast](https://asciinema.org/a/445356.svg)](https://asciinema.org/a/445356)

• **Determining of a prime number**: use ***brain-prime*** command

[![asciicast](https://asciinema.org/a/446284.svg)](https://asciinema.org/a/446284)


## Difference Calculator
<a name="dc"></a>

## Hexlet tests, CodeClimate check and linter status:

[![Actions Status](https://github.com/M4XPRD/frontend-project-lvl2/workflows/hexlet-check/badge.svg)](https://github.com/M4XPRD/frontend-project-lvl2/actions)
[![project-check](https://github.com/M4XPRD/frontend-project-lvl2/actions/workflows/project-check.yml/badge.svg)](https://github.com/M4XPRD/frontend-project-lvl2/actions/workflows/project-check.yml)
[![Maintainability](https://api.codeclimate.com/v1/badges/fb5424cb2db36a0fee0b/maintainability)](https://codeclimate.com/github/M4XPRD/frontend-project-lvl2/maintainability)
[![Test Coverage](https://api.codeclimate.com/v1/badges/fb5424cb2db36a0fee0b/test_coverage)](https://codeclimate.com/github/M4XPRD/frontend-project-lvl2/test_coverage)

## Description:
<a name="dc-desc"></a>

This is the utility, which shows the difference between two files. The output can be shown with different formats.
<br></br>
**List of supported extensions:**

• JSON (```.json``` file extension)

• YML/YAML (```.yml```or ```.yaml``` file extensions)
<br></br>
**List of output formats:**

• ```stylish``` is standart format, which will show the difference between files with ```+``` and ```-``` signs.

• ```plain``` is human-readable variant, where you can see the string-like output of each line, that has any changes. 

• ```json``` is variant, which is similar to *stylish*. But instead of ```+``` and ```-``` you will see AST-tree-like system with statuses of *keys* and their *types*.

## Installation:
<a name="dc-inst"></a>

```sh

# Step 1 — clone this repository
$ git clone https://github.com/M4XPRD/frontend-project-lvl2

# Step 2 — install the dependencies
$ make install

# Step 3 — install the packages
$ sudo npm link
```
## List of commands in terminal:
<a name="dc-com"></a>

**Important note** — in order to use this utility correctly, you should move to ***__fixtures__*** folder in terminal, where you can upload and use your files. 

```sh
# Help window
gendiff -h

# All commands below should run from __fixtures__ folder!

# Show difference with standart (stylish) format
gendiff file1.json file2.json

# Show difference with stylish format
gendiff --format stylish file1.json file2.json

# Show difference with plain format
gendiff --format plain file1.json file2.json

# Show difference with json format
gendiff --format json file1.json file2.json
```

## Project demonstarions via asciinema:
<a name="dc-demo"></a>

## Difference between two flat JSON files:
[![asciicast](https://asciinema.org/a/469841.svg)](https://asciinema.org/a/469841)

## Difference between two flat YML / YAML files:
[![asciicast](https://asciinema.org/a/470085.svg)](https://asciinema.org/a/470085)

## Difference between two nested files (stylish format):
[![asciicast](https://asciinema.org/a/473862.svg)](https://asciinema.org/a/473862)

## Difference between two nested files (plain format):
[![asciicast](https://asciinema.org/a/474906.svg)](https://asciinema.org/a/474906)

## Difference between two nested files (json format):
[![asciicast](https://asciinema.org/a/474928.svg)](https://asciinema.org/a/474928)


## RSS Reader
<a name="rss"></a>

## Hexlet tests and linter status:
[![Actions Status](https://github.com/M4XPRD/frontend-project-lvl3/workflows/hexlet-check/badge.svg)](https://github.com/M4XPRD/frontend-project-lvl3/actions)
[![pages-build-deployment](https://github.com/M4XPRD/frontend-project-lvl3/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/M4XPRD/frontend-project-lvl3/actions/workflows/pages/pages-build-deployment)
[![Maintainability](https://api.codeclimate.com/v1/badges/c99e1ba900628cc47e44/maintainability)](https://codeclimate.com/github/M4XPRD/frontend-project-lvl3/maintainability)

## Description:
<a name="rss-desc"></a>

[RSS Reader](https://frontend-project-lvl3-m4xprd.vercel.app/) is a service for aggregating RSS feeds that makes it easy to read a variety of sources, such as blogs or your favourite news. It allows you to add an unlimited number of RSS feeds, update them and add new entries to the whole stream.

**How to use it:**

• Find a blog or news feed, which you prefer to read

• Use `link-to-RSS` converters to make your blog/news link suitable for [RSS Reader](https://frontend-project-lvl3-m4xprd.vercel.app/)

• Make sure the link is a file with `.xml` markup

• Add this link to the feed

• If you need to change the language, press `RU/EN` button in the upper-right corner

• All downloaded feeds would constantly update every 5 seconds, so you won't miss anything 👀

• That's it!

## Installation:
<a name="rss-inst"></a>

```sh

# Step 1 — clone this repository
$ git clone https://github.com/M4XPRD/frontend-project-lvl3

# Step 2 — install the dependencies
$ make install

# Step 3 — install the packages
$ sudo npm link

# Step 4 — make new bundle using production mode
$ make production
```
## How it looks:
<a name="rss-demo"></a>

![Screenshot_1](https://user-images.githubusercontent.com/86636158/202023130-bd67d861-1926-42fa-ab3f-40ee6d6e34ff.png)
![Screenshot_2](https://user-images.githubusercontent.com/86636158/202023164-4370504f-b041-47ca-9b28-9d0da4796c7d.png)
![Screenshot_3](https://user-images.githubusercontent.com/86636158/202023171-7d2daec8-5d56-4c0d-b4fa-2acfe0162b4f.png)
![Screenshot_4](https://user-images.githubusercontent.com/86636158/202027161-071d1273-73bf-4374-b353-2243f92c8c80.png)

## Online Chat
<a name="chat-demo"></a>

## Hexlet tests and CodeClimate maintainability:
[![Actions Status](https://github.com/M4XPRD/frontend-project-12/workflows/hexlet-check/badge.svg)](https://github.com/M4XPRD/frontend-project-12/actions)
[![Maintainability](https://api.codeclimate.com/v1/badges/bb97a743b480a4c418c4/maintainability)](https://codeclimate.com/github/M4XPRD/frontend-project-12/maintainability)

## Description:
<a name="chat-desc"></a>

[Hexlet Chat](https://bit.ly/project4-m4xprd) is very simplified Slack-like real-time chat app built with React/Redux, AJAX, REST, websockets, React (with Hooks), Redux (@reduxjs/toolkit) and Formik.

## Features:

• Chat supports two languages to choose from: `Russian` and `English`. Just find a flag icon above in the top section

• You can send messages and manage channels (except `'general'` and `'random'`)

• You won't miss anything with fly-off notifications, which appear from the right

• Chat will always tell you, if you're lack with network connection

• Profanity filter included!

## Installation:
<a name="chat-installation"></a>


```sh
All commands should run from root:

# Step 1 — Clone this repository
$ https://github.com/M4XPRD/frontend-project-12

# Step 2 — Install the dependencies
$ make install

# Step 3 — Install the packages
$ sudo npm link

# Step 4 — Start frontend and backend in root folder
$ make start
```

```sh
# If Step 4 didn't work — use an alternative way:

# Step 5 — Initialize frontend in the first terminal
$ cd frontend && make start

# Step 6 — Initialize backend in the second terminal
$ make start-backend
```
## How it looks:
<a name="chat-demo"></a>

![1](https://user-images.githubusercontent.com/86636158/228425143-d3e0077b-e84e-4a0d-abd2-bfb70e136014.png)
![4](https://user-images.githubusercontent.com/86636158/228425438-1acbcd7f-5a9b-4acc-bee9-042a04d4df76.png)
![2](https://user-images.githubusercontent.com/86636158/228425147-476acc1c-da7f-482f-99c7-73b8633fc9d6.png)
![3](https://user-images.githubusercontent.com/86636158/228425152-6be5733f-cb5c-4b60-82cd-3144f7ba6623.png)
![5](https://user-images.githubusercontent.com/86636158/228425180-00615a2f-3c7f-415f-ae55-4bfbd15e5cc0.png)
![6](https://user-images.githubusercontent.com/86636158/228425184-5a050f1e-77e9-444e-a98f-6f2fb5c045d7.png)
