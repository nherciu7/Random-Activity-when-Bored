
# Activity Finder

This Express web application helps users find random activities or activities based on specific criteria using the Bored API. It provides a simple interface where users can specify the type of activities and the number of participants. The application is responsive and styled for an enjoyable user experience.

## Features

- **Random Activity Retrieval:** Fetches a random activity when the homepage loads.
- **Filtered Search:** Users can filter activities based on type and number of participants.
- **Responsive Design:** The UI is built to be responsive, ensuring it works well on both desktops and mobile devices.
- **Error Handling:** Gracefully handles errors by displaying appropriate messages to the user.

## Technologies Used

- **Node.js and Express:** For server-side logic.
- **EJS:** For templating and rendering views.
- **Axios:** For making HTTP requests to the Bored API.
- **CSS:** For styling.

## Project Structure

- `index.js`: The main server file that sets up the Express app and routes.
- `index.ejs`: The EJS template for the front-end interface.
- `main.css`: Contains all the styles applied to the front-end.

## Setup and Installation

1. **Clone the repository:**
   ```
   git clone https://github.com/yourusername/activity-finder.git
   ```
2. **Navigate to the project directory:**
   ```
   cd activity-finder
   ```
3. **Install dependencies:**
   ```
   npm install
   ```
4. **Start the server:**
   ```
   npm start
   ```

## Using the Application

- Navigate to `http://localhost:3000` in your web browser.
- To fetch a random activity, simply refresh the home page.
- To search for activities based on type and participants, use the form provided.

## Deployment

The application can be deployed on platforms like Heroku or AWS Elastic Beanstalk. Ensure you set the environment variables accordingly.

## License

This project is open source and available for everyone to use freely.

## Author

- **Herciu Nichita**
- Email: [nichitaherciu2003@gmail.com](mailto:nichitaherciu2003@gmail.com)
- GitHub: [@nherciu7](https://github.com/nherciu7)
