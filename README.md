## 🤖 [Informa Markets Exhibitor List Scraper](https://apify.com/skython/informa-markets-exhibitor-list-scraper)

Simple web scraper for extracting exhibitor data from trade show exhibitor lists provided by **Informa Markets**. Easily scrape company profiles including **company details, websites, social media links, product categories, and more**. 

Ideal for **B2B lead generation, market research, event networking, and competitive analysis**. Supports multiple **Informa Markets** exhibition websites with a consistent HTML structure.

> [Apify](https://apify.com/) is a cloud platform and marketplace for web scraping and automation tools.

---

## Contents

- [Features](#features)

- [Use Cases](#use-cases)

- [Supported Website Structure](#supported-website-structure)

- [Supported Informa Markets Events (Exhibitor Lists)](#supported-informa-markets-events-exhibitor-lists)

- [Testing Exhibitor List URLs](#testing-exhibitor-list-urls-for-free)

- [Exhibitor List Scraper - All-In-One Version](#exhibitor-list-scraper---all-in-one-version)

- [Data Fields](#data-fields)

- [Example Output](#example-output)

- [My Other Exhibitor List Scrapers](#my-other-exhibitor-list-scrapers)

---

## Features

- Scrape all exhibitor profiles from supported Informa Markets event websites

- Extract detailed data from every exhibitor profile page

- Company primary information (address, email, website)

- Social media links (LinkedIn, Facebook, Instagram, Twitter, YouTube)

- Contact person details

- Product categories with full hierarchical structure

- Two output formats (Single-Row & Multi-Row)

- Multi-Row format for Excel-friendly product category filtering

- Export to JSON, CSV, and Excel

---

## Use Cases

- **B2B Lead Generation:** Build targeted contact lists for marketing and sales outreach. 

- **Market Research:** Analyze exhibitors by product categories, brands, and sectors.  

- **Event Networking:** Familiarize yourself with exhibitors before attending trade fairs.  

- **Competitive Analysis:** Track competitor participation and product focus areas.

---

## Supported Website Structure

- This scraper is designed to extract data from exhibitor directories with the same HTML structure as the supported Informa Markets exhibitor lists below.

- Take a look at some of the event websites from the below list. Your event website URL might be in that list.

- If you are not sure about if this actor is capable of scraping your event URL, test it with [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor.

---

## Supported Informa Markets Events (Exhibitor Lists)

> The following partial list includes Informa Markets exhibitor directory URLs that have been tested so far. Other Informa Markets events or different events with the same website structure may also be supported.

> Some event URLs may have been updated or canceled entirely; please check them before using.

### 2026

- [World Health Expo (WHX) Miami 2026 Exhibitor List – worldhealthexpo.com](https://www.worldhealthexpo.com/events/healthcare/miami/en/attend/exhibitor-list.html)

- [World Health Expo (WHX) Miami 2026 Exhibitor List – app.swapcard.com/event/whx-miami-2026-1](https://app.swapcard.com/event/whx-miami-2026-1/exhibitors/RXZlbnRWaWV3XzEyNjc1NzM=)

- [Vitafoods Europe 2026 Exhibitor List – visitor.vitafoodsglobal.com/event/vitafoods-europe-2026](https://visitor.vitafoodsglobal.com/event/vitafoods-europe-2026/exhibitors/RXZlbnRWaWV3XzEyNDIzNjc=)

- [Natural Products Expo West 2026 Exhibitor List – expowest.com](https://www.expowest.com/en/exhibitor-list/2026-exhibitor-list.html)

- [Natural Products Expo West 2026 Exhibitor List – attend.expowest.com/event/natural-products-expo-west-2026](https://attend.expowest.com/event/natural-products-expo-west-2026/exhibitors/RXZlbnRWaWV3XzEyMjU1ODQ=)

- [Seafood Expo Global 2026 Exhibitor List – seafoodexpo.com/global](https://www.seafoodexpo.com/global/exhibitor-lists/)

- [Seafood Expo Global 2026 Exhibitor List – connectglobal.seafoodexpo.com/event/seafood-expo-global-2026](https://connectglobal.seafoodexpo.com/event/seafood-expo-global-2026/exhibitors/RXZlbnRWaWV3XzEyMzE4MTk=)

- [Expo Riva Schuh 2026 Exhibitor List – exporivaschuh.it](https://exporivaschuh.it/en/exhibitor-list-ers)

- [Expo Riva Schuh 2026 Exhibitor List – gardabags.exporivaschuh.it/event/104-ers](https://gardabags.exporivaschuh.it/event/104-ers/exhibitors/RXZlbnRWaWV3XzExNjMyMDM=)

- [ForMobile 2026 Exhibitor List – formobile.com.br](https://www.formobile.com.br/en/visit/list-of-exhibitors.html)

- [ForMobile Xperience 2026 Exhibitor List – app.informamarkets.com.br/event/formobile-xperience-2026](https://app.informamarkets.com.br/event/formobile-xperience-2026/exhibitors/RXZlbnRWaWV3XzEwNzg4NTE=)

- [HIMSS 2026 Exhibitor List – app.himssconference.com/event/himss-2026](https://app.himssconference.com/event/himss-2026/exhibitors/RXZlbnRWaWV3XzEyMTIxNDU=)

- [Intermodal South America 2026 Exhibitor List – intermodal.com.br](https://www.intermodal.com.br/en/exhibiting-companies/)

- [Intermodal 2026 Exhibitor List – app.informamarkets.com.br/event/intermodal-2026](https://app.informamarkets.com.br/event/intermodal-2026/exhibitors/RXZlbnRWaWV3XzEyMTg5MTI=)

- [kbb Birmingham 2026 Exhibitor List – kbb.co.uk](https://www.kbb.co.uk/en/exhibitors.html)

- [kbb Birmingham 2026 Exhibitor List – app.kbb.co.uk/event/kbb-2026](https://app.kbb.co.uk/event/kbb-2026/exhibitors/RXZlbnRWaWV3XzEyMjQ0NTY=)

- [Seafood Expo North America 2026 Exhibitor List – seafoodexpo.com/north-america](https://www.seafoodexpo.com/north-america/exhibitor-lists/)

- [Seafood Expo North America 2026 Exhibitor List – connectna.seafoodexpo.com/event/sena26](https://connectna.seafoodexpo.com/event/sena26/exhibitors/RXZlbnRWaWV3XzEyMTA3MDY=)

- [SupplySide Connect New Jersey 2026 Exhibitor List – newjersey.supplysideconnect.com](https://newjersey.supplysideconnect.com/en/expo/event-information/exhibitor-list.html)

- [SupplySide Connect New Jersey 2026 Exhibitor List – attendees.supplysideshow.com/event/supplyside-connect-new-jersey-2026](https://attendees.supplysideshow.com/event/supplyside-connect-new-jersey-2026/exhibitors/RXZlbnRWaWV3XzEyMzEzMTM=)

- [VERTICON 2026 Exhibitor List – verticon.org](https://verticon.org/exhibitors-list/)

- [VERTICON 2026 Exhibitor List – events.verticalavi.org/event/verticon-2026](https://events.verticalavi.org/event/verticon-2026/exhibitors/RXZlbnRWaWV3XzEyMDk2NzE=)

- [Winter Fancy Faire 2026 Exhibitor List – events.specialtyfood.com/event/winter-fancyfaire](https://events.specialtyfood.com/event/winter-fancyfaire/exhibitors/RXZlbnRWaWV3XzEyMTQzMDM=)

- [Fispal Food Service 2026 Exhibitor List – app.informamarkets.com.br/event/fispal-food-service-2026](https://app.informamarkets.com.br/event/fispal-food-service-2026/exhibitors/RXZlbnRWaWV3XzEyNDY3NDA=)

- [Feimec 2026 Exhibitor List – app.informamarkets.com.br/event/feimec-2026](https://app.informamarkets.com.br/event/feimec-2026/exhibitors/RXZlbnRWaWV3XzEyMTA2ODM=)

- [Hospitalar Hub 2026 Exhibitor List – app.informamarkets.com.br/event/hospitalar-hub-2026](https://app.informamarkets.com.br/event/hospitalar-hub-2026/exhibitors/RXZlbnRWaWV3XzEyMDgwMzg=)

- [Fispal Technologia 2026 Exhibitor List – fispaltecnologia.com.br](https://www.fispaltecnologia.com.br/en/exhibit/exhibitors-list/)

- [Fispal Technologia 2026 Exhibitor List – informamarkets.com.br/event/fispal-tecnologia-e-tecnocarne-2026](https://app.informamarkets.com.br/event/fispal-tecnologia-e-tecnocarne-2026/exhibitors/RXZlbnRWaWV3XzEyMzc0MjI=)

- [Gardabags 2026 Exhibitor List – exporivaschuh.it](https://exporivaschuh.it/en/exhibitor-list-gb)

- [Gardabags 2026 Exhibitor List – gardabags.exporivaschuh.it/event/104-ers](https://gardabags.exporivaschuh.it/event/104-ers/exhibitors/RXZlbnRWaWV3XzExNjMyMDU=)

- [World Health Expo Dubai 2026 Exhibitor List – worldhealthexpo.com/events/healthcare/dubai](https://www.worldhealthexpo.com/events/healthcare/dubai/en/attend/exhibitor-list.html)

- [World Health Expo Dubai 2026 Exhibitor List – connections.whxevents.com/event/whx-dubai-2026](https://connections.whxevents.com/event/whx-dubai-2026/exhibitors/RXZlbnRWaWV3XzEyMjUzMzU==)

- [World Health Expo Labs Dubai 2026 Exhibitor List – worldhealthexpo.com/events/labs/dubai](https://www.worldhealthexpo.com/events/labs/dubai/en/attend/exhibitor-list.html)

- [World Health Expo Labs Dubai 2026 Exhibitor List – connections.whxevents.com/event/whx-labs-dubai-2026](https://connections.whxevents.com/event/whx-labs-dubai-2026/exhibitors/RXZlbnRWaWV3XzEyMzAyMTY=)

- [Concrete Show 2026 Exhibitor List – app.informamarkets.com.br/event/concrete-show-2026](https://app.informamarkets.com.br/event/concrete-show-2026/exhibitors/RXZlbnRWaWV3XzEyNDc5Njk=)

- [Middle East Energy 2026 Exhibitor List – middleeast-energy.com](https://www.middleeast-energy.com/en/exhibit/exhibitor-directory.html)

- [Middle East Energy 2026 Exhibitor List – attend.imenergy.virtual.informamarkets.com/event/middle-east-energy-2026-1](https://attend.imenergy.virtual.informamarkets.com/event/middle-east-energy-2026-1/exhibitors/RXZlbnRWaWV3XzEyMzY3NTU=)

- [Fi South America 2026 Exhibitor List – visitor.figlobal.com/event/fi-south-america-2026](https://visitor.figlobal.com/event/fi-south-america-2026/exhibitors/RXZlbnRWaWV3XzEyMzQ1Mzk=)

- [Fi South America 2026 Exhibitor List – figlobal.com/south-america](https://www.figlobal.com/south-america/exhibitor-list/)


### 2025

- [SupplySide Global 2025 Exhibitor List – supplysideglobal.com](https://www.supplysideglobal.com/expo/event-information/exhibitor-list/)

- [SupplySide Global 2025 Exhibitor List – attendees.supplysideshow.com/event/supplyside-global-2025](https://attendees.supplysideshow.com/event/supplyside-global-2025/exhibitors/RXZlbnRWaWV3XzEwNDY0ODE=)

- [Plastico Brasil Xperience 2025 Exhibitor List – app.informamarkets.com.br/event/plastico-brasil-xperience-2025](https://app.informamarkets.com.br/event/plastico-brasil-xperience-2025/exhibitors/RXZlbnRWaWV3Xzc3MjMwNA==)

- [Fi Africa & ProPak MENA 2025 Exhibitor List – visitor.figlobal.com/event/fi-africa-and-propak-mena-3](https://visitor.figlobal.com/event/fi-africa-and-propak-mena-3/exhibitors/RXZlbnRWaWV3XzEwMzkzNzg=)

- [Cityscape Global 2025 Exhibitor List – cityscapeglobal.com](https://cityscapeglobal.com/exhibitors-list-exhibit)

- [Cityscape Global 2025 Exhibitor List – visit.cityscapeglobal.com/event/cityscape-global-2025](https://visit.cityscapeglobal.com/event/cityscape-global-2025/exhibitors/RXZlbnRWaWV3XzEwNzU5MTg=)

- [Futurecom Xperience 2025 Exhibitor List – app.informamarkets.com.br/event/futurecom-xperience-2025](https://app.informamarkets.com.br/event/futurecom-xperience-2025/exhibitors/RXZlbnRWaWV3XzEwOTQ3NjE=)

- [Brazil Windpower 2025 Exhibitor List – app.informamarkets.com.br/event/brazil-windpower-2025](https://app.informamarkets.com.br/event/brazil-windpower-2025/exhibitors/RXZlbnRWaWV3XzEwODU3OTk=)

- [Food ingredients Asia 2025 Exhibitor List – visitor.figlobal.com/event/food-ingredients-asia-2025](https://visitor.figlobal.com/event/food-ingredients-asia-2025/exhibitors/RXZlbnRWaWV3XzEwOTMwMDU=)

---

## Testing Exhibitor List URLs for FREE

- Since I have multiple exhibitor list scraper actors for different types of trade event websites, it might be hard to find the correct actor for your exhibitor list URL.

- Use [**Exhibitor List Scrapers URL Tester**](https://apify.com/skython/exhibitor-list-scrapers-router) actor to test your exhibitor list URLs **for FREE** and see which scraper can process them.

---

## Exhibitor List Scraper - All-In-One Version

- I also provide an **All-In-One** version that combines **my 30+ exhibitor list scrapers** into a single actor.

- Instead of searching for the correct scraper for each event URL, simply provide the event URL and the actor automatically selects the appropriate scraper.

- ➡️ [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

---

## Data Fields

<table>
  <thead>
    <tr>
    <th><span style="font-size:14px;">Company</span></th>
    <th><span style="font-size:14px;">Social</span></th>
    <th><span style="font-size:14px;">Additional</span></th>
    </tr>
  </thead>
    <tbody>
        <tr>
            <td>Profile URL</td>
            <td>LinkedIn</td>
            <td>Hall Stands</td>
        </tr>
        <tr>
            <td>Company Name</td>
            <td>Facebook</td>
            <td>Product Categories</td>
        </tr>
        <tr>
            <td>Address</td>
            <td>Instagram</td>
            <td>Contact Persons</td>
        </tr>
        <tr>
            <td>Website</td>
            <td>Twitter / X</td>
            <td></td>
        </tr>
        <tr>
            <td>Email</td>
            <td>YouTube</td>
            <td></td>
        </tr>
    </tbody>
</table>

---

## Example Output

```json
{
  "___exhibitor_profile_url": "https://events.specialtyfood.com/event/winter-fancyfaire/exhibitor/RXhoaWJpdG9yXzIzMjIwOTA=",
  "__company_name": "Hey Grill Hey",
  "_company_country": "United States",
  "_company_website": "https://heygrillhey.com",
  "_hall_stands": "4115",
  "_social_url_linkedin": "https://www.linkedin.com/company/hey-grill-hey",
  "_social_url_facebook": "https://www.facebook.com/heygrillhey",
  "_social_url_instagram": "https://www.instagram.com/heygrillhey",
  "_social_url_youtube": "https://www.youtube.com/@Heygrillhey",
  "trend_s": ["SenseMaxxing"],
  "has_a_new_product": "Yes",
  "state": "Utah",
  "diverse_owned_business": ["Woman/Women"],
  "contact_persons": [
    {
      "_name": "Susie Bulloch",
      "job_title": "Founder, Chef",
      "organization": "Hey Grill Hey",
      "linkedin": "https://www.linkedin.com/in/susie-bulloch"
    }
  ],
  "product_categories": [
    {
      "title": "Seasonings & Spices",
      "subcategories": [
        {
          "title": "Spices",
          "subcategories": null
        },
        {
          "title": "Rubs",
          "subcategories": null
        }
      ]
    },
    {
      "title": "Condiments, Dressings, Marinades",
      "subcategories": [
        {
          "title": "BBQ Sauce",
          "subcategories": null
        }
      ]
    },
    {
      "title": "Non-Food Products/Services",
      "subcategories": [
        {
          "title": "Cookbooks",
          "subcategories": null
        }
      ]
    }
  ]
}
```

---

## My Other Exhibitor List Scrapers

- [Exhibitor List Scraper - All-In-One](https://apify.com/skython/exhibitor-list-scraper)

- [Koelnmesse Exhibitor List Scraper](https://apify.com/skython/koelnmesse-exhibitor-list-scraper)

- [Messe Frankfurt Exhibitor List Scraper](https://apify.com/skython/messe-frankfurt-exhibitor-list-scraper)

- [Map Your Show Exhibitor List Scraper](https://apify.com/skython/map-your-show-exhibitor-list-scraper)

- [Messe Düsseldorf Exhibitor List Scraper](https://apify.com/skython/messe-duesseldorf-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper](https://apify.com/skython/xporience-exhibitor-list-scraper)

- [Reed Expo Exhibitor List Scraper](https://apify.com/skython/reed-expo-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper)

- [Xporience Exhibitor List Scraper V2](https://apify.com/skython/xporience-exhibitor-list-scraper-2)

- [Nürnberg Messe Exhibitor List Scraper](https://apify.com/skython/nuernberg-messe-exhibitor-list-scraper)

- [GSMA MWC Exhibitor List Scraper](https://apify.com/skython/gsma-mwc-exhibitor-list-scraper)

- [Messe Berlin Exhibitor List Scraper](https://apify.com/skython/messe-berlin-exhibitor-list-scraper)

- [AFAG Messe Exhibitor List Scraper](https://apify.com/skython/afag-messe-exhibitor-list-scraper)

- [Messe Stuttgart Exhibitor List Scraper](https://apify.com/skython/messe-stuttgart-exhibitor-list-scraper)

- [Messe Essen Exhibitor List Scraper](https://apify.com/skython/messe-essen-exhibitor-list-scraper)

- [Informa Markets Exhibitor List Scraper V2](https://apify.com/skython/informa-markets-exhibitor-list-scraper-2)

- [Ungerboeck Exhibitor List Scraper](https://apify.com/skython/ungerboeck-exhibitor-list-scraper)

- [A2Z Events Exhibitor List Scraper](https://apify.com/skython/a2z-events-exhibitor-list-scraper)

- [Deutsche Messe Exhibitor List Scraper](https://apify.com/skython/deutsche-messe-exhibitor-list-scraper)

- [Newfront Exhibitor List Scraper](https://apify.com/skython/newfront-exhibitor-list-scraper)

- [Goeshow Exhibitor List Scraper](https://apify.com/skython/goeshow-exhibitor-list-scraper)

- [EasyFairs Exhibitor List Scraper](https://apify.com/skython/easyfairs-exhibitor-list-scraper)

- [IEG Expo Exhibitor List Scraper](https://apify.com/skython/ieg-expo-exhibitor-list-scraper)

- [The Smarter E Exhibitor List Scraper](https://apify.com/skython/the-smarter-e-exhibitor-list-scraper)

- [Schall Messen Exhibitor List Scraper](https://apify.com/skython/schall-messen-exhibitor-list-scraper)

- [Messe München Exhibitor List Scraper V2](https://apify.com/skython/messe-muenchen-exhibitor-list-scraper-2)

- [Comexposium Exhibitor List Scraper](https://apify.com/skython/comexposium-exhibitor-list-scraper)

- [IME Events Exhibitor List Scraper](https://apify.com/skython/ime-events-exhibitor-list-scraper)

- [ANDMORE Exhibitor List Scraper](https://apify.com/skython/andmore-exhibitor-list-scraper)

- [Comexposium Exhibitor List Scraper V2](https://apify.com/skython/comexposium-exhibitor-list-scraper-2)

- [Informa Markets Exhibitor List Scraper V3](https://apify.com/skython/informa-markets-exhibitor-list-scraper-3)