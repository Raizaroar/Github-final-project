All contributions, bug reports, bug fixes, documentation improvements, enhancements, and ideas are welcome.
Contributing to Atom
👍🎉 First off, thanks for taking the time to contribute! 🎉👍

The following is a set of guidelines for contributing to Atom and its packages, which are hosted in the Atom Organization on GitHub. These are mostly guidelines, not rules. Use your best judgment, and feel free to propose changes to this document in a pull request.

Table Of Contents
Code of Conduct

I don't want to read this whole thing, I just have a question!!!

What should I know before I get started?

Atom and Packages
Atom Design Decisions
How Can I Contribute?

Reporting Bugs
Suggesting Enhancements
Your First Code Contribution
Pull Requests
Styleguides

Git Commit Messages
JavaScript Styleguide
CoffeeScript Styleguide
Specs Styleguide
Documentation Styleguide
Additional Notes

Issue and Pull Request Labels
Code of Conduct
This project and everyone participating in it is governed by the Atom Code of Conduct. By participating, you are expected to uphold this code. Please report unacceptable behavior to atom@github.com.

I don't want to read this whole thing I just have a question!!!
Note: Please don't file an issue to ask a question. You'll get faster results by using the resources below.

We have an official message board with a detailed FAQ and where the community chimes in with helpful advice if you have questions.

Github Discussions, the official Atom message board
Atom FAQ
What should I know before I get started?
Atom and Packages
Atom is a large open source project — it's made up of over 200 repositories. When you initially consider contributing to Atom, you might be unsure about which of those 200 repositories implements the functionality you want to change or report a bug for. This section should help you with that.

Atom is intentionally very modular. Nearly every non-editor UI element you interact with comes from a package, even fundamental things like tabs and the status-bar. These packages are packages in the same way that packages in the Atom package repository are packages, with one difference: they are bundled into the default distribution.

atom-packages

To get a sense for the packages that are bundled with Atom, you can go to Settings > Packages within Atom and take a look at the Core Packages section.

