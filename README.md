# Gexec: Documentation

[![General Workflow](https://github.com/gexec/gexec-docs/actions/workflows/general.yml/badge.svg)](https://github.com/gexec/gexec-docs/actions/workflows/general.yml) [![Codacy Badge](https://app.codacy.com/project/badge/Grade/25c2e8372c574ecd8655dc955db33a09)](https://app.codacy.com/gh/gexec/gexec-docs/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade) [![Discord](https://img.shields.io/discord/1335976189025849395)](https://discord.gg/Yda8rD4ZkJ)

Documentation for the Gexec project including the related tools and clients,
you can find this website at [gexec.eu][website].

## Hosting

The website is hosted on [Netlify][netlify], the website gets
automatically updated on every push to the `master` branch.

## Install

This website uses the [Hugo][hugo] static site generator. If you are planning to
contribute you'll want to download and install Hugo on your local machine. The
installation of Hugo is out of the scope of this document, so please take the
[official install instructions][install] to get Hugo up and running.

## Development

To generate the website and serve it on [localhost:1313](http://localhost:1313)
just execute this command and stop it with `Ctrl+C`:

```console
npm install --ci
hugo server
```

When you are done with your changes just create a pull request, after merging
the pull request the website will be updated automatically.

## Security

If you find a security issue please contact
[gexec@webhippie.de](mailto:gexec@webhippie.de) first.

## Contributing

Fork -> Patch -> Push -> Pull Request

## Authors

-   [Thomas Boerger](https://github.com/tboerger)

## License

CC-BY-SA-4.0

## Copyright

```console
Copyright (c) 2025 Thomas Boerger <thomas@webhippie.de>
```

[website]: https://gexec.eu
[netlify]: https://www.netlify.co
[hugo]: https://github.com/spf13/hugo
[install]: https://gohugo.io/overview/installing/
