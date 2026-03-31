# Verilator Setup Guide

A step-by-step guide to install and verify **Verilator** on Linux-based systems.

---

### Step 1: Install Verilator

```bash
sudo apt install verilator
```

> This will download and install Verilator from the default APT package repository.

---

### Step 2: Verify Installation

```bash
verilator --version
```

**Expected Output:**
```
Verilator 5.046 2026-02-28 rev vUNKNOWN-built20260302

```

---

## Done!

If the version number is displayed, Verilator is successfully installed and ready to use.

---

#  Git Setup & Usage Guide

A complete guide to install, configure, and use **Git** on linux systems.
 
 
### Step 1: Install Git
 
```bash
sudo apt install git
```
 
---
 
### Step 2: Verify Installation
 
```bash
git --version
```
 
**Expected Output:**
```
git version 2.51.0
```
 
---
 
## Configuration
 
Set your global username and email (used for commits):
If already setup the config, then move next instruction.
 
```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```
 
---
 
## Clone a Repository
 
```bash
git clone https://github.com/Murugavel14/Soc_Project.git
``` 
---
 
## Basic Workflow
 
### Check Status
 
See which files are modified or staged:
 
```bash
git status
```
 
---
 
### Add Files
 
Stage all changes for commit:
 
```bash
git add .
```
 
> Use `git add <filename>` to stage a specific file.
 
---
 
### Commit Changes
 
Save staged changes with a message:
 
```bash
git commit -m "Your commit message"
```
 
---
 
### Push to Remote
 
Upload your commits to the remote repository:
 
```bash
git push origin master/branch
```
 
---
 
##  Quick Reference
 
| Command | Description |
|---|---|
| `git status` | Show working tree status |
| `git add .` | Stage all changes |
| `git commit -m "msg"` | Commit with a message |
| `git push` | Push to remote |
| `git clone <url>` | Clone a repository |
 
---
 

