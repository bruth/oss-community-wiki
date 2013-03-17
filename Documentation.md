## Download

Download here: https://github.com/bruth/oss-community-wiki/archive/master.zip

```bash
unzip oss-community-wiki-master.zip
```

## Setup

If this is a brand new wiki, do the following where `REPO` is the repository
name this wiki is for (assuming you are deploying it on GitHub):

```bash
mv oss-community-wiki-master REPO.wiki
cd REPO.wiki
git init
git remote add origin git@github.com:USERNAME/REPO.wiki.git
```

If you have an existing wiki, clone the wiki then copy over the desired
files over:

```bash
cp -i oss-community-wiki-master/* REPO.wiki
```

## Write

The most important step is to write content specific to your project!
