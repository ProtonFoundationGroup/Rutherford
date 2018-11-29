# Rutherford
__The Proton BlockChain's entry__

__PC Wallet__

# Development

First, we install Quasar CLI. Make sure you have Node >=8 and NPM >=5 installed on your machine. If you want to learn what Quasar is and what it can do for you, read the [Introduction to Quasar](http://quasar-framework.org/guide/introduction-to-quasar.html). Otherwise, let’s get started.

```bash
# make sure you have vue-cli globally installed
$ yarn global add vue-cli

# Node.js >= 8.9.0 is required.
$ yarn global add quasar-cli

or

$ npm install -g vue-cli
$ npm install -g quasar-cli
```

Then, we checkout the source code of Rutherford from github.
```bash
git clone https://github.com/ProtonFoundation/Rutherford.git
```

### Run Rutherford

Now you're ready to initialise Rutherford for development:

```bash
$ cd Rutherford
$ yarn install
$ yarn dev
```

### Package Rutherford

```bash
$ cd Rutherford
$ yarn dist
