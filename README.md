# learn-git

## Write code

1. Create a branch with your name
1. Create a file called `names.txt`
1. Commit it with a nice commit message
1. Add your first name to the file
1. Commit the change
1. Add your last name to the file
1. Add the change to the previous commit
1. Create a new file called `<your-name>.txt`
1. Copy the following text to the file:

   ```txt
   Commits branch like leaves,
   Merge conflicts bloom and wither,
   Git's code tree stands tall.
   ```

1. Commit the new file
1. Push your changes and create a pull request

## PR review

You got the following review on your PR:

- Change your name in the `names.txt` to be in `snake_case`
- Change your commit messages to start with `DP-666: `
- Your Commit messages should start with a capitalized present-tense verb (`Add commit message`)

  Guideline: If I use the commit, I will \_\_ (Add a feature, Fix a
  bug etc.)

## Fix the PR

1. Create a temporary commit with the message `"Fix names.txt"` that fix the file to be in `snake_case`.
1. Edit your commits with `rebase -i`, you can use the [jetbrains GUI interface](https://www.jetbrains.com/help/webstorm/edit-project-history.html#interactive-rebase)

    - Edit your commit messages
    - Squash the `"Fix names.txt"` with the original commit

1. Commit and push your changes

## Rebase main

1. Update your branch with main with `git pull --rebase main`
1. Resolve the conflict such that all the names will be in the `names.txt` file.
1. Push the Changes
1. Call me and merge the changes! :rocket:
