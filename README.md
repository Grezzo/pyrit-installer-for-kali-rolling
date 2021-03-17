# About

Installing pyrit in Kali Rolling 2021.1 is a bit of a pain. It will appear to compile and install ok, but you'll end up with errors [like this](https://github.com/JPaulMora/Pyrit/issues/591) when you try to run it.

This script installs all the dependancies needed in a default Kali 2021.1 system then fudges the code before compillation to work around the issue. The fudge is inspired by [this comment](https://github.com/JPaulMora/Pyrit/issues/591#issuecomment-622267954).

# Usage

1. Review `install-pyrit-kali-rolling-2021-1.sh` to ensure that it's not doing anything you don't want it to.
2. Run the folllowing command on Kali:

```
curl https://raw.githubusercontent.com/Grezzo/pyrit-installer-for-kali-rolling/main/install-pyrit-kali-rolling-2021-1.sh | bash
```
