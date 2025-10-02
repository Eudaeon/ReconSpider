# ReconSpider

A simple script to crawl websites and retrieve:

- Emails
- Links
- External files
- JavaScript files
- Form fields
- Images
- Videos
- Audios
- Comments

This script is a modified version of the one provided in [Hack The Box Academy](https://academy.hackthebox.com/), with adjustments made to output results directly to the terminal, rather than saving them to a JSON file.

## Dependencies

ReconSpider only requires `scrapy` to work. Install it with:

```sh
pip install scrapy
```

## Usage

Simply run with:

```sh
ReconSpider <URL>
```

You can also pipe the output into `jq` to only retrieve a specific field.

```sh
ReconSpider <URL> | jq .field
```
