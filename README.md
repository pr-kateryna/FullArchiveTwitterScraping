# FullArchiveTwitterScraping
FullArchiveTwitterScraping is a project that uses Twiiter API endpoint to retrieve full archive Twitter data for analytical purposes.

## Prerequisites
- Python version > 3.9
- Create Twitter developer account and create a Twitter developer application ID.
  - Ex.
    - https://developer.twitter.com/en/docs/twitter-ads-api/apply
    - https://developer.twitter.com/en/products/twitter-api/academic-research
- Poetry version > 1.1.10
## Install

1. clone this repository.
2. Install PyPI packages.
   ```bash
   $ poetry install
   ```
## Run

1. Fill configurations in [script](api-json-scraping.py) (ex. Twiiter API token).
2. Run scraping script.
     ```
     $ poetry run python api-json-scraping.py 
     ```


## License

FullArchiveTwitterScraping is [MIT licensed](./LICENSE)
