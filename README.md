# G2 Scraper API

> **Disclaimer**: By using this G2 Scraper API, you agree to follow all applicable data scraping, copyright, and privacy laws. Please ensure that you comply with local and international regulations. The developers of this API are not liable for any misuse of scraped data.

## Overview

This API provides direct access to G2 product, vendor, user, and review data. No GUIs, no extra frills—just clean endpoints so you can retrieve the data you need.

You can view full endpoint documentation in the included **Redoc** file or by referencing the OpenAPI spec below.

## Quick Start

1. **Obtain Your API Credentials**  
   - If you’re using RapidAPI, you’ll need your `X-RapidAPI-Key` and `X-RapidAPI-Host`.
   - 'X-RapidAPI-Host' is 'g2-products-reviews-users2.p.rapidapi.com'
   - To get you 'X-RapidAPI-Key', go to the [listing](https://rapidapi.com/G2Scraper/api/g2-products-reviews-users2/pricing) on rapid api and sign up for a subscription.

2. **Check the Available Endpoints**  
   - Review the [OpenAPI spec](./OpenApiDefinition.json) (or the Redoc file) to see all available endpoints, request parameters, and response schemas.

3. **Make Your First Request**  
   - For example, to fetch a product’s info by slug:

   ```bash
   curl --request GET \
     --url 'https://g2-products-reviews-users2.p.rapidapi.com/product/slack' \
     --header 'X-RapidAPI-Key: YOUR_RAPIDAPI_KEY' \
     --header 'X-RapidAPI-Host: g2-products-reviews-users2.p.rapidapi.com'
