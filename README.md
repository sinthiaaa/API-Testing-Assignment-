# E-commerce Platform Search Feature Testing

This project involves testing the dynamic search functionality for a shoe-selling e-commerce platform. The project covers requirement gathering, test case design, execution, and reporting.

## Project Overview
- **Platform:** Evershop (https://demo.evershop.io/)
- **Feature:** Dynamic Search Implementation

## Step 1: Requirement Gathering
During client discussions, the following key questions were raised to gather requirements:
1. Should the search support partial keywords or exact matches?
2. Should the search allow filtering by categories such as brand, price range, or size?
3. Is there a preference for search result sorting (e.g., relevance, price, or popularity)?
4. Should autocomplete or suggestion features be included?
5. Is typo tolerance required?
6. Should the search highlight matching text in the results?
7. Are there any performance expectations for search results?
8. Should search history be saved for users?
9. Are there any specific UI/UX expectations for the search feature?
10. How should the system handle no result scenarios?

## Step 2: Test Cases
Based on the collected requirements, the following test cases were designed:
- **Search with exact product name.**
- **Search with partial keywords.**
- **Search with misspelled words.**
- **Search with different category filters.**
- **Search with special characters or symbols.**
- **Search with empty input.**
- **Search performance testing (response time).**
- **Search result pagination testing.**
- **Testing search suggestions or autocomplete functionality.**
- **Testing for no result scenarios with proper messages.**

## Step 3: Test Execution
The implemented search feature was tested on the Evershop platform. Test cases were executed to ensure:
- Results matched the expected search terms.
- Filters and sorting options worked correctly.
- The system handled edge cases, like special characters and empty inputs, effectively.

## Step 4: Happy Path Journey
A happy path journey was conducted for the search term: **"Nike react phantom run flyknit 2"**
- Added a couple of small-sized black products to the cart.
- Verified the cart for correct product details, quantity, and total price.
- Performed the journey via both UI and API testing.

## Step 5: Test Analysis and Reporting
- Identified and logged defects during the test process.
- Ensured proper documentation of defect descriptions, reproduction steps, and severity.
- Generated a detailed test report highlighting successful test cases, failed tests, and improvement suggestions.

## Conclusion
This project successfully tested the dynamic search feature with comprehensive test coverage. The outcomes improved the search feature's accuracy, performance, and user experience.

