# Tanzim's Github Repository

## Interest Site - Houston Rockets
### Description
I chose to focus my Interest site on the trials and tribulations of the Houston Rockets NBA team, which spectacularly flopped this year. It is important to note that many of the included links are a couple months old, and we have just entered Free Agency as of Friday, November 20, 2020. This means that some information on the page is subject to change.
### How to Build the Interest Site


1) Download the project folder
2) Install [node](https://nodejs.org/en/download/) 
3) Within the project folder, install the fs and ejs packages in the terminal with the following command lines: 


```bash
npm install fs --save
```
and

```bash
npm install ejs --save
```
4) Next, install LESS to allow CSS abstractions with the following command line

```bash
npm install less --save
```

5) With all the proper packages installed, begin compiling the pages by creating the styles.css file using LESS with the following command line:

```bash
./node_modules/less/bin/lessc ./LESS/styles.less ./build/css/styles.css
```

6) Once the styles.css is created, generate the blogs, about and index pages by running the blogAssembly.js file through Node with the following command line:

```bash
node blogAssembly.js
```
7) Now that all the files are generated, open the index.html page and feel free to browse.
