 # How to Create and Initialize a New Project
 1. Install Anaconda! Instructions listed in `How-to-Install-Anaconda.md` in the main directory.
 2. Open AnacondaPrompt
 3. `[Directory]` represents a sample directory that we want our project to be in. Run `cd [Directory]` to go to that directory. To go back, use `cd ..`
 4. Here's an example: `cd C:\users\User\Documents` and that would set the directory to the Documents folder.
 5. Run `conda env list` to check the environments that already exist.
 6. `[Environment Name]` represents the name that you want your project to have. Run `conda create -n [Environment Name]` to create the project.
 7. Afterwards, if it shows `Proceed? ([y]/n)?` then just type `y` and press enter.
 8. Now run `conda env list` again to check that your new environment is in the list.
 9. To activate this environment, run `conda activate [Environment Name]` Again, `[Environment Name]` represents the name of YOUR environment. Don't type this exactly into it, type your respective environment name.
 10. Run `pip install jupyter` to install jupyter or verify installation.
 11. Run `pip install numpy` to install numpy or verify installation.
 12. To open Jupyter Notebook, just run `jupyter notebook`
 13. Voila! Done!
