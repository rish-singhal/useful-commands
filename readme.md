# Useful Commands

# Table of Contents
1. [Installing deb files](#Installing-deb-file)
2. [Working with pipenv](#Working-with-pipenv)

----

## Generate SSH Keys

```bash
ssh-keygen -t rsa -b 4096
```

## Installing deb file

```bash
sudo dpkg -i <package>.deb
```

## Working with pipenv

It is better to remove

```bash
pipenv --rm
```
before doing actual installation which 

```bash
pipenv install --dev
```

## Copy to Clipboard

```bash
pbcopy < [file_name]
```

