# Two Gradle git-clone options

* [grgit](https://github.com/ajoberstar/grgit)
```
./gradlew -b checkout-grgit.gradle cloneSamples  # lib/samples 38M
```
* [palominolabs/gradle-git-clone-task](https://github.com/palominolabs/gradle-git-clone-task) - Latest commit 2016.08.27, 1 contributor
```
./gradlew -b checkout-palomino.gradle cloneSamples  # lib/samples
```

grgit is feature-rich, but needs more steps to checkout into existing repo, palominolabs' task is spartan and straight-forward.
