# Homework 2

In your home directory, make a folder called `Development`, if it doesn't exist. This is where we will keep all of the code for the class. Next, make sure that you are inside that folder, by checking the output of the following command:

```shell
pwd
```

If `pwd` shows that you are in a different directory, run `cd ~/Development` and check with `pwd` again.

## How to clone this repo

Next, clone this repository by clicking the green button in the upper right corner, selecting `SSH` and copying the string that looks like `git@github.com:code4policy/<REPO-NAME>.git` (`<REPO-NAME>` will be the name of your repository). Then, in the terminal run the following:

```
git clone git@github.com:code4policy/<REPO-NAME>.git
```

Note that by default, git will clone the repository into a folder with name `<REPO-NAME>`. After the repo is cloned, open that directory (use `cd`).


## Tasks

1. Insider your repository, create the following structure of files and folders.

    ```
    .
    └── solar_system
        ├── planets
        │   ├── asteroid_belt.txt
        │   ├── earth
        │   │   └── continents
        │   │       ├── africa.txt
        │   │       ├── antarctica.txt
        │   │       ├── asia.txt
        │   │       ├── australia.txt
        │   │       ├── europe.txt
        │   │       ├── north_america
        │   │       │   └── countries
        │   │       │       ├── canada.txt
        │   │       │       ├── mexico.txt
        │   │       │       └── united_states.txt
        │   │       └── south_america.txt
        │   ├── jupiter.txt
        │   ├── mars.txt
        │   ├── mercury.txt
        │   ├── neptune.txt
        │   ├── pluto.txt
        │   ├── saturn.txt
        │   ├── uranus.txt
        │   └── venus.txt
        └── stars
            └── sun.txt

    7 directories, 19 files
    ```

2. Delete asteroid belt, since that isn't a planet.

3. Move `pluto.txt` to a folder called `other`.

4. The file `expected_results.txt` shows the desired file/folder structure.
