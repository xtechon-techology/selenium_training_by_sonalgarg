# Selenium Training Project by Sonal Garg

This repository is designed for learning and practicing Selenium automation. The project contains various test cases simulating user interactions with an e-commerce website (e.g., Amazon) using Selenium WebDriver.

## Project Structure
selenium_training_by_sonalgarg │ ├── src │ ├── main │ │ └── java │ │ └── com │ │ └── ama │ │ └── qa │ │ ├── base │ │ │ └── TestBase.java │ │ ├── config │ │ │ └── config.properties │ │ ├── pages │ │ │ ├── AmazonHomePage.java │ │ │ ├── AmazonLoginPage.java │ │ │ ├── AmazonProductCheckoutPage.java │ │ │ ├── AmazonProductDetailsPage.java │ │ │ ├── AmazonSearchProductsPage.java │ │ │ └── ShoppingCartPage.java │ │ └── util │ └── testcases │ ├── DemoSuite ├── NullClassSeleniumProject └── Module5_XTechOn.java


## Key Components

- **Base**: 
  - `TestBase.java`: Contains setup and teardown methods for initializing the WebDriver, setting up browser configurations, and loading properties from the config file.
  
- **Config**: 
  - `config.properties`: Stores configuration data such as the browser to be used, URLs, and other environment-related settings.

- **Pages**: 
  - Each page class in the `pages` directory represents a specific page of the website being automated. These follow the Page Object Model (POM) design pattern to separate web element locators and interactions.

  - **AmazonHomePage.java**: Automates interactions with the home page (search, navigation, etc.).
  - **AmazonLoginPage.java**: Handles user login scenarios.
  - **AmazonProductCheckoutPage.java**: Manages the product checkout process.
  - **AmazonProductDetailsPage.java**: Handles interactions on the product details page.
  - **AmazonSearchProductsPage.java**: Automates search functionality.
  - **ShoppingCartPage.java**: Manages interactions with the shopping cart.

- **Utilities**:
  - Utility classes providing common functions like waiting mechanisms, data handling, and browser actions.

- **Test Cases**: 
  - Specific test cases designed to validate functionality like login, searching for a product, adding items to the cart, and checkout.

## How to Use

### 1. Clone the repository:

```bash
git clone https://github.com/xtechon-technology/selenium_training_by_sonalgarg.git
