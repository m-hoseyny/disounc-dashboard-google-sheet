# Exprloria Task


### Description

The Discount Dashboard is a web application that allows users to get discount codes based on their phone numbers. Additionally, it displays a list of previously generated discounts along with their expiration dates.

### Features

- **Get Discount Code**: Users can input their phone numbers to receive a discount code and its expiration date.
- **Display Generated Discounts**: Shows a list of all previously generated discounts.
- **Loading Spinner**: Displays a loading spinner while the discount data is being fetched.
- **Popup Modal**: A modal dialog shows the retrieved discount code and its expiration date.

### Dependencies

- The application uses Google Sheets as a backend to store and fetch discount data using Google Apps Script.

### Deployment

The application is deployed using [Vercel](https://vercel.com/), a platform for hosting static sites and serverless functions.

### Setup and Deployment

#### Prerequisites

- **Git**: Ensure you have Git installed on your machine.
- **GitHub Account**: For hosting the project’s repository.
- **Vercel Account**: For deploying the web application.

#### Steps to Clone and Deploy

1. **Clone the Repository**:
    ```bash
    git clone https://github.com/your-username/your-repository.git
    cd your-repository
    ```

2. **Push to GitHub**:
    - Create a new repository on GitHub.
    - Add the remote origin and push your code:
        ```bash
        git remote add origin https://github.com/your-username/your-repository.git
        git branch -M main
        git push -u origin main
        ```

3. **Deploy on Vercel**:
    - Go to [Vercel](https://vercel.com/), sign in, and create a new project.
    - Import your GitHub repository to Vercel.
    - Vercel will automatically detect and deploy your project.
    - Once deployed, Vercel will provide you with a live URL for your application.

### Project Structure

```plaintext
discount-dashboard/
├── index.html        # The main HTML file.
├── styles.css        # The CSS file for styling the application.
├── README.md         # This README file.