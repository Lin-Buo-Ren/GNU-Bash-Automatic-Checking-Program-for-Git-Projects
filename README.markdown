# 用於 Git 專案的 GNU Bash 腳本自動檢查程式<br>GNU Bash Automatic Checking Program for Git Projects
This is a program that checks all existing GNU Bash scripts for errors and potential issues, customized for Git repositories.

<https://github.com/Lin-Buo-Ren/GNU-Bash-Automatic-Checking-Program-for-Git-Projects>

## Deprecation Notice

This project has been superseded by [pre-commit - A framework for managing and maintaining multi-language pre-commit hooks](https://pre-commit.com/), which is far more flexible and feature-rich than this project can provide.  It is recommended to use that instead.

A sample pre-commit and Travis CI configuration has applied to this project for reference, checkout the `.pre-commit-config.yaml` and `.travis.yml` file for more info.

To manually trigger a full project bash script checking, run `pre-commit run --all-files shellcheck` under the source tree in a terminal.

## 特色<br>Features
* Only scripts in project will be checked, not scripts in submodules, that's their problem
* Directory named with \*.bash will be omitted

## 原作者<br>Original Author
林博仁 &lt;<Buo.Ren.Lin@gmail.com>&gt;

## 智慧財產授權條款<br>Intellectual Property License
[GNU GPLv3+](https://www.gnu.org/licenses/gpl.html)

```
這個專案介紹文件是基於專案介紹文件範本
This README is based on Project README Template

http://github.com/Lin-Buo-Ren/Project-README-templates
```
