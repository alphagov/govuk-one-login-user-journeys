# GovUK One Login User Journeys Prototype

## Prototype Kit requirements

```shell
Node.js 18.x.x
```

## Installation

After cloning the repo, in the repo directory run:

```shell
npm install
npm run dev
```
On the initial run you will be asked a question about usage, answer with Y or N key and enter.


Quit the Prototype Kit, in the terminal press the ctrl and c keys together.

You are now ready to run it.


## Running the prototype

```shell
npm run dev
```

To Quit the Prototype Kit, in the terminal press the ctrl and c keys together.

## Prototype specific features

### To enable "Back to scenario landing page" link in the header and set a url for it (the link ist disabled by default)
Put inside the template, right after "{% extends "layouts/main.html" %}":
```shell
{% set showTopNav = true %}
{% set topNavUrl = "/home" %}
```
replace "/home" url value with the one that you need the link to go to
