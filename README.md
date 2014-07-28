# RubySteps

Welcome to the RubySteps project. Here you will find all the lessons that you
have access to. You can run each lesson on a vagrant virtual machine which contains all
the software necessary to run the lesson.

## Easy as 1, 2, 3(-ish)

The basic steps to setting up the RubySteps environment are to install vagrant
and virtualbox, then clone the RubySteps source code and launch the box.

1. [Download and install VirtualBox](https://www.virtualbox.org/wiki/Downloads)
2. [Download and install Vagrant](https://docs.vagrantup.com/v2/installation/index.html)
3. Clone the RubySteps and launch the box

```
git clone git@lab.patmaddox.com:pat/rubysteps.git
cd rubysteps
vagrant up
```

After launching the vagrant environment, you can ssh into it with `vagrant
ssh`. Once inside, run `ruby hello.rb` to verify that you have a working
environment. You should see the text "Hello RubySteps".

### The ish

If you don't have git installed, you can install it with
[these instructions](https://help.github.com/articles/set-up-git). You only need
to do the "Setting Up Git" section - the "Next steps" section don't apply to
RubySteps. You certainly can celebrate if you want though :)

If you have no idea what the git / cd / vagrant lines are about, don't
worry. They're commands that programmers use to interact with the
computer. You'll learn the standard ones over time. For now, take some time to
learn how to launch your terminal and enter commands, like the ones above.

## Lessons

Lessons will appear in the lessons/ directory. I will send out emails when new
lessons are released. You can always `git pull` in order to fetch the latest
updates.
