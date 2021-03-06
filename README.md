## #9-cli-good-readme-generator
![Project license](https://img.shields.io/badge/license-MIT,https://choosealicense.com/licenses/mit/-brightgreen)

<h3>READ ME Generator executed via Command Line Interface (CLI) in Terminal.</h3>
<p>Github Repository Page: https://github.com/palowenstein/cli-good-readme-generator</p>
<p>Github Deployment Page: N/A - App is to be executed in Terminal via CLI.</p>

# Table of Contents
  * [GIF](#Gif)
  * [Overview](#Overview)
  * [Details](#Details)
  * [Instructions](#Instructions)
  * [Screenshots](#Screenshots)
  * [Video](#Video)
  * [References](#References)
  * [License](#License)
  * [Contact](#Contact)

## GIF
![CLI Good Read Me Generator (GIF)](./demo_assets/9-cli-good-read-me-generator-demo.gif "CLI Good Read Me Generator (GIF)")

## Overview
<ul>
<li>Read Me Generator executed in Terminal via (CLI) Command Line Interface.</li>
<li>Application behaves accordingly to standard ("good") practices and dynamically generates a professional README markdown file.</li>
<li>User is prompted to respond to each question, one at a time.</li>
<li>All questions are answered via a character string except for the licence, which is choice driven.</li>
<li>The goal of the application is its simplicity of use and its overall time saving for the final user.</li>
</ul>

## Details
<ul>
<li>A .gitignore file is present at the root level to prevent the upload of node_modules, .DS_Store.</li>
<li>The included package.json file includes all dependencies if the user wants to run 'npm install' instead of the instructions below</li>
</ul>

## Instructions
<ul>
<li>In Terminal, locate the application folder and enter into it via the 'cd' command: cd hw9-cli-good-readme-generator</li>
<li>Run the 'npm init' command to fill the package json with the application information (screenshot #1).
<li>Run the 'npm inquirer' to install the inquirer dependencies (screenshot #2).</li>
<li>Run the 'node index.js' command to start the application in Terminal (GIF/MP4).</li>
<li>While still in Terminal, answer the following prompts (GIF/MP4):
    <ol>
    <li>GitHub Username</li>
    <li>E-Mail</li>
    <li>Title</li>
    <li>Description</li>
    <li>Licence</li>
    <li>Installation</li>
    <li>Tests</li>
    <li>Usage</li>
    <li>Contributions</li>
    </ol>
<li>Once all questions have been answered, a "README — Title (based on the title entered).md" will be generated in the application folder (screenshot #3).</li>
</ul>

<p><i>Refer to index.js (javascript file) for code dissection.</i></p>

## Screenshots
![CLI Good Read Me Generator (Screenshot #1: npm init)](./demo_assets/9-1-cli-good-read-me-generator-npm-init.jpg?raw=true "CLI Good Read Me Generator (Screenshot #1: npm init)")
<h6>CLI Good Read Me Generator (Screenshot #1: npm init)</h6>
<br />

![CLI Good Read Me Generator (Screenshot #2: npm install inquirer)](./demo_assets/9-2-cli-good-read-me-generator-npm-install-inquirer.jpg?raw=true "CLI Good Read Me Generator (Screenshot #2: npm install inquirer)")
<h6>CLI Good Read Me Generator (Screenshot #2: npm install inquirer)</h6>
<br />

![CLI Good Read Me Generator (Screenshot #3: Read Me Markdown generated from user input)](./demo_assets/9-4-cli-good-read-me-generator-generated-read-me-markdown.jpg?raw=true "CLI Good Read Me Generator (Screenshot #3: Generated Read Me Markdown)")
<h6>CLI Good Read Me Generator (Screenshot #3: Generated Read Me Markdown)</h6>
<br />

## Video
![CLI Good Read Me Generator Prompt Flow (MP4)](./demo_assets/9-cli-good-read-me-generator-demo.mp4 "CLI Good Read Me Generator Prompt Flow (MP4)")
<h6>CLI Good Read Me Generator Prompt Flow (MP4)</h6>
<br />

## References
<ul>
<li>Node.js</li>
<li>Javascript</li>
<li>Inquirer</li>
<li>ES6+</li>
<li>Axios (optional - for GitHub username verification)</li>
</ul>

 ## License
<p>
<a href="./MITlicense.txt">MIT License</a> | Copyright © [2020] Pierre André Lowenstein
</p>

 ## Contact
<p>
<a href="https://pierreandrelowenstein.com" title="[www] Pierre Andr&eacute; Lowenstein" target="_blank">[www] pierreandrelowenstein.com</a>
&nbsp;|&nbsp;
<a href="mailto:coder@pierreandrelowenstein.com" title="Courriel">Send me a 'courriel'</a>
</p>