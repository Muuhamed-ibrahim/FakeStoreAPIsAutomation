# FakeStore Postman Project

## Overview
The FakeStore Postman Project is a comprehensive API testing suite designed to interact with a simulated e-commerce platform. This project utilizes Postman collections and Newman to automate API requests and validate responses, ensuring the reliability and functionality of the fake store's endpoints for managing products, users, and carts.

## Installation
To get started with the FakeStore Postman Project, follow these steps:

1. **Clone the Repository**: Begin by cloning the repository to your local machine:

    ```bash
    git clone (https://github.com/Muuhamed-ibrahim/FakeStoreAPIsAutomation.git)
    ```

2. **Install Newman**: If Newman is not already installed, you can install it globally using npm:

    ```bash
    npm install -g newman
    ```

## Usage
Execute the following steps to run the collection and generate the HTML report:

1. **Navigate to Project Directory**: Open your terminal and change to the project directory:

    ```bash
    cd fakestore-postman
    ```

2. **Run Newman**: Execute the collection using Newman and generate an HTML report with htmlextra:

    ```bash
    newman run fakestore_collection.json -r htmlextra
    ```

    This command triggers the collection run and generates a detailed HTML report for review.

## Features
The FakeStore Postman Project includes the following features:

1. **Products**: Test endpoints related to managing products, including fetching product details, adding new products, updating existing products, and deleting products.

2. **Users**: Validate user-related endpoints, such as user registration, authentication, profile management, and user deletion.

3. **Carts**: Test functionality related to managing shopping carts, including adding items to the cart, updating quantities, removing items, and checking out.

## Report
Upon completion of the collection run, you can find the HTML report in the `reports` directory. Open `index.html` in your web browser to access the comprehensive test results, including request details, assertions, and response data.

## Contributing
Contributions to the FakeStore Postman Project are highly appreciated. To contribute, follow these guidelines:

1. **Fork the Repository**: Fork the repository to your GitHub account.
2. **Create a Feature Branch**: Create a new branch for your feature or enhancement.
3. **Make Changes**: Implement your changes, adhering to coding standards and best practices.
4. **Submit a Pull Request**: Once your changes are complete, submit a pull request to the main repository for review.

## License
The FakeStore Postman Project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
For inquiries, feedback, or assistance, please contact [mohamedibrahem87899@gmail.com][[www.linkedin.com/in/mohamed-ibrahim-44352822b]
