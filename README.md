# app-bootstrap

This is a wrapper repo containing different application boilerplates.

## How to use it

The goal of the repo is to bootstrap project creation in SoftwareBrothers. By using it you ensures that your project follows the good practices within our company.

When you starting a new project simply clone this repo with '--recursive' flag:

```
git clone --recursive git://github.com/softwarebrothers/app-bootstrap.git
```

Next, remove all `.git` folders and push needed parts to your repositories.

## What does it contain

It consists of 2 major parts

*1. Project templates*

It has templates for following frameworks

* (hapi)[./hapi]
* (react native)[./react-native]
* react (soon)
* angular (soon)

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

## License

AdminBro is Copyright © 2018 SoftwareBrothers.co. It is free software, and may be redistributed under the terms specified in the [LICENSE](LICENSE.md) file.

## About SoftwareBrothers.co

<img src="https://softwarebrothers.co/assets/images/software-brothers-logo-full.svg" width=240>

We’re an open, friendly team that helps clients from all over the world to transform their businesses and create astonishing products.

* We are available for [hire](https://softwarebrothers.co/contact).
* If you want to work for us - checkout the [career page](https://softwarebrothers.co/career).