# redhat-employee-mac

Tools to help Red Hat employees get started quickly on a new MacBook Pro, or more easily manage the one they have.

## For Red Hat Employees

This repo doesn't contain anything sensitive, but it won't be useful to you unless you have credentials for the Red Hat wifi network at a Red Hat office building, and you use a Mac that was configured by Red Hat IT.

## Work in Progress

For now, this is a collection of scripts and you can use it by cloning the repo and running the scripts. Eventually I'll wrap it all in a simple command line interface with npm's `commander` package, and then it will be a simple npm install.

What follows in this section is a draft of the instructions for that simple setup, but this does not yet work:

### Setup

1. Install [Homebrew](http://brew.sh/) if you don't have it already.

2. Install Node (and `npm` with it), using Homebrew:

   ```bash
   brew install node
   ```

3. Install the redhat-employee-mac package:

   ```bash
   npm install -g redhat-employee-mac
   ```

4. Run the tool with no commands to see a list of commands.

   ```bash
   redhat-employee-mac
   ```

## What does it do?

They say that necessity is the mother of invention. This repo fixes a few tiny things that I found annoying about the Mac as given to me by Red Hat. I take no responsibility for others using these tools on their Macs. Please use my tools at your own risk and consult your manager before you use any of the more destructive tools (removing Kaspersky, etc). See the disclaimers on each tool.

### The Tools

* Wi-Fi Setup Tool

  See info and instructions in the `wifi/README.md` file.

* BigFix Removal Tool
* Kaspersky Removal Tool

  Still working on these two.

* Whatever else I end up throwing in here in the future.



-----------

Mike Turley

Solving problems nobody needed him to solve since 1989

-----------
