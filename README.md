<!-- markdownlint-disable MD024 -->
<!-- 
Comment out all TODO lines and empty/unneeded sections before committing. 

Placeholder strings to replace (including curly braces)
* {PROJECT_NAME}
* {REPO_NAME}
* {PACKAGE_NAME}
* {RELEASE_TAG}
* {USERNAME}
-->

# {PROJECT_NAME}

**📍 TODO**: Write a project description here. What does it do and why would someone use it?

<!-- 
TIP: Add screenshots or gifs to make your project description or usage steps more effective.

![name of image](./Screenshots/sample.png)
*Add a little caption for your embedded image like this.* 
-->

## 🕵️‍♂️ History

### Project Releases

These tags denote a version or milestone for this project.

Release | Notes
--------|--------
[{RELEASE_TAG}](https://github.com/{USERNAME}/{REPO_NAME}/releases/tag/{RELEASE_TAG}) | Enter your release notes here. What's new and what changed?

### Version Compatibility

These Aras Innovator releases have been confirmed or can reasonably be expected to work with this project.

Project Release | Aras Release
----------------|------
[{RELEASE_TAG}](https://github.com/{USERNAME}/{REPO_NAME}/releases/tag/{RELEASE_TAG}) | List the Aras versions supported by your project here. Ex: "12 SP18" or "R14-R26" or "R31+"

## 👷‍♀️ Installation

> ### **💥 Important**
>
> **Always back up your code tree and database before applying an import package or code tree patch!**

**📍 TODO**: Include instructions describing how to install and configure this project. See the collapsed sections below for example install instructions for Aras Update packages and manual packages.

<details>
<summary><b>Example for Aras Update installations</b></summary>

### Prerequisites

1. Aras Innovator (version ___ preferred)
2. Aras Update tool (version ___)
3. **{PROJECT_NAME}** Aras Update package

### Aras Update Installation

1. Open Aras Update.
2. Select **Local** from the sidebar.
3. Add a new package reference.
4. Select the folder containing your local copy of the **{PROJECT_NAME}** repo.
    - This folder should contain a file called `package.config`.
5. The **{PROJECT_NAME}** package will now appear in your list of local packages.
    - You may need to expand the window to see all of the available projects.
6. Select **{PROJECT_NAME}** from the package list and click **Install**.
7. Check all of the modules that you want to install and click **Next**.
8. Choose **Detailed Logging** and click **Next**.
9. Fill in the details about your Aras Innovator instance and click **Install**.
10. After the installation completes, close the Aras Update utility and proceed to the **Configuration** section below.

</details>

<details>
<summary><b>Example for Manual installations</b></summary>

### Prerequisites

1. Aras Innovator (version ___ preferred)
2. Aras Package Import utility
3. **{PROJECT_NAME}** Import package

### Manual Installation

#### Code Tree

1. Backup your code tree and store the backup in a safe place.
2. Copy the `Innovator` folder from `\CodeTree` in your local repository.
3. Paste this folder to the root install directory of your code tree.
    - This should be the same folder that contains the `InnovatorServerConfig.xml` file.

#### Import Package

1. Back up your database and store the BAK file in a safe place.
2. Open up the Aras Package Import utility.
3. Enter your login credentials and click **Login**.
    - _Note: You must log in as root for the package import to succeed!_
4. Enter the package name in the TargetRelease field.
    - Optional: Enter a description in the Description field.
5. Enter the path to your local `..\{REPO_NAME}\Import\imports.mf` file in the Manifest File field.
6. Select the following in the Available for Import field.
    - **{PACKAGE_NAME}**
7. Select Type = **Merge** and Mode = **Thorough Mode**.
8. Click **Import** in the top left corner.
9. Close the Aras Package Import utility.

</details>

### Configuration

**📍 TODO**: Write any necessary or optional post-install configuration steps here

## 🚀 Usage

### User Steps

**📍 TODO**: Write step-by-step instructions for users to follow. If this project is complex, consider providing a link to a user guide document/page.

### Technical Consumption

**📍 TODO**: If this is a technical project (like an API), include instructions for consuming it via code and/or client

## 🤝 Contributing

Like this project and want to help maintain or improve it? Here's how you can contribute!

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

## 🎉 Credits

**📍 TODO**: Write credits to recognize those who created or contributed to the project. Link profiles and organizations when possible.

Example: This project was created by [Eli J. Donahue](https://github.com/EliJDonahue) from [Aras Labs](https://github.com/ArasLabs).

## 🗝️ License

**📍 TODO**: [Choose an open source license](https://choosealicense.com/) and include it in your repository as LICENSE.md.

Example: This project is published to Github under the MIT license. See the [LICENSE file](./LICENSE.md) for license rights and limitations.
