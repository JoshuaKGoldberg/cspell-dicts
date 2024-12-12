# CSpell GIS and PostGIS Dictionary

GIS (Geographic Information System) and [PostGIS](https://postgis.net/) dictionary for cspell.

This is a pre-built dictionary for use with CSpell.

## Installation

Global Install and add to CSpell global settings.

```sh
npm install -g @cspell/dict-gis
cspell link add @cspell/dict-gis
```

## Uninstall from CSpell

```sh
cspell link remove @cspell/dict-gis
```

## Manual Installation

Manual installation is useful if you want to include this dictionary as part of your CI/CD lint process.

```sh
npm i @cspell/dict-gis
```

The `cspell-ext.json` file in this package should be added to the import section in your `cspell.json` file.

```javascript
{
    // …
    "import": ["@cspell/dict-gis/cspell-ext.json"],
    "dictionaries": ["gis"]
    // …
}
```

# Dictionary Development

See: [How to Create a New Dictionary](https://github.com/streetsidesoftware/cspell-dicts#how-to-create-a-new-dictionary)

## License

MIT

> Some packages may have other licenses included.

<!--- @@inject: ../../static/footer.md --->

<br/>

---

<p align="center">
Brought to you by <a href="https://streetsidesoftware.com" title="Street Side Software">
<img width="16" alt="Street Side Software Logo" src="https://i.imgur.com/CyduuVY.png" /> Street Side Software
</a>
</p>

<!--- @@inject-end: ../../static/footer.md --->