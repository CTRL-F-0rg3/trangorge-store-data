# Trangorge Store Data

Catalog for [Uran App Store](https://github.com/CTRL-F-0rg3/uran-store).

## For users

Uran fetches the catalog from:
`https://ctrl-f-0rg3.github.io/trangorge-store-data/index.json`

## For app developers

Want your open source app in the store? Two ways:

### 1. Open a GitHub Issue (easiest)
[Submit via form](https://github.com/CTRL-F-0rg3/trangorge-store-data/issues/new?template=add-app.yml)  
A maintainer will add it to the catalog.

### 2. Open a Pull Request (fastest)
1. Fork this repo
2. Add your icon to `icons/<your-app-id>.svg`
3. Add an entry to `index.json` in the `apps` array
4. Open a PR - validation runs automatically

**Requirements:**
- Open source with OSI-approved license
- Working `download_url` (direct .tar.gz)
- Icon in SVG or PNG
- `id` must be unique

### 3. Host your own catalog (decentralized)
Just publish an `index.json` file in the same format on your own GitHub Pages / server. Users can add your URL as a custom source in Uran.

Format: see [`index.json`](index.json).

## Licensing

The catalog metadata in this repository is licensed under **GNU General Public License v3.0**. See [LICENSE](LICENSE).

All submitted applications must be open source with an OSI-approved license (GPL-3.0, MIT, Apache-2.0, BSD, etc.).
