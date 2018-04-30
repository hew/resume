# Matthew's Resume 

[![MIT Licence](https://badges.frapsoft.com/os/mit/mit.svg?v=103)](https://opensource.org/licenses/mit-license.php)

Link: https://hew.github.io/resume

This is my professional resume. It conforms to the [fresh standard](https://github.com/fresh-standard/fresh-resume-schema), and uses
[a fresh theme](https://github.com/hew/fresh-resume-theme) that I built.

## Installation

```
# Install CLI tool
npm i -g hackmyresume
```

```
# Get my theme (optional)
git clone git@github.com:hew/fresh-resume-theme.git
```

```
## Use my theme
hackmyresume build resume.json TO public/index.all -t [path/to/theme]

## Use a build-in theme
hackmyresume build resume.json TO public/index.all -t modern
```

## Notes

* The colors, which are defined by CSS variables, will not work on IE 11.
