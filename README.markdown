# scala.heroku.g8

[![Scala CI](https://github.com/alessandrocandolini/scala.heroku.g8/actions/workflows/scala.yml/badge.svg)](https://github.com/alessandrocandolini/scala.heroku.g8/actions/workflows/scala.yml)


A [Giter8][g8] template for generating a scala3 / typelevel stack project ready to be deployed on Heroku using github actions 

## Usage 

Interactively via sbt: 

```
sbt new alessandrocandolini/scala.heroku.g8
```

Not interactively via sbt:
```
sbt new alessandrocandolini/scala.heroku.g8  --branch=main --name="my_project"
```

Alternatively, using `g8`
```
g8 alessandrocandolini/scala.heroku.g8  --branch=main --name="my_project"
```


Template license
----------------
Written in 2022 by A. Candolini <alessandro.candolini@gmail.com>

To the extent possible under law, the author(s) have dedicated all copyright and related
and neighboring rights to this template to the public domain worldwide.
This template is distributed without any warranty. See <http://creativecommons.org/publicdomain/zero/1.0/>.

[g8]: http://www.foundweekends.org/giter8/
