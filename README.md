# rust-www

This repository contains the source files for rust-lang.org.

## Deployment

![TravisCI Badge](https://travis-ci.org/rust-lang/rust-www.svg)

The site is built with TravisCI and automatically deployed to S3.

## Testing Locally

To install jekyll (and any other dependencies, if we get any):

```
bundle install
```

To run this website as a developer:

```
jekyll serve
```

This will serve the site at `localhost:4000`.
