# Supported Git Editors

Here are some commonly used editors and how to set them as the default Git editor:

1. **Vim**:  git config --global core.editor "vim"

2. **Nano**: git config --global core.editor "nano"

3. **Visual Studio Code**: git config --global core.editor "code --wait"

4. **Sublime Text**: git config --global core.editor "subl -n -w"

5. **Atom**: git config --global core.editor "atom --wait"

6. **Notepad++** (Windows): git config --global core.editor "'C:/Program Files/Notepad++/notepad++.exe' -multiInst -notabbar -nosession -noPlugin"

7. **Emacs**: git config --global core.editor "emacs"

8. **Visual Studio**: git config --global core.editor "'C:/Program Files/Microsoft Visual Studio/2022/Community/Common7/IDE/devenv.exe' -w"

These commands set the specified editor as the default for Git. The `--wait` or equivalent flag ensures that Git waits for the editor to close before proceeding.
