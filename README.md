# iSSB - buttonless

A fork of the cross-platform *Super Smash Bros. Brawl* fan game that removes the on-screen controller buttons and options, decluttering the UI. This is intended to be compiled for Windows and is recommended for all PC players.

This project uses Git submodules, so to download it, you'll have to clone it recursively:

```bash
git clone -b buttonless --single-branch --recursive https://github.com/Nightcaat/iSSB
```

Cloning a single branch isn't needed for the default branch, but in my experience on v2.38.1, Git fails to update the submodules if you clone all branches and then try checking out a different one, so you should clone a specific branch if you're interested in compiling it.