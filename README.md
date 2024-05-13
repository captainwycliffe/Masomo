Sure, here's the updated README.md with the added note about accessing the admin dashboard:

```markdown
# E-Learning System

Welcome to our E-Learning System! This application is built using Ruby on Rails and offers a comprehensive set of features to facilitate online learning. From video uploads to user progress tracking, this system provides a rich and interactive learning experience for both students and instructors.

## Features

- 📹 Video Uploads
- 🖼️ Image Uploads
- 💰 User Payments with Stripe
- 🔒 User Authentication/Authorization
- 👨‍💼 Admin Dashboard with Chart.js
- 📐 Drag n Drop Interface
- 🔁 User Progress Tracking
- 📝 WYSIWYG Rich Text Inputs
- 🔐 Premium Gated Content
- ✉️ Email Notifications
- 🚢 Fully Deployed Production Ready Build

## Installation

To install and run the E-Learning System locally, follow these steps:

1. Clone this repository to your local machine:

   ```bash
   git clone https://github.com/captainwycliffe/learning_management.git
   ```

2. Navigate into the project directory:

   ```bash
   cd learning-management
   ```

3. Install dependencies using Bundler:

   ```bash
   bundle install
   ```

4. Set up the database:

   ```bash
   bin/rails db:create
   bin/rails db:migrate
   ```

5. Start the Rails server:

   ```bash
   bin/rails server
   ```

6. Open your web browser and visit [http://localhost:3000](http://localhost:3000) to access the application.

## Deployment

If you encounter issues with deployment, ensure that your production environment is properly configured. Here are some common steps for deploying a Rails application:

- Set up your production database (e.g., PostgreSQL).
- Precompile assets: `RAILS_ENV=production rails assets:precompile`.
- Configure your web server (e.g., Nginx or Apache) to serve your Rails application.
- Set the appropriate environment variables, especially those required for services like Stripe and email notifications.
- Use a service like Render, Heroku, or AWS to host your application.

## Accessing Admin Dashboard

If you want access to the admin dashboard, please contact me at [captainwycliffe@gmail.com](mailto:captainwycliffe@gmail.com).

## Contributing

Contributions to the E-Learning System are welcome! Feel free to submit pull requests with new features, improvements, or bug fixes.

## License

This project is licensed under the MIT License.

## Acknowledgments

We would like to express our gratitude to the Ruby on Rails community for their invaluable contributions and support. Additionally, we extend our thanks to all the developers and maintainers of the libraries and tools used in this project.
```
