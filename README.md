# Truffle Notes

Quick Truffe reference

## Truffle Introduction

Smart contracts are programs which govern the behaviour of accounts within the Ethereum state, and represent the fundamental building block of Ethereum applications. A contract in the sense of Solidity is a collection of code (its functions) and data (its state) that resides at a specific address on the Ethereum blockchain.

## Truffle Environment Installation

To install Truffle, you need to have Node.js and npm installed on yout machine. Truffle can be installed 

```
npm install -g truffle
```

If you execute this command as a normal user, probably you will get some permission errors. Although you could install it using sudo, it's not recommended. This happens because Node.js and NPM probably have been installed using sudo, and so they are placed in `usr/bin/node` and `usr/bin/npm` directories. 

In order to install Truffle on GNU/Linux or macOS as a normal user, and not experience permission errors during installation, first of all you need to remove your current installation of Node.js and NPM, and reinstall them using Node Version Manager or NVM.

You can get NVM usig the following command:

```
wget -qO- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.2/install.sh | bash
```

Once you have NVM, you can check the current version using this command:

```
nvm --version
```

To install the latest LTS version of Node.js through NVM, you need to use the following command:

```
nvm install --lts
```

Now, you can isntall NPM globally using the following command:

```
npm install -g npm
```

Before installing Truffle, it's recommended to install some node-gyp dependencies for compiling native add-on modules for Node.js, 

```
sudo apt install make g++
```

Now, you should be able to install Truffle globally as a normal user without experiende permission errors, using the same command presented before:

```
npm install -g truffle
```

To use Truffe, you will also need a network like Ganache, which can be installed globally using the following command:

```
npm install -g ganache
```

## Truffle Project Initialization

To start a project using Truffle, first of all you need to create an empty folder which will contain all project and Truffle files. 

To create a folder inside the current working directory you are on, you can use the following command.

```
mkdir myProject
```

Now, you need to navigate inside the project directory:

```
cd myProject
```

Now, you can initialize the Truffle environment for that project using the following command:

```
truffle init
```

## Truffle Directory Structure

## Compilation

## Delploy or Migration

## Testing







