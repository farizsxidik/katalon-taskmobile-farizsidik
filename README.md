# katalon-taskmobile-farizsidik

# Project Testing Documentation

This document outlines the testing strategy, test cases, and test suites for our application. It serves as a guide for setting up, executing tests, and understanding the testing coverage of the application.

## Overview

The application provides users with functionalities such as adding items to a cart, checking out, editing profile information, and searching for products. This document focuses on the automated testing approach to validate these features.

## Test Environment Setup

- **Application Source**: [Download Here](https://drive.google.com/file/d/1pDaVl6G1vgj1HjB6SpLyhtmrqkwKj0oj/view?usp=drive_link)
- **Documentation**: [Access Documentation](https://drive.google.com/drive/folders/1kokVuWiC0ueFub_rceIYQoNzrZNF3z5b?usp=drive_link)

Ensure that your testing environment is properly set up according to the documentation provided.

## Test Cases

### 1. Add to Cart

- **Objective**: Verify users can add products to their shopping cart.
- **Steps**:
  1. Navigate to the product listing page.
  2. Select a product.
  3. Click the "Add to Cart" button.
  4. Go to the cart page to verify the product is added.
- **Expected Result**: The product is successfully added to the cart.

### 2. Checkout

- **Objective**: Ensure the checkout process functions correctly.
- **Steps**:
  1. Add one or more products to the cart.
  2. Proceed to the checkout page.
  3. Fill in all required shipping and payment information.
  4. Confirm the order.
  5. Verify the order completion page and confirmation.
- **Expected Result**: The checkout process is completed successfully, and an order confirmation is received.

### 3. Edit Profile Name

- **Objective**: Confirm users can edit their profile name in account settings.
- **Steps**:
  1. Go to account settings.
  2. Edit the profile name field.
  3. Save the changes.
  4. Verify the changes on the profile page.
- **Expected Result**: The profile name is updated successfully.

### 4. Search

- **Objective**: Verify the search functionality returns correct results.
- **Steps**:
  1. Use the search bar to search for a product.
  2. Review the search results.
- **Expected Result**: Search results accurately reflect the search query.

## Test Suites

### 1. Basic Function

Includes tests for fundamental features such as adding items to the cart and searching for products.

- **Test Cases**:
  - Add to Cart
  - Search

### 2. Checkout Process

Focuses on testing the checkout functionality from start to finish.

- **Test Cases**:
  - Add to Cart
  - Checkout

## Running Tests

Provide instructions on how to execute the test suites, including any necessary setup or configuration steps.

## Reporting Bugs

Explain how to report bugs found during testing, including the format and information required.


