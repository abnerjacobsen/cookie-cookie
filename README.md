![Cookie Cookie Logo](assets/img/cookie-cookie-logo.png "Cookie Cookie Logo")

# cookie-cookie
A project template for... project templates...

## Features
- Inspired by [cookiecutter-template](https://github.com/eviweb/cookiecutter-template)
- See [cookiecutter-git](https://github.com/tuxredux/cookiecutter-git#features) Features

## Requirements
- [git](https://git-scm.com/downloads)
- [python](https://www.python.org/downloads/)
- [cookiecutter](https://github.com/audreyr/cookiecutter)

## Usage
    $ cookiecutter gh:tuxredux/cookie-cookie
    # OR
    $ cookiecutter https://github.com/tuxredux/cookie-cookie

### Example
See [cookie-cookie-example](https://github.com/tuxredux/cookie-cookie-example)

    $ tree -a -I .git cookie-cookie-example
    cookie-cookie-example
    ├── AUTHORS.md
    ├── CHANGELOG.md
    ├── CONTRIBUTING.md
    ├── cookiecutter.json
    ├── {{cookiecutter.repository_slug}}
    │   ├── AUTHORS.md
    │   ├── CHANGELOG.md
    │   ├── CONTRIBUTING.md
    │   ├── {{cookiecutter.package_name}}
    │   │   └── .gitkeep
    │   ├── .gitignore
    │   ├── LICENSES
    │   │   ├── AGPL-3.0.txt
    │   │   ├── Apache-2.0.txt
    │   │   ├── BSD-2-Clause.txt
    │   │   ├── BSD-3-Clause.txt
    │   │   ├── EPL-1.0.txt
    │   │   ├── GPL-2.0.txt
    │   │   ├── GPL-3.0.txt
    │   │   ├── LGPL-2.1.txt
    │   │   ├── LGPL-3.0.txt
    │   │   ├── MIT.txt
    │   │   ├── MPL-2.0.txt
    │   │   └── Unlicense.txt
    │   ├── NOTICE
    │   └── README.md
    ├── .gitignore
    ├── hooks
    │   └── post_gen_project.py
    ├── LICENSE
    ├── NOTICE
    └── README.md

    4 directories, 28 files

## Development
See [CONTRIBUTING](CONTRIBUTING.md)

## History
See [CHANGELOG](CHANGELOG.md)

## Credits
See [AUTHORS](AUTHORS.md)

## License
See [LICENSE](LICENSE), [NOTICE](NOTICE)
