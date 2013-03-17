## Download

Download here: https://github.com/bruth/oss-community-wiki/archive/master.zip

```bash
unzip oss-community-wiki-master.zip
```

## Setup

### New

If this is a brand new wiki, do the following where `REPO` is the repository
name this wiki is for (assuming you are deploying it on GitHub):

```bash
mv oss-community-wiki-master REPO.wiki
cd REPO.wiki
git init
git remote add origin git@github.com:USERNAME/REPO.wiki.git
```

Note, before you push you will have to click on your repo's "Wiki" tab on
GitHub (just once) to ensure the wiki is created on GitHub's servers. Otherwise
when attempting to push for first time, you will get a complaint that looks
something like this:

```bash
fatal: '/data/repositories/4/nw/4b/76/75/8826310/8826310.wiki.git' does not appear to be a git repository
fatal: The remote end hung up unexpectedly
```

Since this _does_ create a repository on their servers, when you are ready to
push your changes you will have force your initial push:

```bash
git push --force
```

### Existing

If you have an existing wiki, clone the wiki then copy over the desired
files over:

```bash
cp -i oss-community-wiki-master/* REPO.wiki
```

## Write

The most important step is to write content specific to your project!
