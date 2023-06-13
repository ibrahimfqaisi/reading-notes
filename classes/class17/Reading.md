# Q: What are the key differences between scraping static and dynamic websites?

"""
Static websites are those that do not change frequently. The content on these websites is typically stored in HTML files and does not require any interaction with a database. This makes them relatively easy to scrape, as you can simply download the HTML files and extract the data you need.

Dynamic websites, on the other hand, change frequently. The content on these websites is typically stored in a database and is generated on the fly when a user requests a page. This makes them more challenging to scrape, as you need to interact with the website to obtain the desired data.
"""

# Q: Explain at least three techniques or best practices that can be employed to avoid getting blocked while scraping websites.

"""
1. Use rotating proxies: By using rotating proxies, you can send your requests through different IP addresses, making it harder for websites to detect and block your scraping activity.

2. Implement request delays: Adding delays between your requests helps simulate human browsing behavior and prevents triggering anti-scraping mechanisms like rate limiting or IP blocking. You can use the `time.sleep()` function to introduce delays.

3. Randomize User-Agent headers: Websites often track User-Agent headers to identify scraping activities. Randomizing your User-Agent headers or rotating through a pool of User-Agent strings can help avoid detection and blockage. You can use libraries like `fake_useragent` to generate random User-Agent headers.
"""

# Q: What is Playwright, and how does it assist in web scraping tasks? Provide an example of a use case where Playwright would be particularly beneficial.

"""
Playwright is a Python library that provides a high-level API for browser automation. It allows you to control web browsers like Chrome, Firefox, and WebKit, making it useful for web scraping tasks.

One beneficial use case of Playwright is scraping dynamic websites. Dynamic websites heavily rely on JavaScript to generate content. Playwright excels in scraping such websites by fully rendering and executing JavaScript, providing an accurate representation of the website's behavior. This enables scraping of dynamically loaded data, such as content loaded via AJAX requests, which would be difficult with traditional scraping methods.
"""

# Q: Describe the purpose of using XPath in web scraping, and provide an example of an XPath expression to select a specific HTML element from a webpage.

"""
XPath is a language used to navigate and query XML or HTML documents. In web scraping, XPath is employed to locate specific elements within a webpage's HTML structure.

An example of an XPath expression to select a specific HTML element from a webpage using Python's `lxml` library is:

```python
from lxml import etree

# Assuming `html_content` contains the HTML source code of the webpage
tree = etree.HTML(html_content)
selected_elements = tree.xpath('//div[@class="product-name"]')
```
