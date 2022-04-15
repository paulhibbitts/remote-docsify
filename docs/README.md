## Whoops

It seems you ended up here by accident. This site is meant to host the docs for other repos in the Feathers ecosystem. Add a `basePath` search param to the url to view docs. For example `?basePath=https://raw.githubusercontent.com/feathersjs-ecosystem/feathers-mongodb/master`

https://paulhibbitts.github.io/remote-docsify/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main

Known issue: a remote repo homepage does not seem to be passable as a parameter (syntax shown below), so this needs to be added in manually to the index.html file: `homepage: 'https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main/README.md',`

https://paulhibbitts.github.io/remote-docsify/?basePath=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main&homepage=https://raw.githubusercontent.com/hibbitts-design/docsify-open-course-starter-kit/main/README.md#/
