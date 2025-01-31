# BharatFD Backend Assignment: Multilingual FAQ API with Django & Redis

Welcome to the BharatFD Backend Assignment repository! This project showcases the development of a **multilingual FAQ API** using Django, Django REST Framework, and Redis for caching. The system supports dynamic language translation, efficient caching, and a user-friendly admin interface.

---

## Features

- **Multilingual Support**: FAQs can be translated into multiple languages (e.g., Hindi, Bengali) using the Google Translate API.
- **WYSIWYG Editor**: Integrated Django-CKEditor for rich text formatting of FAQ answers.
- **Caching**: Utilizes Redis for fast and efficient caching of translated FAQs.
- **REST API**: Exposes a RESTful API for managing and retrieving FAQs with language-specific responses.
- **Admin Panel**: A user-friendly Django admin interface for managing FAQs.
- **Unit Tests**: Includes unit tests for models and API endpoints.

---

## Technologies Used

- **Backend**: Django, Django REST Framework
- **Database**: SQLite (default), PostgreSQL (production-ready)
- **Caching**: Redis
- **WYSIWYG Editor**: Django-CKEditor
- **Translation**: Google Translate API (`googletrans`)
- **Testing**: Django Test Framework
- **Version Control**: Git

---

## Installation

Follow these steps to set up the project locally:

### Prerequisites
- Python 3.8 or higher
- Redis (for caching)
- Git (for version control)

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/Satyajeet5275/bharatfd-backend.git
   cd bharatfd-backend
