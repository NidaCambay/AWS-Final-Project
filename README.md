# Django Blog Application with AWS Integration

## Project Overview
This is a Django-based blog application integrated with AWS services to provide a scalable and secure platform for blogging. The goal of this project is to demonstrate how to deploy a Django application on AWS and utilize various services to enhance functionality.

## Features
- **User Authentication**: Users can register, log in, and manage their profiles.
- **Blog Creation**: Users can create, edit, and delete blog posts.
- **Comments System**: Readers can leave comments on blog posts.
- **Tagging System**: Posts can be tagged for better categorization.
- **AWS S3 Integration**: Media files are stored in AWS S3 for scalability and durability.
- **Deployment on AWS**: The application is fully deployed on AWS using Elastic Beanstalk.

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/NidaCambay/AWS-Final-Project.git
   cd AWS-Final-Project
   ```
2. Set up a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```
3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```
4. Configure AWS credentials:
   Ensure your AWS credentials are set up properly to access AWS services.
5. Run the server:
   ```bash
   python manage.py runserver
   ```

## Usage Examples
- To create a new blog post:
   - Navigate to the blog creation page after logging in.
   - Fill out the form with the title and content and submit.

- To leave a comment:
   - Visit a blog post and find the comment section. Input your comment and submit it.

## Project Structure
```
AWS-Final-Project/
│
├── manage.py
├── requirements.txt
├── blog/
│   ├── migrations/
│   ├── templates/
│   ├── static/
│   └── views.py
├── users/
│   ├── migrations/
│   ├── templates/
│   └── models.py
└── config/
    ├── settings.py
    ├── urls.py
    └── wsgi.py
```

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Django Community
- AWS Documentation
- Open-source contributions
