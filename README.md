# Utility Shell Scripts
A number of shell scripts you can use to achieve basic and common tasks.

These are basic timesaving scripts I use all the time and they were borne out of the need to be more efficient.
Many times, I have to create new projects from the scratch either to try out a new concept, or teach something.
I decided to write a script to automate this. also, I have added other time saving scripts.

If you are anything like me, then you might find a couple of these useful.

---

## Contents
+ changextension
+ numguess
+ quickstart
+ note


### changextension
A script that allows you change the extensions of all files in a directory, with a particular extension.

Say you have a directory that contains 50 `.txt` files and you want to change their extensions to `.json`or something else.
I can't imagine attempting to do that manually. Save yourself the headache, that's exactly why this script exists.

+ To use, simply switch to the directory containing the files and type:

```bash
changextension <current-extension> <target-extension>
```

+ Example Usage 

```bash
changextension txt json
```


### numguess
A simple fun game in the command line where a random number is generated by the computer and you are expected to guess what the number is.

You get perks for how fast you are able to guess the number ;)

+ Usage: 

```bash
numguess
```


### quickstart
A bash script that helps you quickly create standard project structures and allow you focus on development.

Supported projects are:
+ Express Js
+ Flask

*Support for more programming frameworks would be added soon*

+ Usage:

```bash
quickstart <project-stack> <project-name>
```

+ Example:

```bash
quickstart express mySuperAwesomeProject
```


### note
Who says you have to leave the convenience of your command line to take quick notes ?
You can easily take notes from the command line using this script.
+ Currently, all notes are stored to a notes.txt file in your home directory.
+ This is still a work in progress and the next update would allow you specify where notes should be stored.

+ To save a note, simply type:

```bash
note
```

+ To retrieve all your notes, type: 

```bash
note list
```


---

Please feel free to contribute to this repository.
Ideas, feedbacks and contributions are much welcome.