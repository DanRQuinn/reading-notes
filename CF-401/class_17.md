# Web Scraping

## Questions

- What are the key differences between scraping static and dynamic websites?

The key differences between scraping static and dynamic websites lie in their content generation and accessibility. Static websites are pre-rendered and serve the same HTML content to all users, making scraping relatively straightforward. The data can be extracted by parsing the HTML structure using libraries like BeautifulSoup or regex. In contrast, dynamic websites generate content dynamically using JavaScript, which requires additional techniques for scraping. Dynamic website scraping often involves using headless browsers or automation tools like Selenium to render and interact with the webpage, enabling access to dynamically generated content.

- Explain at least three techniques or best practices that can be employed to avoid getting blocked while scraping websites.

To avoid getting blocked while scraping websites, several techniques and best practices can be employed:

a. Implementing rate limits and delays: By introducing delays between consecutive requests and adhering to reasonable rate limits, you can mimic human browsing behavior and reduce the chances of being flagged as a bot. This can be achieved by adding random sleep intervals or using libraries that handle request throttling.

b. Rotating user agents and IP addresses: Varying the user agent strings and IP addresses used for scraping can help prevent detection and blocking. User agent rotation involves emulating different web browsers or devices, while IP rotation can be done using proxy servers or Tor networks to mask your real IP address.

c. Scraping API endpoints: Many websites provide APIs specifically for accessing their data. Utilizing these APIs can be a more reliable and efficient method of data extraction, as they are often designed for high-volume access and may have fewer restrictions compared to scraping the website directly.

- What is Playwright, and how does it assist in web scraping tasks? Provide an example of a use case where Playwright would be particularly beneficial.

Playwright is a powerful browser automation library that assists in web scraping tasks. It provides a high-level API to control web browsers, including Chromium, Firefox, and WebKit. Playwright allows you to automate interactions with web pages, such as clicking buttons, filling forms, and extracting data. It supports multiple programming languages like Python, JavaScript, and C#, making it accessible to a wide range of developers.

Playwright can be particularly beneficial for scraping dynamic websites that require JavaScript execution. It can also be used to automate tasks like testing, monitoring, and UI automation.

- Describe the purpose of using Xpath in web scraping, and provide an example of an Xpath expression to select a specific HTML element from a webpage.

Xpath is a query language for selecting nodes from an XML document. It can be used to extract data from HTML documents by traversing the HTML DOM tree. Xpath expressions can be used to select specific HTML elements based on their attributes, such as class, id, or tag name.

## Reading and links

[Scrape a Dynamic Website with Python](https://scrapingant.com/blog/scrape-dynamic-website-with-python)

[Web scraping](https://en.wikipedia.org/wiki/Web_scraping)

[How to Scrape Websites Without Getting Blocked](https://www.scrapehero.com/how-to-prevent-getting-blacklisted-while-scraping/)

[Login and Scrape Data with Playwright and Python](https://www.youtube.com/watch?v=H2-5ecFwHHQ&t=60s)

