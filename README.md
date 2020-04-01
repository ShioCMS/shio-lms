[![Twitter](https://img.shields.io/twitter/follow/shiocms.svg?style=social&label=Follow)](https://twitter.com/intent/follow?screen_name=shiocms)

**Viglet Shio LMS** - Manage, document, track, create reports and deliver educational courses.

**If you'd like to contribute to Viglet Shio LMS, be sure to review the [contribution
guidelines](CONTRIBUTING.md).**

**We use [GitHub issues](https://github.com/Shio/shio-lms/issues) for tracking requests and bugs.**

# Installation

## Download

```shell
$ git clone https://github.com/ShioCMS/shio-lms.git
$ cd shio-lms
```

## Deploy 

### 1. Install Mudles

Use the NPM to install the modules.

```shell
$ npm install
```

### 1. Runtime

Use Ng and Gradle to execute Shio LMS.

```shell
$ ng serve --open
$ ./gradlew bootrun
```

### 2. Build

Use Ng and Gradle to build Shio LMS.

```shell
$ ng build --prod
$ ./gradlew build
```

## URL

Home: http://localhost:2711