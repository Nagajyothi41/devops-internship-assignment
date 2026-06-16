
# Git and SSH Guide

## Configure Git

git config --global user.name "Your Name"
git config --global user.email "your@email.com"

## Generate SSH Key

ssh-keygen -t ed25519 -C "your@email.com"

## Test SSH

ssh -T git@github.com

## Git Workflow

git clone
git checkout -b feature-A
git add .
git commit -m "feature"
git push origin feature-A
