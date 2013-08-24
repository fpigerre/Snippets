Snippets
========

The following is a collection of useful code and command line snippets that I use fairly often. Know of a few things you use pretty often? Commit it! Pull requests are welcome!

### Windows

#### Symlink
Symlinking something creates a reference to a file in another location, as if it were a direct file. Similar to a shortcut.

```ln -s path/to/target path/to/link```

### Android

# List android targets
Lists the available android API versions

```android list targets```

#### Create an android project
The appropriate command to create a new android project from the command line
```android create project --target <target-id> --name MyFirstApp \
--path <path-to-workspace>/MyFirstApp --activity MainActivity \
--package com.example.myfirstapp```

### Git

#### Git Stripspace
Strips trailing whitespace, collapses newlines, adds a final newline, deals with horrible contributors/co-workers.

```git stripspace (file)```

#### Diff Check

```git diff --check```

#### Abort Merge
Aborts a broken branch merge

```git merge --abort```

#### Git merge message
Like commit -m, but populates the merge commit

```git merge -m "Message"```

### Maven

#### Maven clean install
Cleans and compiles a maven project

```mvn clean install```

#### Maven clean install -U
Cleans and compiles a maven project, and updates dependencies

```mvn clean install -U```

#### Maven compile
Compiles a Maven project

```mvn compile```

#### Maven clean
Removes the target directory

```mvn clean```

#### Maven IDEA idea
Regenerates IntelliJ IDEA settings (project.iml)

```mvn idea:idea```
