![Build Status](https://gitlab.com/pages/jekyll/badges/master/build.svg)
![Jekyll Version](https://img.shields.io/gem/v/jekyll.svg)

---

The NTPsec Project blog, using [Jekyll] and [GitLab Pages].

Learn more about GitLab Pages at https://pages.gitlab.io and the official
documentation http://doc.gitlab.com/ee/pages/README.html.

Learn more about NTPsec at http://ntpsec.org/

---

## GitLab CI

This project's static Pages are built by [GitLab CI][ci], following the steps
defined in [`.gitlab-ci.yml`](.gitlab-ci.yml):

Asciidoc pages are also supported by way of [Jekyll Asciidoc].  Use the
extension .adoc or .ad.

## Building locally

To work locally with this project, you'll have to follow the steps below:

* Fork, clone or download this project
* [Install][] Jekyll.  Your OS may have a package; Ubuntu's is "jekyll".
* Install the jekyll-asciidoc gem.  `sudo gem install jekyll-asciidoc`
* Generate the website: `jekyll build -d public`
* Preview your project: `jekyll serve`
* Add content

Read more at Jekyll's [documentation][].

Note that the main project (https://ntpsec.org) documentaion is
also maintained in Asciidoc, but it use a Python convertor, not
the Blog's Ruby.  There are subtle differences in implementation.

## GitLab User or Group Pages

This project is being served by GitLab pages at http://ntpsec.gitlab.io/

Read more about [user/group Pages][userpages] and [project Pages][projpages].


[Jekyll Asciidoc]:https://github.com/asciidoctor/jekyll-asciidoc
[ci]: https://about.gitlab.com/gitlab-ci/
[Jekyll]: http://jekyllrb.com/
[Gitlab Pages]:https://gitlab.com/pages/jekyll
[install]: https://jekyllrb.com/docs/installation/
[documentation]: https://jekyllrb.com/docs/home/
[userpages]: http://doc.gitlab.com/ee/pages/README.html#user-or-group-pages
[projpages]: http://doc.gitlab.com/ee/pages/README.html#project-pages

## TODO

Empty!

### recently compeleted TODO

1. Add https, TLSA, fix HSTS

2. add ntpsec logo and favicon.

3. Change GH to GL logo

4. Link check

5. unify with www.ntpsec.org css

6. asciidoc
