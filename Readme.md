# Welcome to the pip Cheatsheet Repository!

This repository contains a comprehensive list of useful `pip` commands that every Python developer should know. Whether you're a beginner or an experienced developer, this cheatsheet is a great reference to keep handy.

The commands are organized in a simple and easy-to-understand manner, making it quick and convenient for you to find what you're looking for. Whether you need to list installed packages, search for a package, upgrade packages, or uninstall a package, you'll find the command you need here.

So go ahead, bookmark this repository and never struggle to remember the right `pip` command again!



</br>
</br>



## List installed packages
`pip list`

## Install a package
`pip install <package_name>`


## Install from txt file 
`pip install -r <filename.txt>`

## Upgrade a package
`pip install --upgrade <package_name>`


## Installing without using Cached Packages
`pip install <package_name> --no-cache-dir`

## Search for a package
`pip search <package_name>`

## Show information about a package
`pip show <package_name>`

## Uninstall a package
`pip uninstall <package_name>`

## List outdated packages
`pip list --outdated`

## Upgrade all packages
`pip freeze --local | grep -v '^\-e' | cut -d = -f 1  | xargs -n1 pip install -U`

## Creating a Virtual Environment
`python -m venv <name of Virtual Environment>`

## Activating a Virtual Environment
`<name_of_venv>/Scripts/activate.bat`

## Adding Packages of Virtual Environment into a `txt` File 
`pip freeze > requirements.txt`
(Note: This command will only capture packages installed in the current active virtual environment. If executed outside of a virtual environment, it will add all packages installed in the global pip directory to the specified text file.)





 
