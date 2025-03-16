# E-commerce Platform Search Feature Testing

This project involves testing the dynamic search functionality for a shoe-selling e-commerce platform. The project covers requirement gathering, test case design, execution, and reporting.

## Project Overview
- **Platform:** Evershop (https://demo.evershop.io/)
- **Feature:** Dynamic Search Implementation
# Q1| 
You have a shoe-selling e-commerce platform. Now, the client wants to implement a new feature "Search". During the client meeting, they mentioned they wanted to make the search dynamic, with any keywords, or specific text. Now you have a chance to get into more details on the feature. You can ask 10 questions to the client. List the questions according to priority.



# Q2|
Write down the test cases according to your questions.



# Q3|
Let's say, your development team implemented the feature on the  Evershop site 
``` bash
    https://demo.evershop.io/ 
```

Now execute your test case into the URL and generate a report.



# Q4|
Now there is a happy path journey for searching with the text “Nike react phantom run flyknit 2”. Add a couple of small-sized black products to your cart. Then verify the Cart. Now execute the journeys from both API and UI. Now provide feedback on your test analysis, keep logs of the defects, and generate a report.


 


# NOTE: 

If you find any bug keep track on Google Drive with proper naming convention, and keep the URL in your test case file.

For the API test, export the collection and share the file.






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

