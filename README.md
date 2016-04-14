# Jekyll Multilingual Application Structure

## Usage

[https://jekyllrb.com/docs/home/](https://jekyllrb.com/docs/home/)

## Code Structure

    ├── jekyll
    │   ├── _data
    │   │   └── .gitkeep
    │   ├── _includes
    │   │   └── templates
    │   │       ├── contact
    │   │       │   └── index.html
    │   │       └── index.html
    │   ├── _layouts
    │   │   ├── default.html
    │   │   └── master.html
    │   ├── _posts
    │   │   ├── en
    │   │   │   └── contact
    │   │   │       └── 1970-01-01-.html
    │   │   ├── fr
    │   │   │   ├── contact
    │   │   │   │   └── 1970-01-01-.html
    │   │   │   └── 1970-01-01-.html
    │   │   └── 1970-01-01-.html
    │   ├── .gitignore
    │   ├── _config.yml
    │   ├── favicon.ico
    │   └── sitemap.xml
    ├── .editorconfig
    ├── .gitattributes
    ├── .gitignore
    └── README.md

## License

This package is open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT).
