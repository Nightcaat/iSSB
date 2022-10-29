# iSSB - buttonless

A fork of the cross-platform *Super Smash Bros. Brawl* fan game that lazily removes the in-game controller buttons on Windows. Useful for decluttering screenshots or other content since they don't work anyway. If they did, the ideal solution would be to show them if touchscreen input is detected and hide them if that stops being the case, but that's not this fork's goal.

This project uses Git submodules, so to download it, you'll have to clone it recursively:

```bash
git clone -b buttonless --single-branch --recursive https://github.com/Nightcaat/iSSB
```

Cloning a single branch isn't needed for the default branch, but in my experience on v2.38.1, Git fails to update the submodules if you clone all branches and then try checking out a different one, so you should clone a specific branch if you're interested in compiling it.