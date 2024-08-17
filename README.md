<div align="center">
  <img src="https://starship.rs/icon.png" alt="Starship Logo" width="200" height="200">
</div>

# Zsh Setup with Ansible
This project provides an Ansible playbook to automate the installation and configuration of Zsh, Oh My Zsh, and the Starship prompt on a local machine. It ensures that all necessary dependencies are installed and configured properly.

## Table of Contents

- [What is Zsh?](#what-is-zsh)
- [What is Starship?](#what-is-starship)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installing](#installing)
- [Usage](#usage)

### What is Zsh?

Zsh (Z shell) is a powerful and highly customizable Unix shell that extends the Bourne shell (sh) with many improvements. It includes features such as improved tab completion, spell correction, and a rich scripting language. Zsh is often preferred by developers and power users for its flexibility and advanced features.

### What is Starship?

Starship is a cross-shell prompt that is fast, customizable, and packed with features. It works with various shells, including Zsh, Bash, Fish, and others. Starship provides a minimal and informative prompt that can be easily configured to display information such as the current directory, Git status, and more. It aims to be the minimal, blazing-fast, and infinitely customizable prompt for any shell.

## Getting Started <a name = "getting_started"></a>

Clone the repository and run the Ansible playbook to install Zsh, Oh My Zsh, and Starship. 

### Prerequisites

Ensure you have the following installed on your machine:

- Ansible
- curl
- unzip

### Installing

Follow these steps to get your development environment running:

1. **Clone the repository:**
    ```sh
    git clone https://github.com/Immain/Zsh-Ubuntu.git
    cd Zsh-Ubuntu
    ```
    
2. **Run the Ansible playbook:**
    ```sh
    ansible-playbook zsh.yml
    ```

After running the playbook, you need to run exec zsh to see the changes.

3. **Run exec zsh:**
    ```sh
    exec zsh
    ```

## Usage <a name = "usage"></a>

After running the playbook, Zsh will be set as your default shell, and the Starship prompt will be configured. You can start using Zsh by opening a new terminal session or by running exec zsh.
