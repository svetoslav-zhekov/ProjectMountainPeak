# 🚨 Before forking this repo (PLEASE READ!) 🚨
All the images, videos, sounds, music and logos in this project are with illustrative purposes only, they cannot be used, adapted, copied or published without their creator's permission.

# ℹ️ Git Flow Conventions ℹ️

## Branches
* Always create a new branch for every single new feature or change!
* Never push directly to main, always create a PR!
* New branches are named in this way ```init|update|feature|fix``` then ```/``` and finally the name of the branch. If there is spacing in the branch name, replace spaces with ```-```. Example: ```feature/add-new-entity```.

## Commits
* Commits are named almost the same way as branches, again before name we put ```init|update|feature|fix```, after this we use ```:``` and put commit message, you are allowed to use spaces in commit messages. Example: ```update: changed property name```.

## Pull Requests
* Always use Squash and Merge as a completion strategy!
* Always double check everything before merging!

# ℹ️ Project Conventions ℹ️

## Summaries
* Summaries are mandatory for every single script created!

## Comments
* If something is unclear, always put down a comment, after the ```//``` put a space and write your comment message, start with a capital letter. Example: ```// Calculating distance from object```

## Code
* For private fields, use ```_``` as a prefix and name after with camel casing. Example: ```private string _helloWorld;```.
* Protected fields, use camel casing, but do not have the ```_``` prefix.
* For methods, classes, interfaces, enums and all base types, also for properties use pascale case. Example: ```public class HelloWorld```.
* All interfaces start with ```I``` before their name. Example: ```IEntity```.
* All enums end with ```Type```. Example: ```public enum PlayerStatusType```.
