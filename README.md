[![Jovo Framework](https://www.jovo.tech/img/github-logo.png)](https://www.jovo.tech)

<p align="center">Templates for the <a href="https://github.com/jovotech/jovo-framework-nodejs">Jovo Framework</a> ⭐️</p>

<p align="center">
<a href="https://www.jovo.tech/framework/docs/"><strong>Documentation</strong></a> -
<a href="https://github.com/jovotech/jovo-cli"><strong>CLI </strong></a> - <a href="https://github.com/jovotech/jovo-framework-nodejs/blob/master/CONTRIBUTING.md"><strong>Contributing</strong></a> - <a href="https://twitter.com/jovotech"><strong>Twitter</strong></a></p>
<br/>

# Template: Hello World

Jovo Typescript Sample Voice App with a simple "Hello World!" + asking for the user's name. This is the default template for the `jovo new` command:

```sh
$ jovo new <directory>

## Alternative
$ jovo new <directory> --template helloworld
```

## Setup Instructions for LibertyJS 2019!


### NodeJS + NPM

The most robust way to use NodeJS is through nvm, which stands for Node Version Manager.
Sometimes, NodeJS versions move ahead of what's supported in remote hosting environments. NVM makes choosing a version of node per-project easy, so we're going to use NVM to install NodeJS and pick the right version. For us, we'll use node version _10.10_. The `.nvmrc` file already has this recorded.

>`curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.0/install.sh | bash`

Once NVM is installed, confirm that you have a `.nvmrc` file in the project's root directory, and that it says `v10.10` (if not, please add that to the file!).

Now, let's use nvm to install node v10.10:
>`nvm use && nvm install`

You can read more about NVM [here](https://github.com/nvm-sh/nvm).

### AWS CLI

If you do not have the python package manager, `pip`, you can install with the following bash:

>`curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py`

Then, in the directory you installed pip in,
>`python get-pip.py`

Finally, use pip to install the AWS CLI:
>`pip install awscli`


### ASK CLI

Although this project is all about Jovo, the ASK CLI is sometimes used under-the-hood, so we want to have this handy for those cases.

>`npm install -g ask-cli`

That's it!

More info on the ASK CLI is available [here](https://developer.amazon.com/docs/smapi/quick-start-alexa-skills-kit-command-line-interface.html).


### Jovo CLI

>`npm install -g jovo-cli`

More info [here](https://github.com/jovotech/jovo-cli).


## URLs

If you want to get back to this source repo quickly, follow [this link](https://github.com/Jefftopia/libertyjs-2019-jovo).


## Start the project

1. `npm install`
2. `npm start`
