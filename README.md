# Contact me👋 form
This project is a simple contact form built using Node.js and Nodemailer. The project includes a minimalist and responsive design and serves as a personal exercise to understand the fundamentals of Node.js.

## Functionality:
- Users can fill out a contact form with their name, email and message.
- Upon submission, the form data is sent via email using Nodemailer.
- Utilizes serverless functions for deployment on Vercel (on branch Vercel).

### Setup:
1. Clone the repository:
    ```
    git clone <repository_url>
    ```

2. Install dependencies:
    ```
    cd <project_directory>
    npm install
    ```

3. Configure environment variables:
    - Create a `.env` file in the root directory.
    - Add the following variables:
        ```
        EMAIL_ADDRESS=your_email@gmail.com
        EMAIL_PASSWORD=your_email_password
        ```

4. Run the project locally:
    ```
    npm start
    ```

### Deployment on Vercel (optional - only for branch Vercel):
1. Ensure you have a Vercel account and the Vercel CLI installed.
   
2. Create a Vercel project:
    ```
    vercel
    ```

3. Follow the prompts to deploy the project. Select the appropriate settings, including the serverless function for handling form submissions.

### Project Structure:
- `server.js`: Main server file containing routes and server setup.
- `app/`: Directory containing serverless function for form submission on Vercel (optional).

### Dependencies:
- `express`: Web framework for Node.js.
- `nodemailer`: Module for sending emails.
- `dotenv`: Module for loading environment variables.
- Other dependencies are used for server setup and form validation.

### Notes:
- Ensure to replace placeholder email and password in the `.env` file with your actual email credentials.
- This project is intended for learning purposes and may require additional security measures for production use.

## Project Link
https://contact-form-one-zeta.vercel.app/

### Screenshot 📸
![image](https://github.com/StefaniaPaduraru/contact-form/assets/100425781/d64ec5f2-9846-4abb-bf8d-30ee30964979)
