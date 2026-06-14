[Domain Com Au Real Estate Agents Scraper](https://apify.com/easyapi/domain-com-au-real-estate-agents-scraper?fpr=data)

Extract comprehensive real estate agent data from Domain.com.au with this powerful scraper. Get detailed information about agents, their performance metrics, and agency affiliations automatically.

## Features ✨

- Extract agent contact details including phone numbers and email availability
- Get performance metrics like total properties for sale, average sold price, and days on market
- Collect agency information including names, logos, and branding details
- Support for multiple search URLs and customizable result limits
- Built-in proxy support for reliable data collection
- Automated pagination handling
- Clean, structured JSON output

## Output Data 📊

- Agent name, job title, and profile URL
- Contact information (phone, mobile)
- Performance metrics:

- Total properties for sale
- Average sold price
- Average days on market
- Total sold and auctioned properties
- Total properties for rent
- Leasing performance
- Agency details:

- Agency name
- Logo URL
- Brand colors
- Profile tier and photo URL

## Use Cases 🎯

- Lead generation for real estate services
- Market research and competitor analysis
- Real estate industry performance tracking
- Agent recruitment and talent scouting
- CRM database enrichment

### Input Example

A full explanation of an input example in JSON.

```
{   
    "searchUrls": [
        "https://www.domain.com.au/real-estate-agents/samford-valley-qld-4520/"
    ],
    "maxItems": 20
}
```

### Output sample

The results will be wrapped into a dataset which you can always find in the **Storage** tab. Here's an excerpt from the data you'd get if you apply the input parameters above:

And here is the same data but in JSON. You can choose in which format to download your data: JSON, JSONL, Excel spreadsheet, HTML table, CSV, or XML.

```
[
    {
        "searchUrl": "https://www.domain.com.au/real-estate-agents/samford-valley-qld-4520/",
        "__typename": "ContactSearchContact",
        "id": 1703257,
        "agentIdV2": "A60970",
        "agencyId": 33070,
        "name": "Georgie Haug",
        "jobTitle": "Sales Agent",
        "hasEmail": true,
        "telephone": "07 3289 3289",
        "mobile": "0411 184 561",
        "profileTier": "platinum",
        "profileUrl": "https://www.domain.com.au/real-estate-agent/georgie-haug-1703257",
        "profilePhoto": "https://rimh2.domainstatic.com.au/wvWBIU24fBOonCOrFxG3bHpsRz8=/232x232/top/filters:no_upscale():format(jpeg):quality(85)/https://images.domain.com.au/img/33070/contact_1703257.jpeg?date=637292956323758237",
        "totalForSale": 5,
        "averageSoldPrice": 2186357.1428571427,
        "averageSoldDaysOnMarket": 69.61538461538461,
        "totalSoldAndAuctioned": 14,
        "totalJointSoldAndAuctioned": 0,
        "totalForRent": 0,
        "totalLeased": 0,
        "totalJointLeased": 0,
        "agencyName": "Belle Property Samford",
        "agencyLogoUrl": "https://images.domain.com.au/img/Agencys/33070/logo_33070.png?date=638791089191288225",
        "brandColour": "#386250"
    },
    ...
]
```

## Related Actors 🤝

- [Real Estate Agents Scraper](https://apify.com/easyapi/realtor-com-agent-scraper) - Extract agent profiles from Realtor.com
- [PropertyFinder Agent Scraper](https://apify.com/easyapi/propertyfinder-agent-scraper) - Scrape agent profiles from PropertyFinder.ae
- [Rightmove Property Search Scraper](https://apify.com/easyapi/rightmove-property-search-scraper) - Extract property listings from Rightmove
- [99acres.com Scraper](https://apify.com/easyapi/99acres-com-scraper) - Scrape property listings from India's leading property portal
- [Housing.com Scraper](https://apify.com/easyapi/housing-com-scraper) - Extract property listings from Housing.com
- [Land.com Listing Scraper](https://apify.com/easyapi/land-com-listing-scraper) - Scrape land and property listings
- [VRBO Property Listing Scraper](https://apify.com/easyapi/vrbo-property-listing-scraper) - Extract vacation rental property data
- [Realtor.com Scraper](https://apify.com/easyapi/realtor-com-scraper) - Scrape real estate listings from Realtor.com
- [Trulia Property Scraper](https://apify.com/easyapi/trulia-property-scraper) - Extract property listings from Trulia
- [Funda.nl Scraper](https://apify.com/easyapi/funda-nl-scraper) - Scrape property listings from Netherlands
- [Bayut List Search Scraper](https://apify.com/easyapi/bayut-list-search-scraper) - Extract property listings from UAE
- [Dubizzle List Search Scraper](https://apify.com/easyapi/dubizzle-list-search-scraper) - Scrape property listings from UAE
- [Houzz Professional Scraper](https://apify.com/easyapi/houzz-professional-scraper) - Extract professional profiles from Houzz
- [BBB Business Directory Scraper](https://apify.com/easyapi/bbb-business-directory-scraper) - Scrape business listings from BBB
- [YellowPages.ca Scraper](https://apify.com/easyapi/yellowpages-ca-scraper) - Extract business listings from Canadian Yellow Pages