# G2 Scraper API 🚀

Access G2 Product, Vendor, Review, and User Data via API 

[Website](https://g2scraper.com)

[Click here for RapidAPI listing](https://rapidapi.com/G2Scraper/api/g2-products-reviews-users2)

<img alt="License" src="https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge" />

## Overview

The G2 Scraper API provides programmatic access to scraped data from G2.com, including detailed information about products, vendors, user reviews, and user profiles. Integrate G2 insights directly into your applications and workflows.

## ⚡ Features

*   **Comprehensive Data:** Access information on:
    *   Products (details, slugs, descriptions, ratings)
    *   Vendors (details, slugs, products, ratings, company info)
    *   Reviews (ratings, text content - likes/dislikes, user details, timestamps)
    *   Users (profiles, associated reviews/products)
    *   Competitors (for specific products)
    *   Autocomplete (for products, vendors, categories)
*   **RESTful API:** Simple and standard HTTP methods.
*   **JSON Responses:** Easy-to-parse data format.
*   **Hosted on RapidAPI:** Reliable and scalable access.


## 🚀 Getting Started (FREE TIER INCLUDED)

This API is available through the RapidAPI marketplace.

1.  **Subscribe on RapidAPI:**
    *   Visit the [G2 Scraper API page on RapidAPI]([https://rapidapi.com/g2scraper/api/g2-scraper-api](https://rapidapi.com/G2Scraper/api/g2-products-reviews-users2/pricing)) 
    *   Choose a pricing plan (including free tier) and subscribe.

2.  **Get Your API Key:**
    *   After subscribing, find your unique `X-RapidAPI-Key` in your RapidAPI dashboard.
    *   The required `X-RapidAPI-Host` header value is `g2-products-reviews-users2.p.rapidapi.com`.

3.  **Make Requests:**
    *   Include the `X-RapidAPI-Key` and `X-RapidAPI-Host` headers in your API requests to the base URL: `https://g2-products-reviews-users2.p.rapidapi.com`
    *   **Example (Get product info for 'slack'):**
        ```bash
        curl --request GET \
          --url 'https://g2-products-reviews-users2.p.rapidapi.com/product/slack' \
          --header 'X-RapidAPI-Host: g2-products-reviews-users2.p.rapidapi.com' \
          --header 'X-RapidAPI-Key: YOUR_RAPIDAPI_KEY'
        ```
      Replace `YOUR_RAPIDAPI_KEY` with your actual key.


## 📚 API Documentation

The complete API specification, including all endpoints, parameters, request/response schemas, and more examples, is defined in the OpenAPI 3.0 standard.

*   **View the OpenAPI Specification:** [OpenApiDefinition](OpenApiDefinition.json) 
*   **Interactive Documentation:** You can view interactive documentation generated from the spec file.
    * [View Interactive Documentation Here](https://your-documentation-link.com)

**Available Endpoint Categories:**

*   `/autocomplete`: Search products, vendors, categories.
*   `/product`: Get product details, competitors, and reviews.
*   `/vendor`: Get vendor details and their products.
*   `/user`: Get user details, their reviews, and associated products.

Refer to the full documentation for details on parameters (like `id`, `slug`, `page`, `sortOrder`, etc.).


## 📞 Support

*   For issues with the API or data, please contact [contact@g2scraper.com](mailto:contact@g2scraper.com).
*   For questions related to your RapidAPI subscription or billing, please refer to RapidAPI's support channels.
*   Found a bug or have a feature request? Open an issue on the [GitHub repository](https://github.com/biegehydra/Advanced-G2-Scraper/issues). *(<-- Update link)*


## 📄 License

This API service is governed by the terms specified on RapidAPI and the usage outlined in the disclaimer. The underlying specification format may be shared under the [MIT License](https://g2scraper.com/license).


## ⭐ Star Us

If you find this API useful, please consider starring the repository and giving it a 5 star rating on [RapidAPI](https://rapidapi.com/G2Scraper/api/g2-products-reviews-users2)


## Disclaimer

> By using the G2 Scraper API, you agree to comply with all applicable local and international laws related to data scraping, copyright, and privacy. The developers of the G2 Scraper API will not be held liable for any misuse of this service. It is the user's sole responsibility to ensure adherence to all relevant laws and G2's terms of service, and to use the API in an ethical and legal manner.

For inquiries or issues, please contact us at [contact@g2scraper.com](mailto:contact@g2scraper.com).
- Bulk purchases are available
- Scraping other sites is available
- Data analysis and visualization is available
