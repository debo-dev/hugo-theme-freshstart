# freshStart
A clear and responsive theme for [Hugo](//gohugo.io/) witch provides a dynamic environment to manage bookmarks in a clean and fast start page.


## Demo
* [Demo](http://themes.gohugo.io/theme/freshstart/)


## Screenshot
![startPageColumns = false](https://raw.githubusercontent.com/rz3n/hugo-theme-freshstart/master/images/screenshot.png)


## Installation
Inside your Hugo site directory run:
```
$ git submodule add https://github.com/rz3n/hugo-theme-freshstart.git themes/freshstart
```
For more information read the official [setup guide](//gohugo.io/overview/installing/) of Hugo.


## Configuration
Example config.yaml:
```
baseURL: http://example.org/
languageCode: en-us
title: Your site title
theme: freshStart

params:
  author: Your Name
  description: A description of your site
  favicon: /favicon.ico

  searchEngines:
    - name: Google
      activated: true
      icon: fab fa-google
      url: https://google.com/search
    - name: DuckDuckGo
      activated: true
      icon: fas fa-search
      url: https://www.duckduckgo.com

  bookmarks:
    - group: dev
      icon: fas fa-code-branch
      items:
        - name: cloudflare
          url: https://cloudflare.com
        - name: codepen.io
          url: https://codepen.io
        - name: github
          icon: fab fa-github
          url: https://github.com
        - name: gitlab
          icon: fab fa-gitlab
          url: https://gitlab.com

    - group: docs
      icon: fas fa-folder-open
      items:
        - name: docker
          url: https://docs.docker.com/

        - name: puppet
          url: https://puppet.com/docs/puppet/latest/

        - name: terraform
          url: https://www.terraform.io/docs/
    
    - group: tools
      icon: fas fa-tools
      items:
        - name: some site
          url: #
        - name: another site
          url: #

```

## Sources
* Icons from [Font Awesome](https://fontawesome.com/icons?d=gallery)


REFERENCES:
  https://github.com/gohugoio/hugoThemes#themetoml
  https://github.com/spech66/bootstrap-bp-hugo-startpage
  https://github.com/yoshiharuyamashita/blackburn

