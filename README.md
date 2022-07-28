<div align="center">

# Hephaestus

<img src="https://static.wikia.nocookie.net/godofhighschool/images/c/c8/Hephaestus_2.jpg" alt="logo" width="25%" />

<i>Hephaestus from God of Highschool</i>

**Hephaestus - R.A.T Forger: completely setup R.A.T + host it on heroku with a single Java console application.**

![](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)
![](https://img.shields.io/github/downloads/DxxxxY/Hephaestus/total?style=for-the-badge)

</div>

## [Demo](https://youtu.be/R-F2dygIOZg)
Notes:
- You can find the built mod in `%AppData%/Hephaestus/build/libs/`

- Heroku error handling isn't done yet. What this means is:
    - When entering a name for the Heroku app, make sure it is something that **shouldn't already exist**. It does not check for it, but will throw an error farther down the line.
    - You also have to make sure that you have **less than 5** Heroku apps as that is the limit.
    > If deploying to Heroku doesn't take a while (if it's quick), then you probably messed up there.


## Features
- Clean, simple and easy to use menu.
- Synchronous command execution.
- Always up-to-date R.A.T (pulls from Git repository).
- Partial error handling (external processes).
- Uses:
    - *JGit* for Git commands.
    - *Gradle Tooling API* for Gradle controls.

## Pre-requirements
- [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) (after you install login yourself using `heroku login`)
- [Git](https://git-scm.com/)

## Download
Setup and build yourself.

**or**

Download from [Releases](https://github.com/DxxxxY/Hephaestus/releases) and execute with `java -jar Hephaestus-1.0-SNAPSHOT.jar`.

## Disclaimer
This is for educational purposes only. I am not responsible for any damage caused by this tool.

## License
GPLv3 © dxxxxy