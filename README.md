# git-hook-script (for linux)

# Purpose

Pre-commit's use is to automatically check your java code according to specific java conventions that are called 
through rulesets.xml file. This script is called after you try to commit your changes into any branch. If script
check fails, then commit is aborted.

# How to use

1) This script is based on PMD library. So first of all you need to install PMD library.

2) Download pre-commit and rulesets.xml files and place them into ${your_project_base_folder}/.git/hooks folder.

3) DONE

# Customize

The rulesets.xml file has most java conventions and is ready for use. BUT if someone want's to have more or less
rules then all he has to do is to edit rulesets.xml file.
