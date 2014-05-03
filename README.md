Snippets
========

The following is a collection of useful code and command line snippets that I use fairly often. Know of a few things you use pretty often? Commit it! Pull requests are welcome!

### [Windows](http://windows.microsoft.com/en-au/windows/home)

* Symlink

> Symlinking something creates a reference to a file in another location, as if it were a direct file. Similar to a shortcut.

```ln -s path/to/target path/to/link```

* Shell
> Executes a shell script using windows

``` sh path/to/script```

### [Android](http://developer.android.com/)

* List android targets

> Lists the available android API versions

```android list targets```

* Create an android project

> The appropriate command to create a new android project from the command line

```android create project --target <target-id> --name MyFirstApp \
--path <path-to-workspace>/MyFirstApp --activity MainActivity \
--package com.example.myfirstapp```

### [Git](http://git-scm.com/)

* Git Stripspace

> Strips trailing whitespace, collapses newlines, adds a final newline, deals with horrible contributors/co-workers.

```git stripspace (file)```

* Diff Check

```git diff --check```

* Abort Merge

> Aborts a broken branch merge

```git merge --abort```

* Git merge message

> Like commit -m, but populates the merge commit

```git merge -m "Message"```

### [Maven](http://maven.apache.org)

* Maven clean install

> Cleans and compiles a maven project

```mvn clean install```

* Maven clean install -U

> Cleans and compiles a maven project, and updates dependencies

```mvn clean install -U```

* Maven compile

> Compiles a Maven project

```mvn compile```

* Maven clean

> Removes the target directory

```mvn clean```

* Maven IDEA idea

> Regenerates IntelliJ IDEA settings (project.iml)

```mvn idea:idea```

### [RubyGems](http://rubygems.org)

* Install Gems from a GemFile

> Installs all the Gems for a project listed in a Gemfile

```bundle install```

* Start a new Dashing Server

> Starts a new server instance of a dashing project on http://localhost:3030

```dashing start```

* Create a new Jekyll site

> Creates a new static site using Jekyll

```jekyll new <site directory/name>```

* Serve up a jekyll site

> Serves a new server instance of a jekyll site on http://localhost:4000

```jekyll serve```

### [NodeJS](http://nodejs.org/)

* Initialise a new Node server

> Initialises a new Node server using a JavaScript file

```node <file.js>```

* Install a node dependency

> Installs a new dependency for a project using NodeJS

```npm install <dependency name>```

### [MongoDB](http://www.mongodb.org/)

* Show Databases

> Displays a list of databases

```show dbs```

* Use a Database

> Sets the Active Database

```use <database name>```

* Insert a Document

> Inserts a document into a collection. In this case, everything between the curly brackets ```{}``` is a new document

```db.<collection name>.insert({name: 'psgs', age: 32, languages: ['java', 'javascript', 'ruby']});

* List Data from a Collection

> Lists data contained in a certain collection. The data shown can be filtered using the find() parameter

```db.<collection name>.find()```