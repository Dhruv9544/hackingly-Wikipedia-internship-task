# Wikipedia Loop Checker



## Table Of Contents

- [About the Project](#about-the-project)
- [Built With](#built-with)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Authors](#authors)
- [Acknowledgements](#acknowledgements)

## About The Project

Ever heard of the fascinating "Wikipedia Loop" phenomenon? The Wikipedia Philosophy Loop Checker is an interactive web application/API designed to explore this well-known phenomenon. The challenge is to navigate through Wikipedia articles by clicking the first link in the main body text and eventually reaching the "Philosophy" page. This project not only determines the number of requests it takes to reach the "Philosophy" page from a given Wikipedia URL but also displays the path of visited pages along the way.

![Wikipedia Loop Checker](https://github.com/Dhruv9544/hackingly-Wikipedia-internship-task/assets/113520549/34176f27-4c30-4389-9538-109d38126c16)
![Wikipedia Loop Result](https://github.com/Dhruv9544/hackingly-Wikipedia-internship-task/assets/113520549/1e6986cd-c2e3-4b8f-9821-9de1f9feb1fa)

## Built With

- Node.js
- Express (Web framework)
- EJS (Embedded JavaScript) for templating

## Getting Started

1. **Clone the Repository:**

    ```bash
    git clone https://github.com/Dhruv9544/Wikipedia.git
    ```

2. **Navigate to Project Directory:**

   ```bash
    cd wikipedia
    ```

3. **Install Dependencies for Back-end:**

   ```bash
    npm install
    ```
    
4. **Run the Application for Back-end:**

    ```bash
    node app.js
    ```

### Prerequisites

Open your web browser and go to http://localhost:3000 to use the Wikipedia Philosophy Loop Checker.

## Usage

1. Open your web browser and go to http://localhost:3000.
2. Enter a valid Wikipedia URL in the provided input field.
3. Click the "Calculate" button to initiate the process.
4. Observe the real-time display of visited pages and the number of requests.
5. The traversal continues until the "Philosophy" page is reached, and the results are displayed.

## Authors

- **Dhruv Shah** - _I am currently a third-year student pursuing a Bachelor's in Information Technology at Vishwakarma Government Engineering College._

This README provides a brief overview, but feel free to explore the project further to experience the Wikipedia Loop firsthand!
