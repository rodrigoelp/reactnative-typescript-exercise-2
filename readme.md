# Responding to actions

After writing the very well known "Hello World", I wondered... How should I start cleaning my code and increasing the complexity?

So, adding a few buttons should make things a bit more interesting (in preparation for a todo list or a master detailed app).

This `Actions` app gives you options and you should answer properly to the question.

## What will I find here?

- A simple app with three buttons and a question.
- Providing an answer will give you a message.
- Restructured code to extract in a neater way resources and other components. For Instance, decided to not use the standard `Button` and implemented mine (not an original idea, plenty of other places where the author is doing something similar); the idea is to have a square area to tap on as opposed to a link-ish button.

## I want to play with this code

1. Clone this repo `git clone git@github.com:rodrigoelp/reactnative-typescript-exercise-2.git actions` (`actions` is the name of the local folder, change it to whatever floats your boat)
1. Open a terminal and enter `$> cd actions/`
1. Then `$> npm install` (this will set up the dependencies for your project. I am going to start recommending you to use `yarn` - [instructions on how to install it](https://yarnpkg.com/lang/en/docs/install/))
1. To start React-Native packager type: `$> react-native start` (it will block the terminal as it will be running a web server)
1. In a new terminal type in the same folder: `$> react-native run-ios` or `$> react-native run-android` (depends on the version you want to run)

## What if I am using vscode?

I haven't provided a configuration for you to run it, but is not hard to configure it. Just install the `vscode react native tools` [instructions available here](https://github.com/Microsoft/vscode-react-native). This link will also explain how to configure that .vscode folder (is all automatic, don't be afraid!)

## Interesting to note

If you choose the middle option, there is no second `alert` shown after the original has triggered... Wonder what is going on there...