![Banner](https://lexis-solutions-apify.fra1.cdn.digitaloceanspaces.com/banners/opensea-top-nfts.png)

## What is OpenSea?

## 📊 Actor Stats

| Stat | Value |
|------|-------|
| **Version** | `0.0.9` |
| **Last Update** | Dec 1, 2025 |

---



## 💻 Integration Examples

This repository includes example code showing how to integrate the `opensea-top-trending-nfts-scraper` actor into your projects.

You can find example implementations in the [`examples/`](./examples) folder:
- **TypeScript/JavaScript**: See [`examples/typescript/`](./examples/typescript) for a complete TypeScript example
- **Python**: See [`examples/python/`](./examples/python) for a complete Python example

Each example includes:
- Ready-to-use code templates
- Setup instructions
- Documentation links

---



OpenSea is a platform for buying and selling digital assets on various blockchains like Ethereum, Polygon, Solana, etc. It's a marketplace for NFTs, and it's one of the most popular NFT marketplaces.

<p align="center">
  <img src="https://apify-image-uploads-prod.s3.us-east-1.amazonaws.com/SnqvUazcqTIIrSYbx/LDf2yF3tnrYL4l1F7-opensea.png" alt="OpenSea Top & Trending NFTs Scraper" style="height: 60px; margin-right: 15px;" /><a href="https://apify.com/lexis-solutions/opensea-top-trending-nfts-scraper" target="_blank">
    <img src="https://img.shields.io/badge/Try%20it%20on-Apify-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNDA4IiBoZWlnaHQ9IjQwOCIgdmlld0JveD0iMCAwIDQwOCA0MDgiIGZpbGw9Im5vbmUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+CjxnIGNsaXAtcGF0aD0idXJsKCNjbGlwMF8zNDFfNDE1NykiPgo8cGF0aCBkPSJNMjE4LjY5NSAxMDRIMzAwLjk3QzMwMi42NDMgMTA0IDMwNCAxMDUuMzU3IDMwNCAxMDcuMDNWMjMyLjc2NkMzMDQgMjM1Ljc3OCAzMDAuMDgzIDIzNi45NDUgMjk4LjQzNCAyMzQuNDI1TDIxNi4xNTkgMTA4LjY5QzIxNC44NDEgMTA2LjY3NCAyMTYuMjg3IDEwNCAyMTguNjk1IDEwNFoiIGZpbGw9IndoaXRlIi8+CjxwYXRoIGQ9Ik0xODkuMzA1IDEwNEgxMDcuMDNDMTA1LjM1NyAxMDQgMTA0IDEwNS4zNTcgMTA0IDEwNy4wM1YyMzIuNzY2QzEwNCAyMzUuNzc4IDEwNy45MTcgMjM2Ljk0NSAxMDkuNTY2IDIzNC40MjVMMTkxLjg0IDEwOC42OUMxOTMuMTU5IDEwNi42NzQgMTkxLjcxMyAxMDQgMTg5LjMwNSAxMDRaIiBmaWxsPSJ3aGl0ZSIvPgo8cGF0aCBkPSJNMjAyLjU5MSAyMDQuNjY4TDEwOS4xMjcgMjk4LjgzNUMxMDcuMjI5IDMwMC43NDcgMTA4LjU4MyAzMDQgMTExLjI3OCAzMDRIMjk2LjhDMjk5LjQ4MyAzMDQgMzAwLjg0MiAzMDAuNzcgMjk4Ljk2NyAyOTguODUyTDIwNi45MDggMjA0LjY4NUMyMDUuNzI2IDIwMy40NzUgMjAzLjc4MiAyMDMuNDY4IDIwMi41OTEgMjA0LjY2OFoiIGZpbGw9IndoaXRlIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDBfMzQxXzQxNTciPgo8cmVjdCB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgZmlsbD0id2hpdGUiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEwNCAxMDQpIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==&logoColor=white" alt="Try it on Apify" style="border-radius: 12px; height: 60px;" />
  </a>
</p>


## What is OpenSea Rankings Scraper?

OpenSea Rankings Scraper is a dedicated web scraping tool that enables you to **extract top and trending collections from the [OpenSea Rankings](https://opensea.io/rankings)** quickly and efficiently.

OpenSea Rankings allow filtering collections by categories, chains, and time periods.

You can use this scraper to:

- Scrape Top NFTs from OpenSea
- Scrape Trending NFTs from OpenSea

## What data can I extract from OpenSea Rankings Scraper?

Using this web scraper, you will be able to extract the following data from [OpenSea Top NFTs](https://opensea.io/rankings/rankings):

| Field             | Type    | Description                                 |
| ----------------- | ------- | ------------------------------------------- |
| position          | number  | Position of the collection in the rankings  |
| name              | string  | Name of the collection                      |
| logo              | string  | Logo of the collection                      |
| collectionUrl     | string  | URL of the collection                       |
| totalListed       | number  | Total number of listings in the collection  |
| listUrl           | string  | URL of the collection listings              |
| isVerified        | boolean | Whether the collection is verified          |
| isCategory        | boolean | Whether the collection is a category        |
| totalQuantity     | number  | Total quantity of the collection            |
| floorPrice        | object  | Floor price of the collection               |
| floorPrice.unit   | string  | Floor price of the collection in the unit   |
| floorPrice.eth    | string  | Floor price of the collection in ETH        |
| floorPrice.symbol | string  | Floor price of the collection in the symbol |
| numOwners         | number  | Number of owners of the collection          |
| totalSupply       | number  | Total supply of the collection              |
| numOfSales        | number  | Number of sales of the collection           |

## Why scrape top/trending NFTs from OpenSea?

- **Watch the market**: Keep track of the latest trends and changes in the NFT market.
- **Competitor analysis**: Identify direct competitors and emerging disruptors in your industry based on traffic and shares across online channels.
- **Market research**: Understand the market dynamics and identify opportunities for growth and expansion.
- **Investment decisions**: Make informed investment decisions by analyzing market trends and performance metrics.
- **Strategic planning**: Develop effective strategies for market entry, expansion, and competitive positioning.

## How to scrape top/trending NFTs from OpenSea

It's quite simple to scrape Top NFTs on OpenSea with OpenSea Rankings Scraper. Just follow the steps below and you'll get your data in a few minutes.

1. Click on the Try for free button.
2. Go to OpenSea and find the Trending NFTs section.
3. Set up your filters.
4. Copy the URL of the Trending NFTs section.
5. Paste the URL of the Trending NFTs section into the input field.
6. Click on Run.
7. When the scraping has finished, preview or download your data from the Dataset tab.

## How much will it cost to scrape OpenSea?

When it comes to scraping, it can be challenging to estimate the resources needed to extract data as use cases may vary significantly. That's why the best course of action is to run a test scrape with a small sample of input data and limited output. You’ll get your price per scrape, which you’ll then multiply by the number of scrapes you intend to do.

[Watch this video](https://www.youtube.com/watch?v=-wyz2iscZ30) for a few helpful tips. And don't forget that choosing a higher plan will save you money in the long run.

[![Watch the video](https://img.youtube.com/vi/-wyz2iscZ30/0.jpg)](https://www.youtube.com/watch?v=-wyz2iscZ30)

## Results preview

Here is an example of the output from scraping [Rankings](https://opensea.io/rankings/rankings) section of OpenSea:

```json
{
  "position": 1,
  "id": "Q29sbGVjdGlvblR5cGU6MzE0MDM4Mzk=",
  "name": "Emby",
  "slug": "emby-1",
  "logo": "https://i.seadn.io/s/raw/files/924c75539a18ea2ad9e4c40aa792190c.png",
  "collectionUrl": "https://opensea.io/collection/emby-1",
  "isVerified": true,
  "relayId": "Q29sbGVjdGlvblR5cGU6MzE0MDM4Mzk=",
  "isCategory": false,
  "totalQuantity": "2750",
  "floorPrice": {
    "unit": "0.086",
    "eth": "0.086",
    "symbol": "ETH"
  },
  "numOwners": 1003,
  "totalSupply": 2750,
  "totalListed": 34,
  "numOfSales": "102.000000000000000000",
  "listUrl": "https://opensea.io/rankings/trending?category=gaming&sortBy=one_day_volume"
}
```

## FAQ

### How many NFTs can the OpenSea Top NFTs Scraper extract?

The OpenSea Rankings Scraper will extract all rows from the OpenSea Rankings page.

### Is it legal to scrape OpenSea?

It's generally legal to scrape public websites. However, you should always check the [OpenSea Terms of Service](https://opensea.io/tos) to make sure you're not violating any rules.

### How can I scrape more NFTs?

It is possible to extend the result count up to 250 NFTs. Contact us to get a custom solution.

---

👀 p.s.

Got feedback or need an extension?

Lexis Solutions is a [certified Apify Partner](https://apify.com/partners/find). We can help you with custom solutions or data extraction projects.

Contact us over [Email](mailto:scraping@lexis.solutions) or [LinkedIn](https://www.linkedin.com/company/lexis-solutions)

## Support Our Work 💝

If you're happy with our work and scrapers, you're welcome to leave us a company review [here](https://apify.com/partners/find/lexis-solutions/review) and leave a review for the scrapers you're subscribed to. It will take you less than a minute but it will mean a lot to us!

Image Credit: OpenSea
