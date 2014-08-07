# Gradle Plugins

This is a collection of handy Gradle plugins which where originally forked from [this excellent repository](https://github.com/bradleybeddoes/gradle-plugins) by [Bruno de Carvalho](https://github.com/brunodecarvalho) that I intend to extend and add to over time.

## RSpec like test output

You'll end up with something like this:

![example output](https://www.dropbox.com/s/7arfxiq38nux99q/Screenshot%202014-08-07%2010.41.38.png)

### How to use

In your build.gradle file add the following, then run `gradle test` as normal.

    apply from: "https://raw.github.com/bradleybeddoes/gradle-plugins/master/colored-test-output.gradle"