<p align="center">
  <img src="https://github.com/amberframework/site-assets/raw/master/images/amber.png" width="200">
  <p align="center">Productivity. Performance. Happiness.<p>
  <p align="center">
    <sup>
      <i>
        Amber makes building web applications fast, simple, and enjoyable - with fewer bugs and blazing fast performance.
      </i>
    </sup>
  </p>
  <p align="center">
    <a href="https://travis-ci.org/amberframework/amber"><img src="https://img.shields.io/travis/amberframework/amber.svg?maxAge=360"></a>
    <a href="https://github.com/amberframework/amber/releases/latest"><img src="https://img.shields.io/github/tag/amberframework/amber.svg?maxAge=360"></a>
    <a href="https://shards.rocks/github/amberframework/amber"><img src="https://shards.rocks/badge/github/amberframework/amber/status.svg"></a>
    <a href="https://github.com/amberframework/amber/blob/master/LICENSE"><img src="https://img.shields.io/github/license/amberframework/amber.svg"></a>
  <a href="https://gitter.im/amberframework/amber"><img src="https://img.shields.io/gitter/room/amberframework/amber.svg"></a>
  </p>
</p>

# Welcome to Amber

**Amber** is a web application framework written in [Crystal](http://www.crystal-lang.org) inspired by Kemal, Rails, Phoenix and other popular application frameworks.

The purpose of Amber is not to create yet another framework, but to take advantage of the beautiful Crystal language capabilities and provide engineers and the Crystal community with an efficient, cohesive, well maintained web framework that embraces the language philosophies, conventions, and guidelines.

Amber borrows concepts that have already been battle tested and successful, and embraces new concepts through team and community collaboration and analysis, which also aligns with Crystal's philosophy.

## Documentation

Read Amber documentation on https://docs.amberframework.org

## Benchmarks

[Techempower Framework Benchmarks - Round 15 (2018-02-14)](https://www.techempower.com/benchmarks/#section=data-r15&hw=ph&test=fortune&f=zik073-zik0zj-zik0zj-zik0zj-zhxjwf-zik0zj-gnbmym-cn3)

Fortunes test comparing [Amber](https://amberframework.org/), [Kemal](https://kemalcr.com/), [Rails](https://rubyonrails.org/), [Phoenix](https://phoenixframework.org/), and [Hanami](https://hanamirb.org/):

[![framework-benchmark](https://github.com/amberframework/site-assets/raw/master/images/benchmarks-fortunes.png "TFB Fortunes test for Crystal, Elixir and Ruby frameworks")](https://www.techempower.com/benchmarks/#section=data-r15&hw=ph&test=fortune&f=zik073-zik0zj-zik0zj-zik0zj-zhxjwf-zik0zj-gnbmym-cn3)

## Installation & Usage

#### macOS

```
brew install amber
```

#### Linux

```
git clone https://github.com/amberframework/amber.git
cd amber
git checkout stable
make
sudo make install
```

If you're using ArchLinux or similar distro try:

```
yaourt -S amber
```

#### Common

To compile a local `bin/amber` per project use `shards build amber`

To use it as dependency, add this to your application's `shard.yml`:

```yaml
dependencies:
  amber:
    github: amberframework/amber
```

[Read more about Amber CLI installation guide](https://amberframework.org/guides/getting-started/Installation/README.md#installation)

[Read Amber guide from zero to deploy](https://amberframework.org/guides/getting-started/quickstart/zero-to-deploy.md#zero-to-deploy)

[Read Amber CLI commands usage](https://amberframework.org/guides/getting-started/cli/README.md#cli-readme)

## Community

Questions or suggestions? Join our IRC channel [#amber](http://webchat.freenode.net/?channels=#amber) at `chat.freenode.net` or ask on our [Gitter room](https://gitter.im/amberframework/amber).

Guidelines? We have adopted the Contributor Covenant to be our [CODE OF CONDUCT](.github/CODE_OF_CONDUCT.md) for Amber.

Our Philosophy? [Read Amber Philosophy H.R.T.](.github/AMBER_PHILOSOPHY.md).

## Have an Amber-based Project?

Use Amber badge

![Amber Framework](https://img.shields.io/badge/using-amber%20framework-orange.svg)

```markdown
[![Amber Framework](https://img.shields.io/badge/using-amber%20framework-orange.svg)](Your project url)
```

## Contributing

Contributing to Amber can be a rewarding way to learn, teach, and build experience in just about any skill you can imagine. You don’t have to become a lifelong contributor to enjoy participating in Amber.

Amber is a community effort and we want You to be part of it. [Join Amber Community!](https://github.com/amberframework/amber/blob/master/.github/CONTRIBUTING.md)

1. Fork it https://github.com/amberframework/amber/fork
2. Create your feature branch `git checkout -b my-new-feature`
3. Write and execute specs `crystal spec`
4. Commit your changes `git commit -am 'Add some feature'`
5. Push to the branch `git push origin my-new-feature`
6. Create a new Pull Request

## Contributors

- [Dru Jensen](https://github.com/drujensen "drujensen")
- [Elias Perez](https://github.com/eliasjpr "eliasjpr")
- [Isaac Sloan](https://github.com/elorest "elorest")
- [Faustino Aguilar](https://github.com/faustinoaq "faustinoaq")
- [Nick Franken](https://github.com/fridgerator "fridgerator")
- [Mark Siemers](https://github.com/marksiemers "marksiemers")
- [Robert Carpenter](https://github.com/robacarp "robacarp")

[See more Amber contributors](https://github.com/amberframework/amber/graphs/contributors)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

* Inspired by [Kemal](https://kemalcr.com/), [Rails](https://rubyonrails.org/), [Phoenix](https://phoenixframework.org/), and [Hanami](https://hanamirb.org/)
