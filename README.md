# LearnGitBranching

LearnGitBranching is a pseudo-git sandbox and interactive series of tutorials / challenges to accelerate the understanding of how git commit trees work. The ideal audience is a complete newcomer to git, but a wide range of experience levels should be able to benefit from these tutorials.

It supports a fairly wide range of commands and dynamically visualizes the effects each change has on a commit tree visualization next to the command box:

<img src="https://raw.github.com/pcottle/learnGitBranching/master/assets/learnGitBranching.png"/>

You can see the demo here:
http://pcottle.github.com/learnGitBranching/?demo

or use the vanilla app here:
http://pcottle.github.com/learnGitBranching/

### Sandbox Mode

Sandbox mode is where you can mess around and just see what certain git commands do. It is moderately helpful, but the real magic lies in levels...

## Levels

Type `levels` to see the available levels. These are a mix of tutorials and challenges to introduce git concepts and get newcomers familiar with certain workflows. There is also a "git golf" concept that tracks how many commands you used to solve the level :P

### Level Builder

You can build levels with `build level`. The dialog should walk you through the majority of the commands -- at the end you will get a JSON blob that you can share with friends or paste into a Github issue.

### Contributing Levels

I would love for more levels to be added! I think there is a ton to learn and cover. Hopefully the community together can build a great tool for all git newcomers.

## Contributing

I am really loose about contributing levels. For contributing functionality, you will need to install the `grunt` build tool. The general steps:

```
git clone <your fork of the repo>
cd learnGitBranching
npm install
git checkout -b newAwesomeFeature
# some changes
grunt build
git commit -am "My new sweet feature!"
git push
# go online and request a pull
```

## Helpful Folks
A big shoutout to these brave souls for extensively testing our sandbox and finding bugs and/or inconsistencies:

* Nikita Kouevda
* Maksim Ioffe
* Dan Miller

Also huge shoutout for everyone who has put up a pull request

* Stephen Cavaliere
* Andrew Ardill
* Shao-Chung Chen
* Tobias Pfeiffer
* Luke Kysow
* Adam Brodzinski

And reported an issue that was successfully closed!

* Caspar Krieger
* Stuart Knightley
* John Gietzen
* Chris Greene
* "datton"
* Jaymes Bearden
* Jan-Erik Rediger

