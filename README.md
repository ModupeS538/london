
# Description

The Women Who Code London is a community dedicated to inspiring women to excel in their technology careers. Our events cover various topics around software engineering.

If you're interested in joining the community as a member or volunteer please visit our [website](https://www.womenwhocode.com/london) or join [our slack](https://bit.ly/wwcodelondonslack).

## Contributing

We welcome your contributions! 💕 To contribute to this repo, follow the [contributing guidelines](CONTRIBUTING.md). 

Also if you want to support the *Mentorship Program* in general you can contact [Eleonora Belova](https://wwcodelondon.slack.com/archives/D03SM0VR5V1) on WWCode London Slack.

## Mentorship Program Webpage

### How to Run Locally

This content is created using GitHub Pages with Jekyll. 

#### Prerequisites
Before you can use Jekyll to test a site, you must:

1. Install [Jekyll](https://jekyllrb.com/docs/installation/).
Create a Jekyll site. For more information, see "Creating a GitHub Pages site with Jekyll."
We recommend using Bundler to install and run Jekyll. Bundler manages Ruby gem dependencies, reduces Jekyll build errors, and prevents environment-related bugs. To install Bundler:

2. Install Ruby. For more information, see [Installing Ruby](https://www.ruby-lang.org/en/documentation/installation/).
   
3. Install Bundler. For more information, see [Bundler](https://bundler.io/)

#### Building and run

Run on terminal `bundle install`

Run on terminal `bundle exec jekyll serve`

Access the page on browser: http://127.0.0.1:4000


### External Links about GitHub Pages

* [GitHub Pages Doc](https://docs.github.com/en/pages) 
* [About GitHub Pages and Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/about-github-pages-and-jekyll)
* [Test locally with Jekyll](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll)


### How to Run End-To-End Testing Locally

1. Open your Terminal in the `e2e-tests` folder, e.g. `cd ~/workspace/london/e2e-tests`
2. `npm install cypress --save-dev` - This will install Cypress locally as a dev dependency for your project.
3. Run `npx cypress open` from your project root
4. Select E2E testing

![Open Cypress](https://i.ibb.co/4VNPFjf/welcome-cypress.png)

5. Select *E2E testing* option.

6. Choose your browser and click *Start E2E testing in..*..

![Browser Selection](https://i.ibb.co/kQxJpmJ/browser-selection.png)

Now you can run any tests from *Specs*.

For more details, please refer to the official [Cypress Documentation](https://docs.cypress.io/guides/overview/why-cypress).