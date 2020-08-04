# Bureau-Env theme for Oh My Zsh

Modification of the Oh My Zsh [Bureau](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bureau.zsh-theme) theme that adds a Python virtual environment label to the left of the git block.

This works for Conda environments that declare $CONDA_DEFAULT_ENV as well as Virtualenv environments. 

If both Conda and Virtualenv have active environments, the prompt defaults to the Virtualenv environment, *not* what your current `python` points to, so beware.

If you still see a label for your virtualenv to the left of your prompt after you activate, add `export VIRTUAL_ENV_DISABLE_PROMPT=1` to the end of your `.zshrc`.
### Installation

To install this plugin, simply merge the `themes` folder with `.oh-my-zsh/themes`. You can also just move the theme file to that folder, which does the same thing.
