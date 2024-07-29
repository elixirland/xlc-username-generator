# Username Generator
This is an Elixirland exercise. Read an introduction to Elixirland here: https://github.com/elixirland.

## Status
Description: *Not Reviewed*<br>
Solution:    *In Development*

> [!NOTE]  
> The possible statuses of exercises and their example solutions are:
> 
>   1. **In Development**: Currently being developed and not ready for use.
>   1. **Not Reviewed**: Available for use but has not been reviewed. Therefore, might contain non-idiomatic Elixir.
>   1. **Reviewed**: Available for use and has been reviewed.
>
> Learn more about the reviewing process [here](https://elixirland.dev/reviewing).

## Introduction
Saša recently joined a team of developers and volunteered to build a random username generator. The team’s software requires users to log in via third-party authorization (e.g., Google, Apple, or GitHub), and each user must have a unique username. Initially, the team considered requiring users to choose their usernames upon first login, but they decided to assign random usernames instead. Users can change their usernames later in the settings.

## Task
Develop a package that allows users to generate random usernames. Ensure your implementation meets the following requirements:
  - Adheres to idiomatic Elixir practices
  - Is well-tested
  - Is easily understandable by others, not just yourself

## Requirements
### Usernames
  - The generator must be able to generate at least 600,000 unique usernames
  - Usernames must consist of existing English words
  - Words in a username are separated by a hyphen (-) by default, with an option to choose other single-character delimiters
    
### Documentation
  - A detailed README.md that provides users with all the information they need
  - Includes instructions about how to install the package
  - Includes information about the limitations of the generator

## How to get started
Fork this repository and implement your solution in the Mix app at the root directory. The solution by Elixirland is located in the directory `/solution`.

Alternatively, you can start a new Mix app by using the command `mix new`. For more information, see the [mix new](https://hexdocs.pm/mix/1.12/Mix.Tasks.New.html) documentation.
