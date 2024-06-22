# Resumegen - Web Based PDF Resume Generator

Welcome to Resumegen, a Python Django based application designed for generating PDF resumes online.

## Features

- **User Authentication**: Secure login system for registered users.
- **Resume Template Selection**: Choose from a variety of templates for your resume.
- **Data Entry**: Input your personal, educational, and professional information.
- **PDF Generation**: Generate a downloadable PDF resume based on entered data.
- **Admin Dashboard**: Manage users and templates via an admin panel.

## Installation

Follow these steps to set up Resumegen on your local machine:

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd resumegen
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Initialize database:
   ```bash
   python manage.py migrate
   ```

4. Create a superuser (admin):
   ```bash
   python manage.py createsuperuser
   ```

5. Start the development server:
   ```bash
   python manage.py runserver
   ```

6. Open your web browser and navigate to `http://localhost:8000` to view the app.

## Usage

- **User Registration and Login**: Create a new account or login with existing credentials.
- **Create Resume**: Input personal details, educational background, and work experience.
- **Select Template**: Choose from available resume templates.
- **Generate PDF**: Download a professionally formatted PDF resume.
- **Admin Dashboard**: Access admin features at `http://localhost:8000/admin` to manage users and templates.

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/my-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/my-feature`).
6. Create a new Pull Request.

## License

This project is licensed under the [MIT License](LICENSE).
```

Replace `<repository-url>` with the actual URL of your GitHub repository where the Django application is hosted. This README template includes sections tailored to a web-based PDF resume generator application named "Resumegen," focusing on features such as user authentication, resume creation, template selection, PDF generation, and administration. Adjust and expand sections as per your project's specific requirements and features.
