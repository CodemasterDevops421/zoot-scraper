
```markdown
# CodeMaster Zoot Scraper

## Overview

The CodeMaster Zoot Scraper is an advanced tool designed to automate data extraction from Zoot, a leading fashion retail website in the Czech Republic, Slovakia, and Romania. This scraper allows users to efficiently harvest detailed product information, streamlining market research and competitive analysis.

## Features

- **Custom Product Queries**: Input specific product URLs or search criteria to extract data directly from Zoot's product pages.
- **Comprehensive Data Extraction**: Gather key product details such as name, brand, price, sizes, and more.
- **Highly Configurable**: Adjust scraper settings to handle dynamic site content or to wait for specific elements before extraction begins.

## Getting Started

Configure the scraper with URLs or search criteria, and customize settings to suit your data needs:

### Example Input

```json
{
    "urls": [
        "https://www.zoot.cz/polozka/3123456/elegant-dress"
    ],
    "waitForSelector": ".product-description"
}
```

### Example Output

```json
{
    "id": "3123456",
    "url": "https://www.zoot.cz/polozka/3123456/elegant-dress",
    "name": "Elegant Dress",
    "brand": "Trendy Brand",
    "price": "2 500 Kč",
    "sizesAvailable": ["XS", "S", "M"],
    "description": "Elegant evening dress perfect for special occasions.",
    "images": [
        "https://image.zoot.cz/example/dress_front_3123456.jpeg",
        "https://image.zoot.cz/example/dress_back_3123456.jpeg"
    ],
    "categoryPath": ["Home", "Women", "Dresses", "Evening Dresses"]
}
```

## Integrations

Seamlessly integrate scraped data with your systems using Apify SDK or connect through popular platforms like Zapier for automation.

## Support and Updates

For support inquiries, feature requests, or updates, please reach out through our dedicated channels.

---

**Connect with Quick Life Solutions**:
- **YouTube**: [Visit our channel](https://www.youtube.com/channel/UCSglWXooehH8Cy7LYHhXtqA)
- **Instagram**: [Follow us on Instagram](https://www.instagram.com/quicklifesolutionsofficial/)
- **AI Newsletter**: [Subscribe to our newsletter](https://sendfox.com/quicklifesolutions)
- **Free Consultation**: [Book a free consultation call](https://tidycal.com/quicklifesolutions/free-consultation)
- **More Tools**: [Explore our Apify actors](https://apify.com/dainty_screw)
- **Discord**: [Raise a Support ticket here](https://discord.gg/2WGj2PDmHb)
- **Contact Email**: [codemasterdevops@gmail.com](mailto:codemasterdevops@gmail.com)

Harness the power of web scraping to enhance your business strategy with the CodeMaster Zoot Scraper. Start extracting valuable fashion retail data today!
```
