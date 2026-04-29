# jurij-jukic.github.io

Personal website built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Local preview

Install Hugo once:

```sh
brew install hugo
```

Then run:

```sh
./bin/preview
```

Open <http://127.0.0.1:1313/>.

## New post

```sh
hugo new posts/my-post.md
```

Edit the generated file in `content/posts/` and set `draft: false` when it is ready to publish.

## Theme

PaperMod is included as a Git submodule:

```sh
git submodule update --init --recursive
```
