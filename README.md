# ToDo: World Travel File Navigation

We're going to practice our command line file navigation skills by traveling around the world. Get your bags packed! We have a file structure representing the world that looks like this: 

![directories](https://curriculum-content.s3.amazonaws.com/KWK/cli-world-travel-directory-tree-sm.png)

[https://curriculum-content.s3.amazonaws.com/KWK/cli-world-travel-directory-tree.png](Larger version of directories)

### Refresher
You're going to be identifying the `cd` command to switch into different directories and travel around the geography tree. 

Let's quickly review absolute and relative file paths. If I'm currently in the directory called TORONTO and I want to move to another city inside Canada, OTTAWA, there are two ways I can do this:

**Absolute**, where we explicitly write the entire path to the directory where we're trying to go. An absolute path is a path that points to the same location on the file system regardless of the working directory. They start with / because that is the root of your file system.
```
cd /Earth/NorthAmerica/Canada/Ottawa
```

**Relative**, where we write the path based on our current working directory. A relative path is a path relative to the working directory of the user or application, so the full absolute path will not have to be given. They start with the name of a directory or a file.
```
cd ../Ottawa
```
Remember that `..` is used to go up a level on the tree.

So if I wanted to use a relative path to go from Madrid to Peru, I would write:
```
cd ../../../SouthAmerica/Peru
```
(I use `..` three times in a row because I need to move up three levels before I can go down the tree.)

???

## Your Challenge

Write the commands for the following directory changes:

?: Mexico City to Caracas

(X) cd ../../../South_America/Venezuela/Caracas
( ) cd Earth/South_America/Caracas
( ) cd South_America/Venezuela/Caracas

?: Caracas to Europe

( ) cd ../Earth/Europe
( ) cd ../../Europe
(X) cd ../../../Europe

?: Europe to Africa

(X) cd ../Africa
( ) cd Africa
( ) cd ../../../Africa

?: Africa to Addis Ababa

( ) cd ~/Addis_Ababa
( ) cd Addis_Ababa
(X) cd Ethiopia/Addis_Ababa

?: Addis Ababa to Rome

(X) cd ../../../Europe/Italy/Rome
( ) cd Europe/Italy/Rome
( ) cd Earth/Italy/Rome

?: Rome to Windhoek

( ) cd ../Namibia/Windhoek
(X) cd ../../../Africa/Namibia/Windhoek
( ) cd Earth/Africa/Namibia/Windhoek

?: Windhoek to Brazilia

(X) cd ../../../South_America/Brazil/Brazilia
( ) cd ../../South_America/Brazil/Brazilia
( ) cd ../../Earth/Brazilia

?: Brazilia to Mexico City to Italy to Beijing

( ) cd Earth/Mexcio_City/Beijing/Italy
( ) cd ../../Mexico/Italy/Beijing
(X) cd ../../../NorthAmerica/Mexico/MexicoCity/../../Europe/Italy/../../Asia/China/Beijing

???

