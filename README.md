# stupid-ansible-tricks
---
## Description
This is a repo for examples of Ansible situations that I found unintuitive initally.

Under the `examples` folder are separate folders for each specifc situation I needed to see running in person to grok what was actually happening.
Each example subfolder is a standalone - the folders needed to run Ansible (e.g. roles, templates, etc.) for the specific example.  This is mostly to make it simpler to isolate each example - you shouldn't need to wade
through a ton of potentially-similarly-named playbooks and roles to prove one thing to yourself.

Each folder has a README in it that goes over what was unclear to me, what I wrote to show functionailty, and a series of commands to recreate the outcome.

INDEX.md has a list of each situation and a brief description.

---
## Development Environment Reference

For what it's worth, I use [Visual Studio Code](https://code.visualstudio.com/) as my editor of choice.  I use [Red Hat's Ansible VS Code Extension](https://marketplace.visualstudio.com/items?itemName=redhat.ansible) (with ansible-lint).
I also use ["vim's modeline magic"](https://vim.fandom.com/wiki/Modeline_magic) via this [modelines extension](https://marketplace.visualstudio.com/items?itemName=chrislajoie.vscode-modelines) to avoid having to use Red Hat's 
naming convention for VSC to properly pick up Ansible files for linting, autocomplete, etc.

As a result, you'll see "# code: language=ansible" at the top of pretty much all my YAML files to enable that functionality.  
