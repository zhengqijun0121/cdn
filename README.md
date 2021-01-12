# cdn

jsdelivr & github

# table of contents

<!-- vim-markdown-toc GFM -->

* [jsDelivr](#jsdelivr)
    * [npm](#npm)
    * [github](#github)
    * [wordpress](#wordpress)

<!-- vim-markdown-toc -->

----

## jsDelivr

A free CDN for Open Source

fast, reliable, and automated

### npm

```
// load any project hosted on npm
https://cdn.jsdelivr.net/npm/package@version/file

// load jQuery v3.2.1
https://cdn.jsdelivr.net/npm/jquery@3.2.1/dist/jquery.min.js

// use a version range instead of a specific version
https://cdn.jsdelivr.net/npm/jquery@3.2/dist/jquery.min.js
https://cdn.jsdelivr.net/npm/jquery@3/dist/jquery.min.js

// omit the version completely to get the latest one
// you should NOT use this in production
https://cdn.jsdelivr.net/npm/jquery/dist/jquery.min.js

// add ".min" to any JS/CSS file to get a minified version
// if one doesn't exist, we'll generate it for you
https://cdn.jsdelivr.net/npm/jquery@3.2.1/src/core.min.js

// omit the file path to get the default file
https://cdn.jsdelivr.net/npm/jquery@3.2

// add / at the end to get a directory listing
https://cdn.jsdelivr.net/npm/jquery/
```

### github

```
// load any GitHub release, commit, or branch
// note: we recommend using npm for projects that support it
https://cdn.jsdelivr.net/gh/user/repo@version/file

// load jQuery v3.2.1
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/dist/jquery.min.js

// use a version range instead of a specific version
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2/dist/jquery.min.js
https://cdn.jsdelivr.net/gh/jquery/jquery@3/dist/jquery.min.js

// omit the version completely to get the latest one
// you should NOT use this in production
https://cdn.jsdelivr.net/gh/jquery/jquery/dist/jquery.min.js

// add ".min" to any JS/CSS file to get a minified version
// if one doesn't exist, we'll generate it for you
https://cdn.jsdelivr.net/gh/jquery/jquery@3.2.1/src/core.min.js

// add / at the end to get a directory listing
https://cdn.jsdelivr.net/gh/jquery/jquery/
```

### wordpress

```
// load any plugin from the WordPress.org plugins SVN repo
https://cdn.jsdelivr.net/wp/plugins/project/tags/version/file

// load an exact version
https://cdn.jsdelivr.net/wp/plugins/wp-slimstat/tags/4.6.5/wp-slimstat.js

// load the latest version
// you should NOT use this in production
https://cdn.jsdelivr.net/wp/plugins/wp-slimstat/trunk/wp-slimstat.js

// load any theme from the WordPress.org themes SVN repo
https://cdn.jsdelivr.net/wp/themes/project/version/file

// load an exact version
https://cdn.jsdelivr.net/wp/themes/twenty-eightteen/1.7/assets/js/html5.js

// add ".min" to any JS/CSS file to get a minified version
// if one doesn't exist, we'll generate it for you
```

<!-- EOF -->

