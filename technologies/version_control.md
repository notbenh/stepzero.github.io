# Version Control

## Introduction

Version control (aka _revision control_) is a very important concept and tool in any project, open source, software, or otherwise.

Version control does exactly what it says on the tin: It allows you to track and control different versions of your work. Have you ever used the _Track Changes_ option in your word processor? If so, then you've already used a simple form of version control.

## Terminology

### Repository

A repository (aka _repo_) is the main home for your project. It can be copied, modified locally, then have those local changes applied to the repository. This separation of working copy from master copy helps to minimize unintentional data loss or alteration. The local changes are not applied to the repository until they have been tested and verified as good and worthy.

### Sandbox

A local copy of the main repository is often called a _sandbox_. This is where you can play, test, and complete your work before submitting it back to the repository.

### Branch

A branch is a special copy of the repository. Work can progress on a branch while it continues to move forward elsewhere in the repository (on other branches or on the HEAD). Once work is complete on the branch, it can be merged into the repository.

### HEAD (aka master)

Each repository has one main branch. This branch is called the _HEAD_ or the _master_. While the specific use of the code on the HEAD branch varies from project to project, it is always a very important branch to the project's workflow. Many projects will have a rule forbidding people from working directly on the HEAD branch, instead requiring them to work on a separate branch which will then be merged into the HEAD once it has been verified that the branch will not break or destabilize the HEAD.

### Check out

### Commit

### Revert (aka roll back)

### History (aka commit log)

### Blame

## Features

Almost all version control systems will provide their own special flavor of the following features:

* Retrieve a 

## Basic operations

## Version control systems

There are many different version control packages used in open source and software development.
