# ELECTRICITYMAPS_CONTRIB

> Anticloud offline package — upstream: electricitymaps/electricitymaps-contrib @ `master`.

## What This Project Does

The open source repository for Electricity Maps data parsers that powers the world's most comprehensive electricity data platform

**Topics:** app, climate-change, data-visualization, electricity, electricity-consumption, electricity-prices, electricitymap, electricitymaps, hacktoberfest, map, sustainability

## Upstream README

<p align="center">
  <a href="https://app.electricitymaps.com">
    <picture>
      <source
        srcset="https://raw.githubusercontent.com/electricitymaps/electricitymaps-contrib/master/.github/images/electricity-maps-logo-dark.svg"
        media="(prefers-color-scheme: dark)"/>
      <img
        alt="Electricity Maps"
        src="https://raw.githubusercontent.com/electricitymaps/electricitymaps-contrib/master/.github/images/electricity-maps-logo.svg"
        width="100"/>
    </picture>
  </a>
</p>
<h1 align="center">
  Electricity Maps
</h1>

<p align="center">
A collection of parsers to collect and standardize electricity data such as production, exchanges and price from across the globe.<br>
  <strong><a href="https://app.electricitymaps.com">app.electricitymaps.com »</a></strong>
</p>

<p align="center">
  <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/electricitymaps/electricitymaps-contrib"/>
    <a href="https://github.com/electricitymaps/electricitymaps-contrib/blob/master/LICENSE.md">
    <img src="https://img.shields.io/github/license/electricitymaps/electricitymaps-contrib" alt="Electricity Maps is released under the GNU-AGPLv3 license." /></a>
</p>

![image](.github/images/electricity-maps-banner.png#gh-light-mode-only)
![image](.github/images/electricity-maps-banner-dark.png#gh-dark-mode-only)

## Introduction

This project aims to provide a free, open-source, and transparent way to collect electricity data.

We fetch the raw data from public, free, and official sources. They include official government and transmission system operators' data. This data powers the [Electricity Maps platform](https://electricitymaps.com), which includes [our flow-tracing algorithm](https://www.electricitymaps.com/blog/flow-tracing), estimation models, forecast engine and much more.

_View it online [app.electricitymaps.com](https://app.electricitymaps.com), or download the app on [Google Play](https://play.google.com/store/apps/details?id=com.tmrow.electricitymap&utm_source=github) or the [App store](https://itunes.apple.com/us/app/electricity-map/id1224594248&utm_source=github)._

## Contributing

Electricity Maps collection of parsers is a community project and we welcome contributions from anyone!

We are always looking for help to build parsers for new countries, fix broken parsers, improve accuracy of data sources, discuss new potential data sources, update region capacities, and much more.

Read our [contribution guidelines](/CONTRIBUTING.md) to get started.

## Community & Support

Use these channels to be part of the community, ask for help while using Electricity Maps, or just learn more about what's going on:

- [GitHub Issues](https://github.com/electricitymaps/electricitymaps-contrib/issues): Raise any issues you encounter with the data or bugs you find while using the app.
- [GitHub Discussions](https://github.com/electricitymaps/electricitymaps-contrib/discussions): Join discussions and share new ideas

## License

Upstream terms preserved in `THIRD_PARTY_LICENSES/`. Overlay licensed under Anticommons 0.1.0.

## Verification

Recompute the SHA3-256 of `BENCH.json` and compare to this package’s register. Any drift = invalid package.
