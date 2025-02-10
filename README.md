# Projector Utilities
Yes, I know JetBrains projector is deprecated. So why dont I switch?

I specifically want an in-browser code experience such as GitPod or Codespaces but using IntelliJ IDEs.

## Usage
Install using your OS's script, located in the install folder.
Here's some predetermined script <--> cloud if you need it:

**Gitpod has its own config file (`.gitpod.yml`) which can be used to change the specified operating system. The chart below uses default no-config gitpod from this repo.**

| Cloud IDE | Install Script | Notes |
| --- | --- | --- |
| GitHub Codespaces | debian-based install script | Tested on 7/13/24 |
| Gitpod | debian-based install script | Tested 2/9/25, see below!!! |
| Coder | Depends on chosen OS | Not tested |
| CodeSandbox | csb-based install + modifying (see below) | Tested on 2/9/25 |


## CodeSandbox
I set up a "devbox" with it working [here](https://codesandbox.io/p/devbox/serene-tristan-kn7599) and you can see the csb-instructions.md file in this repo for a tutorial.


## Gitpod "Classic"
Use the debian script and follow steps 4-6 from the csb-instructions.md file to fix errors.