# ReconSpider

ReconSpider is a web crawling script that retrieves:

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

## Usage

ReconSpider only requires `scrapy` to work. Install it with:

```sh
pip install scrapy
```
Additionally, you can use `jq` to parse the output and only retrieve a specific field.

```sh
ReconSpider <URL> | jq .field
```
