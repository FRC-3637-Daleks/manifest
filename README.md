**Warnging: This is only usable on *nix based systems as the repo tool does not support Windows.**

This is the manifest for the `repo` tool. This allows locally downloading all projects in an easy and reproducable manner.

##Installing repo

Follow the instructions avaliable on the Google AOSP documentation.  
[Installing Repo](https://source.android.com/source/downloading.html#installing-repo)

##Initializing this repo
To initialize this repo, run:
```
$ repo init -u https://github.com/FRC-3637-Daleks/manifest.git -b <branch>
```
`<branch>` should be replaced with the current competition year to download the latest sources.  

Synchronizing sources can be done with:
```
$ repo sync
```
Optionally, the `-j <threads>` paramater can be supplied to increase the speed of the sync.
