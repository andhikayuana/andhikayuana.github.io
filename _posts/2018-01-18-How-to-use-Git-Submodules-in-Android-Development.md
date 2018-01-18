---
layout: post
title: How to use Git Submodules in Android Development
---

### Introduction

Last time, I was working with modular application and monorepo android project. I think it will be great if the repo is separated to some repo modules, not one repo with multiple module inside.

Currently I have one repo with some modules inside the repo.

### Car Gallery Application
  * App Module
  * Splash Screen Module
  * Auth Module
  * Data Module (SharedPreferences, Retrofit, SQLite)
  * Car Module (Create, Read, Update, Delete)

From above explanation about the repo, I need to refactor the code and separate the module to some repos and then the module can be reusable. So, You can use that module, eg. `Splash Screen Module` to another project you want.

### How to work with this flow ?

You can use `git submodule` command to manage like _adding, using, removing, updating_ the repo eg. `Splash Screen Module`.
You can read about `git submodule` at [this link](https://git-scm.com/docs/git-submodule)

### What do you need ?

  1. Laptop and Internet absolutely :smile:
  2. Latest [Android Studio and SDK](https://developer.android.com/studio/index.html?hl=id)
  3. [Git](https://git-scm.com/downloads)
  
### Are you ready to Rock :metal: ?

```java
//TODO
```
