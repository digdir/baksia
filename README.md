# Baksia

- [Test site](https://blue-sand-086e7ab03.2.azurestaticapps.net/)
- [Figma prototype](https://www.figma.com/proto/oT5ZgqREUJGgYwXIgp3HWL/Baksia?page-id=707%3A4957&node-id=707%3A5045&viewport=-59%2C-4262%2C0.32&scaling=scale-down-width&starting-point-node-id=707%3A5045&hide-ui=1)

## Run site locally

Requirements: [Hugo](https://gohugo.io/installation/) (extended)

1. Clone repo:

```shell
git clone https://github.com/digdir/baksia --recurse-submodules --remote-submodules
```

2. Navigate to folder and run Hugo:

```shell
cd baksia
```

3. Install requirements

```shell
npm install
```

4. Run site locally

```shell
hugo serve --navigateToChanged
```

5. Application available locally at: `localhost:1313`

## Theme

- [digdir-hugo-theme](https://github.com/felleslosninger/digdir-hugo-theme)

## Shortcodes

For content editors:  
You may encounter something like this

```go
{{< icon class="prod-li-start-icon" >}}
```

which is a called a shortcode in Hugo. These are used to render
a specific type of a content, which content editors should ignore.

In the example above, the shortcode renders an icon.
