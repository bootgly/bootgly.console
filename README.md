<p align="center">
  <img src="https://github.com/bootgly/.github/raw/main/favicon-temp1-128.png" alt="bootgly-logo" width="120px" height="120px"/>
</p>
<h1 align="center">Bootgly.CLI template</h1>
<p align="center">
  <i>Bootgly CLI Workables template</i>
</p>
<p align="center">
  <a href="https://packagist.org/packages/bootgly/bootgly">
    <img alt="Bootgly License" src="https://img.shields.io/github/license/bootgly/bootgly"/>
  </a>
</p>

You should use this repository to start building your CLI workables.

This repository serves as a template (starter kit) for creating CLI applications using the Bootgly CLI, which is a part of the [Bootgly PHP Framework][BOOTGLY_PHP_FRAMEWORK].

## 🧩 Templating

### Using Github / Git

To get started with the Bootgly CLI template repository on GitHub, follow the steps below:

1. Navigate to the main page of the Bootgly CLI template repository on GitHub.
2. Click on the "Use this template" button located near the top-right corner of the repository page:
| ![Click on the "Use this template"](https://github.com/bootgly/.github/raw/main/screenshots/bootgly-php-framework/Bootgly.CLI-template.png) |
4. On the "Create a new repository" page, provide a name for your new repository.
5. Optionally, add a description and choose the visibility and permissions for your repository.
6. Click on the "Create repository from template" button to create your new repository based on the Bootgly CLI template.

### Using Composer

If you prefer using Composer to manage your PHP dependencies, follow the steps below to initialize the Bootgly CLI template repository:

#### Option 1 - create-project command

To create a new project using the Bootgly CLI template and Composer's create-project command, follow these steps:

1. Open your terminal or command prompt.
2. Run the following command to create a new project based on the Bootgly CLI template:

```
composer create-project bootgly/bootgly.cli my-bootgly-cli-app
```

Replace `my-bootgly-cli-app` with the desired name of your project directory.

**Composer will download the Bootgly CLI template and its dependencies, and create the project structure for you.**

<!--
#### Option 2 - package init

1. Open your terminal or command prompt.
2. Create a new directory for your project and navigate to it:

```
mkdir my-bootgly-cli-app
cd my-bootgly-cli-app
```

3. Initialize a new Composer project within your directory:

```
composer init
```

4. When prompted, provide the necessary information for your project such as package name, description, author, etc.
5. After completing the initialization, open the composer.json file in a text editor.
6. Under the require section, add the following line to include the Bootgly CLI template as a dependency:

```json
"require": {
   "bootgly/bootgly.cli": "1.0.0"
}
```

7. Save the changes to the composer.json file.
8. Run the following command to install the Bootgly CLI template and its dependencies:

```
composer install
```
-->
## 🔜 Next Steps

Once you have initialized your Bootgly CLI template repository either using GitHub or Composer, you can start developing your CLI application. Here are a few recommended steps to get started:

1. Review the [Bootgly documentation][BOOTGLY_DOCS] to understand the features and capabilities of the Bootgly CLI.
2. Check `projects\*.constructor.php` files. Add new commands, instance CLI components, and update the application configuration as needed.
3. Test your CLI application locally to ensure it functions as expected. You can use the provided testing tools and utilities included in the Bootgly CLI.
4. Add any additional dependencies or libraries your application requires to the composer.json file and install them using Composer.
5. Document your CLI application by updating the README file and providing instructions on how to use and configure your application.
6. Once you are ready, consider publishing your CLI application to Packagist to make it available to others. Follow the Packagist documentation for guidelines on publishing your project.

That's it! You now have a solid foundation for building your CLI application using the Bootgly CLI. Happy coding!

## 📃 License

The Bootgly PHP Framework is open-sourced software licensed under the [MIT license][MIT_LICENSE].

<!-- Links -->
[BOOTGLY_DOCS]: https://docs.bootgly.com
[BOOTGLY_PHP_FRAMEWORK]: https://github.com/bootgly/bootgly
[MIT_LICENSE]: https://opensource.org/licenses/MIT
