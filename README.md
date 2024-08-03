# Documentation and Guidelines

## Setup and Installation

1. For the purpose of this project, we need the following installed on our
   systems:

   - [Git](https://git-scm.com/downloads)
   - [NodeJS](https://nodejs.org/en)
   - A text editor of your choice (we shall use
     [VS Code](https://code.visualstudio.com/) - but feel free to use the one of
     your choice)

   Expand a section based on the OS you are using:

   <details>
   <summary>Windows</summary>

   Download the setup executables from the above links, and install the programs
   keeping everything default.

   `NOTE - Make sure to update your PATH`

   Check if you have correctly installed by running the following commands:

   ```
   node --version
   git --version
   ```

   You should see an output like this:

   <img src="images/versions.png" />

   Next, download [Visual Studio Code](https://code.visualstudio.com/) or any
   other text editor of your choice and install it by simply following the steps
   in the setup wizard.

   </details>

   <details>
   <summary>Mac</summary>

   Install HomeBrew:

   ```
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

   Run the following commands to install Git and NodeJS on Mac:

   ```
   brew install git
   brew install node
   ```

   Check if you have correctly installed by running the following commands:

   ```
   node --version
   git --version
   ```

   You should see an output like this:

   <img src="images/versions-mac.jpg" />

   </details>

   <details>
   <summary>Linux</summary>

   Run the following commands to install Git and NodeJS on Ubuntu:

   ```
   sudo apt install git
   sudo apt install nodejs
   ```

   `NOTE - Make sure to use the correct package manager of your Linux Distro`

   Check if you have correctly installed by running the following commands:

   ```
   node --version
   git --version
   ```

   You should see an output like this:

   <img src="images/versions-linux.png" />

   Finally, install VS Code on the system using this command(Ubuntu):

   ```
   sudo snap install code --classic
   ```

   `Make sure to refer installation guide on your distro to find the correct install command`

   </details>

2. Next, go ahead and create a [GitHub](https://github.com/) account.

3. Run the following commands to configure git on your system

   ```
   git config --global user.name "Your Name"
   git config --global user.email "youremail@email.com"
   ```

   `The email you enter here has to be the same with which you created your GitHub account`

4. Setup your GitHub account and add an SSH key. Follow
   [this](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account)
   guide.

5. Fork this repository

<img src="images/fork.png" />

6. Clone the forked repository with this command:

   ```
   git clone ...
   ```

   <!-- TODO: Add clone command -->

7. Open the repository in your favorite text editor/IDE.

8. Install npm dependencies of the project by running the following command in
   the project's root directory:

   ```
   npm install
   ```

9. Now that the dependencies are installed, you can view the working demo of the
   page by running:
   ```
   npm run dev
   ```
   Navigate to http://localhost:5173 to view the output

**Hurray!! You are now ready to contribute to the project**

## How to Contribute

`Skip steps 1 - 3 if you followed all the steps from Setup and Installation`

1. Make sure to fork this repository into your GitHub account - this way you
   will be able to create Pull Requests to merge your code in the repository.

2. Clone the forked repository in your system

3. Run `npm install` in the root directory of the cloned repository.

4. Make the changes you want to do.

5. Once you are done, commit your code to git using the following commands:

   ```
   git add .
   git commit -m "A useful commit message"
   ```

6. Push your commits to your GitHub repository

   ```
   git push -u origin master
   ```

7. Make a Pull Request

**That's it!** The PR you made would be reviewed by a Team Member of ours, and
based on the code you have written the PR would be requested for changes, if
any, and eventually Merged!

## Guidelines for Contributions

This guide helps you to follow the best practices to follow while writing code -
so that you write the best way

### Code Formatting

Formatting your code is very important - it helps to maintain consistency across
the project and also helps increase readability.

A helpful tool for code formatting is [Prettier](https://prettier.io/). You can
install it from the `Extensions` tab in VS Code:

<img src="images/prettier.png">

Look around in the repository, and find the `.prettierrc` file. This file
contains all the necessary configurations for code formatting of this project.

Now the only thing you need with prettier to format your code is to save the
file! Prettier formats code on each file save automatically!!

You can refer the following documents to know more about guidelines on how to
write better code:

- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/MDN/Writing_guidelines/Writing_style_guide/Code_style_guide)
- [FreeCodeCamp's Clean Code Guide](https://www.freecodecamp.org/news/how-to-write-clean-code/)
- [GeeksForGeeks' Guide](https://www.geeksforgeeks.org/coding-standards-and-guidelines/)

Happy Learning!
