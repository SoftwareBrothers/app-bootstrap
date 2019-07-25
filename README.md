# app-bootstrap

This is a wrapper repo containing different application boilerplates.

## The purpose

The purpose of the repo and all it's submodules is to:
* speed up starting new projects.
* enforce following standards and good practices.

## How to use it

When you starting a new project simply clone this repo with '--recursive' flag:

```
git clone --recursive git://github.com/softwarebrothers/app-bootstrap.git
```

Also it may have sense to checkout the latest version for each submodule (by default master repo tracks submodules by particular commit):

```
git submodule foreach "(git checkout master; git pull)"
```

Next, remove all `.git` folders and push needed parts to your repositories.

*Alternative approach*

...is to cherry peak the things you want to include in your project - this is also ok.

## What does it contain

It consists of 2 major parts

*1. Project templates*

It has templates for following frameworks

* hapi: `./hapi`
* react native: `./sb-starter-react-native`

*2. Root project setup*

It also has standard application setup for all subprojects:

* ./infrastructure

docker compose setup for an entire stack.

* ./documentation - jsdoc documentation setup

to genterate documentation:

```
cd documentation
yarn install
yarn docs
```

## Adding new boilerplates

Every one of us can add new app boilerplate. Please just ensure the repo has:

* readme with the information how to run it.
* linter
* docker setup
* continuous integration and delivery
* automated tests
* authentication with JWT

_Not all elements are required_

Then you can request adding it to the list of the boilerplates.

## License

AdminBro is Copyright © 2018 SoftwareBrothers.co. It is free software, and may be redistributed under the terms specified in the [LICENSE](LICENSE.md) file.

## About SoftwareBrothers.co

<img src="https://softwarebrothers.co/assets/images/software-brothers-logo-full.svg" width=240>

We’re an open, friendly team that helps clients from all over the world to transform their businesses and create astonishing products.

* We are available for [hire](https://softwarebrothers.co/contact).
* If you want to work for us - checkout the [career page](https://softwarebrothers.co/career).