Let's suppose we have a team of 6 people working on a Python Flask project.

For our CI setup we will need a linter and testing, but we won't need to build the application since Python is an interpreted language and we won't gain anything by having minimized build of the app.
As for linting we can use Flake8 which is a tool that allows to detect both logical and stylistic lint. We can configure our stylistic prefereces for our project, but we'll mostly base on PEP8 which is leading stylistic guide.
For testing Flask application we'll use pytest library as it is proposed by official Flask documentation. With it we can configure our tests for the app. For checking the coverage we'll use coverage library.

As an alternative for GitHub Actions we can use CircleCI which is configurable both for cloud and on-premises solutions. With this we're not limiting ourselves to one solution, but we open ourselves an option for the future if we want to make the switch.

Our team is only 6 people, which can be considered a small team. Taking this into account we are going to use cloud solution, because the on-premises solution would take too much time to set up and wouldn't give us exnough upsides.