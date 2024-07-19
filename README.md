# Username Generator
This is an Elixirland challenge. Read an introduction to Elixirland here: https://github.com/elixirland.

## Status
This repository is **NOT REVIEWED** and **WORK IN PROGRESS**. This status will be set to "reviewed" when enough feedback has been given on the code and documentation in the `solution` directory.

You can provide feedback by [opening an issue](https://github.com/elixirland/xlc-username-generator/issues/new) or contributing to this repository's [discussions](https://github.com/elixirland/xlc-username-generator/discussions).

## Description
### Background
Saša recently joined a team of developers and volunteered to build a random username generator. The team’s software requires users to log in via third-party authorization (e.g., Google, Apple, GitHub), and each user must have a unique username. Initially, the team considered requiring users to choose their usernames upon first login, but they decided to assign random usernames instead. Users can change their usernames later in the settings.

### Task
Develop a package that allows users to generate random usernames. Ensure your implementation meets the following requirements:
  - Adheres to idiomatic Elixir practices
  - Is well-tested
  - Is easily understandable by others, not just yourself

### Requirements
#### Usernames
  - The generator must be able to generate at least 600,000 unique usernames
  - Usernames must consist of existing English words
  - Words in a username are separated by a hyphen (-) by default, with an option to choose other single-character delimiters
    
#### Documentation
  - A detailed README.md that provides users with all the information they need
  - Includes instructions about how to install the package
  - Includes information about the limitations of the generator

## How to get started
Fork this repository and implement your solution in the Mix app at the root directory. The solution by Elixirland is located in the directory `/solution`.

Alternatively, you can start a new Mix app by using the command `mix new`. For more information, see the [mix new]([https://hexdocs.pm/phoenix/Mix.Tasks.Phx.New.html](https://hexdocs.pm/mix/1.12/Mix.Tasks.New.html)) documentation.
