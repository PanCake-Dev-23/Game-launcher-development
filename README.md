# Game-launcher-development
generic game launcher base made using one drive download base

i plan to build to launcher types one that uses a google drive link and another that is decigned for dev versions.

# the drive launcher
while making a game i needed a game launcher/updater to simplyfy the update prosses, this game launcher uses google drive links to grab the build files and is made specificaly for unreal engine (might make for diffrent engins if im bothered).

the logic behind the launcher is a followes, a small nested program inside the launcher checks if the launcher itself needs and update if not boots launcher, then once launcher boots it loades the txt file that determins game version and compares it to the drive link txt version file, if the drive version is higher than the local version it will pull the build files from teh drive and replace it, if its the same the launcher will give teh option to boot game.

if the version file is lower on the drive the launcher will give back an error (i plan to add a protocal that calls a separate txt file in the drive that checks the error and gives it a comand.)

#the dev launcher

this version works the same as the drive one but instead of trying to pull a build and version from a external source you have to plug in the game version manualy, this version will be designed for game devs who are testing there packaged games, thats it there is nothing fancy this is probs the first one ill make as it will be used for my project.
