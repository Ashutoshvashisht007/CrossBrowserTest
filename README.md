## EL PAÍS Scraper – Cross Browser Test

This project performs automated scraping of EL PAÍS Opinion section across multiple browsers using BrowserStack.
It extracts article titles, translates them using RapidAPI Translate service, and stores results in JSON format.

### Features
- Cross-browser testing (Chrome, Firefox, Safari, Edge, etc.)
- Parallel execution using multiple threads
- Article title scraping from EL PAÍS Opinion section
- Spanish → English translation using RapidAPI
- Repeated word analysis in translated titles
- JSON export of scraped data
- Download and save the cover image of each article 

### Tech Stack
- Node.js
- Selenium WebDriver
- BrowserStack
- RapidAPI Translate API
- dotenv

### Installation
- Clone the repository: ```git clone CrossBrowserTest```



### Install dependencies:

- npm install

### Environment Setup

- Create a .env file in root folder:
   - ```BROWSERSTACK_USERNAME=your_username```
   - ```BROWSERSTACK_ACCESS_KEY=your_access_key```
   - ```RAPID_API_KEY=your_rapidapi_key```

### How to Run Tests

- Run the scraper: ```node index.js```