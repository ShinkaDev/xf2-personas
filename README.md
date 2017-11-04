# [Shinka] Personas
Lightweight sub-accounts with customizable user fields and avatars.

## Installation
* Download the [latest stable release](https://github.com/kalynrobinson/xf2_personas/releases)
* Extract the zip
* Copy the contents of the `upload` folder to the root of your Xenforo installation
* Install and activate the add-on in your Admin CP

## Features
* TBD

## Tip Jar
* Like my plugins and have some extra coffee money? [Throw it my way!](https://www.paypal.me/shinkacodes/5)

## Development
* Clone or fork the repository
* Create a symbolic link for the ThreadLog folder in your XF2 installation to the one in the repository directory, e.g.
```
> mklink /D "C:/Fake User/My Site/src/addons/Shinka/Personas" "C:/Fake User/Dev/xf2_threadlog/upload/src/addons/Shinka/Personas"
```
* Import development output by executing 
```
> php cmd.php xf-dev:import --addon Shinka/Personas
```
