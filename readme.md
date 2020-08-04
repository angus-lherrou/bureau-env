# Bureau-Env theme for Oh My Zsh

Modification of the Oh My Zsh [Bureau](https://github.com/ohmyzsh/ohmyzsh/blob/master/themes/bureau.zsh-theme) theme that adds a Python virtual environment label to the left of the git block.

This works for Conda environments that declare $CONDA_DEFAULT_ENV as well as Virtualenv environments. 

If both Conda and Virtualenv have active environments, the prompt defaults to the Virtualenv environment, *not* what your current `python` points to, so beware.

Don't run this and the `virtualenv` plugin at the same time! I mean, you can, but your prompt will tell you your venv twice.

### Installation

To install this plugin, simply merge the `themes` folder with `.oh-my-zsh/themes`. You can also just move the theme file to that folder, which does the same thing.
