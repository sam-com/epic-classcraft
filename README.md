<div>
  <h1 align="center"><a href="https://github.com/sam-com/epic-classcraft">Dev Team Workshops 📚</a></h1>
  
  <a href="https://epicreact.dev">
    <img
      alt="Learn React from Start to Finish"
      src="https://monosnap.com/file/OEeoQtmJjPBAtyWwP1weXf1bcLwteJ"
    />
  </a>
</div>

<hr />

## Prerequisites

> NOTE: The EpicReact.dev videos were recorded with React version ^16.13 and all
> material in this repo has been updated to React version ^18. Differences are
> minor and any relevant differences are noted in the instructions.

## Quick start

It's recommended you run everything in the same environment you work in every
day, but if you don't want to set up the repository locally, you can get started
[CodeSandbox](https://codesandbox.io/p/devbox/epic-classcraft-f6n8vn).

For a local development environment, follow the instructions below

## System Requirements

- [git][git] v2.13 or greater
- [NodeJS][node] `>16`
- [npm][npm] v8.16.0 or greater

All of these must be available in your `PATH`. To verify things are set up
properly, you can run this:

```shell
git --version
node --version
npm --version
```

If you have trouble with any of these, learn more about the PATH environment
variable and how to fix it here for [windows][win-path] or
[mac/linux][mac-path].

## Setup

> If you want to commit and push your work as you go, you'll want to make a git
> branch for yourself

After you've made sure to have the correct things (and versions) installed, you
should be able to just run a few commands to get set up:

```shell
git clone https://github.com/sam-com/epic-classcraft.git
cd epic-classcraft
node setup
```

This may take a few minutes.

If you get any errors, please read through them and see if you can find out what
the problem is. If you can't work it out on your own then please [file an
issue][issue] and provide _all_ the output from the commands you ran (even if
it's a lot).

If you can't get the setup script to work, then just make sure you have the
right versions of the requirements listed above, and run the following commands:

```shell
npm install
npm run validate
```

If you are still unable to fix issues and you know how to use Docker 🐳 you can
setup the project with the following command:

```shell
docker-compose up
```

## Running the app

To get the app up and running (and really see if it worked), run:

```shell
npm start
```
