[![Gitter][gitter-image]][gitter-chat]

discussions
===========

Need help? or just wanna ask a question? [open an issue][discussion/issues] on this repo!

NodeSchool organizers can have discussions [over here][organizers]. If you want to create your own NodeSchool workshop, have a look at the [workshoppers repo][workshoppers].

**Disclaimer**: In you open an issue, it's content, title and code formatting may be edited by the repository owners to improve overall understanding of the problem.

# FAQs

## Installation

### How do I know that Node.js installed correctly?

**Windows** - Open the Start Menu and look for an icon that says "Node.js Command Prompt". Type `node` in the terminal and press Enter. If a weird greater symbol (>) appeared in your terminal with a blinking underscore, then you're able to run Node.

**Linux/OSX** - Open a terminal and type `node`. If a weird greater symbol (>) appeared in your terminal with a blinking underscore, then you're able to run Node.

### I installed Node.js, now what?

**Windows** - Open the Start Menu and look for an icon that says "Node.js Command Prompt". Once you open it, you could for example type `npm install javascripting -g` to install Javascripting. If you want to install other workshopper, use the same command replacing the module name.

**Linux/OSX** - Open a terminal and type `npm install javascripting -g` to install Javascripting. If you want to install other workshopper, use the same command replacing the module name.

### I installed Node.js but when I type `node` in my terminal it says `'node' is not recognized` (or `node: command not found`)

It's likely that you have a problem with your installation. Go through the installation steps again and if you still have the problem, open an issue telling us exactly which steps did you followed to install Node.

### I have Node.js installed but when I type `javascripting` in my terminal it shows an error

If you know that Node installed [correctly][node-installed-correctly], then you may have a problem with the installation of the workshopper. Try to reinstall the workshopper. After that, if you still have the problem open an issue with your error and tell us exactly what happened.

## Working on challenges

### I can't find what is wrong!

Don't panic. Open an issue, give us your code, the workshopper name, the challenge name and be patient. Someone will try to help you soon.

### The challenge is wrong!

All the workshoppers are Open Source. If you know how to fix it, just submit a pull request to the workshopper's repository explaining the problem. If you don't know how to fix it, open an issue with the title `Improvement - Workshopper name, challenge name` and all the aditional info you consider it's neccessary in it's content.



# NodeSchool Discussions Rules

## 1 - Be nice

All of the workshops and all of the discussions are done by volunteers and there is no guarantee that all questions get answered. If you only provide negative feedback and not constructive criticism your issue will probably get closed with no response.

## 2 - Be public

Don't email workshop authors directly, use the public discussion forum (the Issues) for all communication, that way your question and any answers you get can benefit everyone else.

## 3 - Be patient

It may take a day or two for people to respond here. Please don't send multiple messages in a row, it won't help your question get answered any faster.

# Suggestions

## Provide full command output

To help us debug your problem please include all output from the commands you ran, including any error messages you received.

It also helps to include your node, npm, git or other CLI command versions, which you can get by running `node -v`, `npm -v` etc.


[gitter-image]: https://badges.gitter.im/Join%20Chat.svg
[gitter-chat]: https://gitter.im/nodeschool/discussions?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge
[discussion/issues]: https://github.com/nodeschool/discussions/issues
[organizers]: https://github.com/nodeschool/organizers
[workshoppers]: https://github.com/nodeschool/workshoppers
[node-installed-correctly]: https://github.com/nodeschool/discussions#how-do-i-know-that-nodejs-installed-correctly