# LoopWorkspace - Version Pierre VERY EXPERIMENTAL

## Purpose

This version is a specific version included the link with the xDrip4IOS instead of Spike. The main advantage is to provide a shared environment without server between these two apps. 

To be OK, we should compile/run the xDrip4iOS app in the same group as Loop.  See JohanDegraeve's xdripswift (https://github.com/JohanDegraeve/xdripswift). 

This version uses the xdrip client provided by julian-groen and improved by alekst1d. Thanks  ! 


## Clone

This repository uses git submodules to pull in the various workspace dependencies.

To clone this repo:

```
git clone --branch=master --recurse-submodules https://github.com/avouspierre/LoopWorkspace
```

Replace `<branch>` with the initial LoopWorkspace repository branch you wish to checkout.

## Open

Change to the cloned directory and open the workspace in Xcode:

```
cd LoopWorkspace
xed .
```

## Build

Select the "Loop (Workspace)" scheme (not the "Loop" scheme) and Build, Run, or Test.

<a href="/docs/scheme-selection.png"><img src="/docs/scheme-selection.png?raw=true" alt="Image showing how to select the Loop (Workspace) scheme in Xcode" width="400"></a>

