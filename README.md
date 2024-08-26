![image](https://github.com/user-attachments/assets/701c4486-38f1-47b6-86f7-2c7c44da30a8)


# Understanding Axios by Making API Calls

Welcome to the **Understanding Axios by Making API Calls** exercise! In this project, you'll learn how to use Axios to fetch data from an API and display it in a user-friendly interface. This exercise will help you understand how to make HTTP requests, handle responses, and update the UI based on user interactions.

## Getting Started

### Prerequisites
- Node.js
- npm
- ejs

### Setup

1. **Fork the Repository**: Click the "Fork" button at the top right of this repository to create your own copy.
2. **Clone the Repository**: Clone your forked repository to your local machine using the following command:
    ```bash
    git clone https://github.com/your-username/your-repo-name.git
    ```
3. **Navigate to the Project Directory**: 
    ```bash
    cd your-repo-name
    ```
4. **Install Dependencies**: Run the following command to install all necessary packages:
    ```bash
    npm install
    ```

## Exercise Instructions

### Objective

Your task is to write code to fetch data from the Bored API using Axios. The application should allow users to click the go (submit button) and display  activities based on the type of activity and the number of participants. By default, when the user has not searched for anything, the application should display a random activity with a random number of participants.


### Steps

1. **Fetch Random Activity**: When the application loads, fetch a random activity and display it.
2. **Search Functionality**: Implement a search feature that allows users to search for activities based on the type and number of participants.
3. **Handle No Results**: If no activity matches the user's criteria, display the message "No activity that matches your criteria" on the UI.
4. **Update UI**: Update the UI to display the fetched activity details.


### API Endpoints

- **Random Activity**: `https://www.boredapi.com/api/activity/`
- **Search Activity**: `https://www.boredapi.com/api/activity?type={type}&participants={participants}`

### VIDEO DEMO


https://github.com/user-attachments/assets/5b14e0de-be5d-4db4-b8fe-dadc319b53ca


