# IDE Setup

This guide will assume you are using IntelliJ IDEA as your main Java IDE. At Minerift, we follow the IDEA module pattern directory schema, which means every Java project on GitHub is a module on a project you create. This way, you don't have to keep opening and closing projects, which takes a while when you have more than 10 modules.

## How do I get a project?

Go to the GitHub project page, copy the Git clone (the `git` SSH protocol is preferred), open a terminal, `cd` to your project root directory and run the following:

```bash
git clone git@github.com:Minerift-Network/<Project Name>.git Directory_Name/
```

Name your modules appropiately, as changing them in the future is a pain. Once you have cloned it, go to IntelliJ, click on File -> New -> Module from Existing Sources...

![IntelliJ IDEA](https://i.imgur.com/gDNtWE0.png)

Finally, select the `Directory_Name/` that you just using `git clone`, click OK and then just spam the `Next` button until you're done.