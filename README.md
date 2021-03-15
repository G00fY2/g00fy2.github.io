#### Fork of [github/personal-website](https://github.com/github/personal-website) for generating a personal website hosted on github pages

### Changes I made

* Add support for company info ([24fcefe](https://github.com/G00fY2/g00fy2.github.io/commit/24fcefe212f21d1599fa57a80466705f43518ee6#diff-7cf4c69a410525138d5ebc100363d6e7))
* Add social support for Reddit and Xing ([a85e440](https://github.com/G00fY2/g00fy2.github.io/commit/a85e4401d388aa7247e9de8092c6bcb0fdeb1148#diff-30c65bcc6951e40eec5a7fffbdce31d3))
* Add personal favicon and CNAME

### Refresh content

Since GitHub Pages is static we need to rebuild this project to update the content (e.g. data, repositories, stars, ...).
Therefore I created a scheduled GitHub action to trigger rebuilding once a day.

### License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
