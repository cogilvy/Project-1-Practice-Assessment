
# Project 1 Practice Assessment

You will be editing the JS file in an HTML/CSS/JS repl to create a functioning app.

To view an example of the app we will be building, click here [https://project-1-assessment-practice-2.cogilvy.repl.co/]

### Getting Started

1. Create an HTML/CSS/JS repl
2. Copy the following code into your HTML file:

```html
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width">
    <title>repl.it</title>
    <link href="index.css" rel="stylesheet" type="text/css" />
  </head>
  <body>
    <div>
      <input id="num1"> + <input id="num2">
    </div>
    <button>=</button>
    <h1>RUNNING TOTAL: <span></span></h1>
    <script src="index.js"></script>
  </body>
</html>
```

## Slack

We will be using slack to communicate throughout the course. You will receive an invite to the relevant channels via e-mail. You can login via the web browser, but downloading / installing the app is highly recommended.

[Download Slack](https://slack.com/downloads)

Remember to drag the Slack app into the Applications folder when you open the downloaded archive.

## Homebrew

Homebrew is a package manager that we will use to install various command line tools in our class.

Open up terminal, and paste the following command to install Homebrew. You might be prompted to install XCode Command Line Tools during the install process.

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

If you are prompted to install the XCode CLI, say yes and your homebrew installation will continue.

After the installation process, run the command `brew doctor`. If any warnings or errors are displayed, we will need to resolve them before proceeding with the rest of the install fest.

Lastly, make sure to run `brew update` to make sure you have the latest lists of available software.
