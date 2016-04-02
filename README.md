# aglio-docker

Dockerfile for aglio that spares you the hassle of installing NPM toolchain.

## Usage

Go to your blueprint's root dir:

```
$ cd ~/projects/awesome-twitter-clone
```

Start aglio docker:

```
docker run --rm -it -v $(pwd):/tmp iterators/aglio-docker aglio -i BLUEPRINT.md -o doc.html
```

Enjoy your documentation:

```
chromium doc.html
```

## Author & license

If you have any questions regarding this project contact:

Łukasz Sowa <lukasz@iterato.rs> from [Iterators](https://iterato.rs).

For licensing info see LICENSE file in project's root directory.
