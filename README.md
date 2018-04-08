
# Readrust

A simple command line tool written in Rust to get articles from https://readrust.net

  

[![Build Status](https://travis-ci.org/PenetratingShot/readrust.svg?branch=master)](https://travis-ci.org/PenetratingShot/readrust)

  

## General Info

**Name:** ReadRust

**Version:** 1.0.2-beta.3

**Author:** PenetratingShot


## Documentation

### Installation

<dl>
	<dt><b>1. Clone the repository</b></dt>
	<dd>$ git clone <a>https://github.com/PenetratingShot/readrust.git</a></dd>
</dl>
  
<dl>
	<dt><b>2. Navigate to the directory</b></dt>
	 <dd>Go to the path `./target/release/readrust`</dd>
</dl>
  
<dl>
	<dt><b>3. Run the script.</b></dt>
	<dd>Double click on the file and select you command prompt as the application to open it. Once it says `[Process Completed]`, you may close the tab.</dd>
</dl>

<dl>
	<dt><b>4. Open a new command prompt tab</b></dt>
	<dd>Open a new tab or instance of you local command prompt and try running the command: <em>readrust -h</em> or <em>readrust --help</em></dd>
</dl>
  
  ***

### Usage

  

***Note*:** You may NOT combine different flags together. They are meant to be used individually for the time being. Attempting to do so will return the output for the first flag and ignore the second.

| Flag | Alias | Usage |
|:-------:|:------:|:------|
| ––help | –h | Prints help information |
| ––about | –a | About the project |
| --version | –v | Prints version information
| ––count | –c | Show the count of posts |
| ––devops | –d | Feed from DevOps and Deployment |
| ––performance | –p | Feed from Performance |
| --rust2018 | –r | Feed from Rust2018 |


**Example Function:**  `$ readrust --devops`

This command will return the feed from the devops section on [readrust](https://readrust.net)
****
### License
[Readrust](https://github.com/PenetratingShot/readrust.git) is licensed under the [MIT License](https://github.com/PenetratingShot/readrust/blob/master/LICENSE)
***
