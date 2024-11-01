# Pet Store API Performance Testing

This project performs API performance testing on the Pet Store application using JMeter. It automates tests on various pages, including the Home page, Pet, Store, and User pages, with test data sourced from an Excel file named **Pet Store Data**.

## Features

- **Page Testing**: Validates the performance of:
  - **Home Page** (Cute PetStore)
  - **Pet Page**
  - **Store Page**
  - **User Page**
- **Data-Driven Testing**: Utilizes data from an Excel file to drive API requests.
- **Result Analysis**:
  - **View Results Tree**: View detailed request and response data.
  - **Graph Results**: Visualize performance metrics in graphical form.
  - **View Results in Table**: Tabular view of request timings and response data.
  - **Graph Storage**: Saves performance results in graph format for easy reference.

---

# Reqres_API_Performance_Testing

This project uses JMeter to test the Reqres API for performance across different request types. The test plan, includes various HTTP requests, header management, and response extraction, It features a comprehensive test plan structured into two thread groups to simulate different load scenarios: one with a 1 thread and another with 50 threads.

## Features

- **Request Types**:
  - **POST Request**: Creates a new user.
  - **GET Request**: Retrieves user information.
  - **PUT Request**: Updates user data.
  - **GET Request**: Fetches updated user information.
  - **DELETE Request**: Removes a user.
- **Header Management**: HTTP Header Manager used for consistent request headers.
- **Data Extraction**: JSON Extractor to capture specific response data.
- **Result Analysis**:
  - **View Results Tree**: Detailed logging of requests and responses.
  - **Aggregate Report**: Summarized performance metrics.
  - **Graph Results**: Visualizes API performance over time.
  
This performance testing framework allows users to assess the behavior and responsiveness of the Reqres API under varying load conditions.
