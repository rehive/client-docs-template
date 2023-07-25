<p align="center">
  <img width="64" src="https://avatars2.githubusercontent.com/u/22204821?s=200&v=4" alt="Rehive Logo">
  <h1 align="center">Client Docs Template</h1>
  <p align="center">Template project to use for creating client merchant docs</p>
</p>

## Requirements

- GIT
- Hugo (v0.100.2 extended)

## Usage

### Download/Clone

The client docs template uses a GIT submodule for its theme. Therefore, when cloning the repository ensure you do so recursively:

```sh
git clone --recurse-submodules git@github.com:rehive/client-docs-template.git
```

When pulling new changes from `master` make sure you also run the following afterwards to get the latest submodule updates.

```sh
git submodule update
```

If a submodule has been updated at its origin, then you will need to merge these updates into the repository using:

```sh
git submodule update --remote --merge
```

And then commit/push the new submodule.

### Development

To run the hugo server:

```sh
hugo serve
```

To build the static files:

```sh
hugo
```

Please take a look at the [Hugo Documentation](https://gohugo.io/documentation/) for additional usage.

### Configuration

Update the configuration in the `config.yaml` with apropriate values.

Update the `references` in the `content/checkout/_index.md` file.
