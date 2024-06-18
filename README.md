<header>

<!--
  <<< Author notes: Course header >>>
  Include a 1280×640 image, course title in sentence case, and a concise description in emphasis.
  In your repository settings: enable template repository, add your 1280×640 social image, auto delete head branches.
  Add your open source license, GitHub uses MIT license.
-->

# Release Workflow Course for Arizona Quickstart

_Get started with managing releases for Arizona Quickstart in less than an hour._

</header>

<!--
  <<< Author notes: Course start >>>
  Include start button, a note about Actions minutes,
  and tell the learner why they should take the course.
-->

## Welcome

The Arizona Quickstart project uses GitHub for managing releases, including minor and patch releases. This course will guide you through the steps to effectively manage these releases using GitHub Actions.

- **Who is this for**: Developers and project maintainers of the Arizona Quickstart project.
- **What you'll learn**:
  - Preparing for a minor release
  - Creating minor and patch releases
  - Managing security releases
  - Writing effective release notes
  - Finding commits to add to a release
  - Best practices, and troubleshooting
- **Prerequisites**: Basic knowledge of GitHub and GitHub Actions, familiarity with the `az-digital/az_quickstart` project.
- **How long**: This course takes approximately 45 minutes to complete, covering 4 steps.

In this course, you will:

1. Set up your repository
2. Prepare for a minor release
3. Create a release
4. Learn best practices and troubleshooting

### How to start this course

<!-- For start course, run in JavaScript:
'https://github.com/new?' + new URLSearchParams({
  template_owner: 'YOUR-USERNAME',
  template_name: 'az_quickstart-release-workflow-course',
  owner: '@me',
  name: 'az_quickstart-release-workflow-course',
  description: 'My clone repository',
  visibility: 'public',
}).toString()
-->

[![start-course](https://user-images.githubusercontent.com/1221423/235727646-4a590299-ffe5-480d-8cd5-8194ea184546.svg)](https://github.com/new?template_owner=YOUR-USERNAME&template_name=az_quickstart-release-workflow-course&owner=%40me&name=az_quickstart-release-workflow-course&description=My+clone+repository&visibility=public)

1. Right-click **Start course** and open the link in a new tab.
2. In the new tab, most of the prompts will automatically fill in for you.
   - For owner, choose your personal account or an organization to host the repository.
   - We recommend creating a public repository, as private repositories will [use Actions minutes](https://docs.github.com/en/billing/managing-billing-for-github-actions/about-billing-for-github-actions).
   - Scroll down and click the **Create repository** button at the bottom of the form.
3. After your new repository is created, wait about 20 seconds, then refresh the page. Follow the step-by-step instructions in the new repository's README.

## Steps

### 1. Setting Up the Repository

*Congratulations on setting up your repository!*

In this step, you'll fork and clone the `az-digital/az_quickstart` repository.

#### :keyboard: Activity: Set Up Your Repository
1. Fork the `az-digital/az_quickstart` repository.
2. Clone your fork locally:
    ```sh
    git clone https://github.com/YOUR-USERNAME/az_quickstart.git
    cd az_quickstart
    ```
3. Set up your local environment according to the [project documentation](https://github.com/az-digital/az_quickstart).

### 2. Preparing for a Minor Release

*Great job on setting up your repository! Now, let's prepare for a minor release.*

#### :keyboard: Activity: Prepare for a Minor Release
1. Create a new branch for the release:
    ```sh
    git checkout -b release-x.y.z
    ```
2. Update the necessary files and configurations.

### 3. Creating a Release

*You've prepared your branch. Now, let's create the release.*

#### :keyboard: Activity: Create a Release
1. Push your branch to GitHub:
    ```sh
    git push origin release-x.y.z
    ```
2. Use the GitHub Actions workflow to create the release.

### 4. Best Practices and Troubleshooting

*Congratulations on creating your release! Let's review some best practices and troubleshooting tips.*

- Always review the release notes.
- Test thoroughly before creating a release.
- Follow the [release policy](./docs/release-policy.md).

## Finish

*Well done! You've completed the course.*

Review what you've learned and invite feedback.

## Footer

---

Get help: [Post in our discussion board](https://github.com/orgs/skills/discussions/categories/introduction-to-github) • [Review the GitHub status page](https://www.githubstatus.com/)

© 2024 GitHub • [Code of Conduct](https://www.contributor-covenant.org/version/2/1/code_of_conduct/code_of_conduct.md) • [MIT License](https://gh.io/mit)
