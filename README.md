# 🚀 Learn CI/CD with Husky & GitHub Actions (Next.js Example)

This project is a hands-on guide for developers who want to **learn and implement a CI/CD pipeline** using **Husky**, **GitHub Actions**, and **Vitest** in a **Next.js** application. By exploring this repo, you’ll gain practical experience in setting up a professional development workflow from scratch.

👉 freeCodeCamp tutorial - [How to Set Up a CI/CD Pipeline with Husky and GitHub Actions](https://www.freecodecamp.org/news/how-to-set-up-a-ci-cd-pipeline-with-husky-and-github-actions)

#### 🧠 What You'll Learn

* How **CI/CD** works in modern web development
* Setting up **Husky Git hooks** to lint and test code before every commit
* Using **lint-staged** to speed up checks by only scanning staged files
* Creating **GitHub Actions workflows** to:

  * Run linting and unit tests on every push
  * Run coverage reports on every pull request
  * Automatically report test coverage as PR comments
* Connecting with **Vercel** for automatic deployments

#### 💠 Technologies Used

* [Next.js](https://nextjs.org/)
* [Vitest](https://vitest.dev/)
* [ESLint](https://eslint.org/)
* [Husky](https://typicode.github.io/husky)
* [lint-staged](https://github.com/okonet/lint-staged)
* [GitHub Actions](https://github.com/features/actions)
* [Vercel](https://vercel.com/)

#### 📘 How to Use This Project

1. **Clone the repo** and install dependencies

   ```bash
   git clone https://github.com/sasmithaK/hands-on-CI-CD
   hands-on-CI-CD
   npm install
   ```
2. **Inspect the pre-commit file under the demo-app/.husky**

   * Contains scripts that automatically run linting and tests before every commit to ensure code quality.


3. **Inspect the workflow YML files under the demo-app/.github/workflows**

   * Define GitHub Actions that run on push and pull_request events to automate testing, linting, and code coverage reporting.


4. **Make a change and commit it**

   * Husky will run lint and test checks before the commit is finalized.

5. **Push to GitHub**

   * GitHub Actions will automatically run tests and lint your code.
   * Open a PR to see coverage reports posted as comments.

6. **Deploy automatically with Vercel**

   * You can deploy it on Vercal. 
   * Any change merged to `main` will trigger a Vercel deployment.

---

Feel free to fork this project, experiment with the workflow files, and adapt it to your own apps. It’s designed to help you build solid CI/CD habits early in your development journey.
