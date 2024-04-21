# CloudNet | Pull Pilot
This module for CloudNet allows changes to be bundled for testing by Git to give non-developers or developers the opportunity for quality control.

## Focus
It should merge Git branches locally and push them back to the respective platform and trigger the CI system there. This should be configured so that a jar file with the plugin/product is loaded back into a Maven repo. And be fetched from there and deployed as a plugin/extension.
This reduces the resources for servers and you can test several functions in one jar. The result should be a jar with X branches instead of X servers for each branch.
So we have static test servers instead of X dynamic servers in CloudNet

## Motivation
Since we have to maintain many plugins / functions, we are looking for a solution that allows us to quickly test many functions that can also be tested in parallel. It is important to use fewer resources and to map this on a Minecraft server. In particular, you only need Git and any CI system instead of "custom solutions". We wanted to utilise the standard of Maven and Git to avoid inventing even more new wheels. It was also a goal not to make developers accept or test functions

## Usage
**Will be added soon**


## Developer
Important preface, the project is based on Domain Driven Design and is intended to provide a learning effect and modularity.
Modularity because of the different Git platforms
There may be events or an API. But nothing is currently planned.


## Download
To download a current usable version you can use the built-in `modules install CloudNet-Pull-Pilot` command or download the jar from the release page and put it in the modules folder