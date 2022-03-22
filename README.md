# hugo-static-site-generator.txt

## check if you have Hugo installed and update Hugo

```
hugo version
brew install hugo
brew cleanup hugo
hugo version
```

# Create a new site with Hugo

```
hugo new site quickstart

ls -la

cd quickstart
```

## Get / install a theme for your Hugo site

```
git init

git submodule add https://github.com/theNewDynamic/gohugo-theme-ananke.git themes/ananke

```

## add the new theme into your site's config file

```
echo theme = \"ananke\" >> config.toml
```

## add a new post to the blog

```
hugo new posts/my-first-post.md\n

code .
```

## edit the post in /content/posts and then start the hugo local web server in development mode

```
hugo server -D
```
