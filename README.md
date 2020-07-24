# ognamesearcher
Tool to search for OG mojang accounts names that can be taken.
## Prerequisites
You need to have [node.js](https://nodejs.org/en/) installed on your pc
## Installation
Download the project and unzip it. Then open a terminal, naviguate inside the project folder and enter this command wich will install all the dependencies

```
npm install
```
## Usage
Once you correctly installed the project, run this command to launch the program with the base parameters
```
npm start
```
## Configuration
I don't have time to make a config file so its up to you to go in the `index.js` file and modify the variables.

`const timeBetweenRows = 10000` This variable sets the time between each row (in ms)

`const timeBetweenWords = 2000` This one sets the time between each word (in ms)

`const wordsPerRow = 60` This one sets the number of words per row
