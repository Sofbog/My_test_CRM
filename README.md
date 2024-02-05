
# My Test CRM

## Introduction

This project is a simple yet powerful Customer Relationship Management (CRM) system designed to help businesses manage their customer interactions, support, and relationships. It provides an intuitive interface for tracking customer information, communications, sales opportunities, and more.

## Installation

To get started with this CRM system, you will need Python and pip installed on your machine. Follow these steps:

1. Clone the repository:

```bash
git clone https://github.com/Sofbog/My_test_CRM.git
cd My_test_CRM
```

2. Install the necessary Python packages:

```bash
pip install -r requirements.txt
```

## Setup

After installation, perform initial setup and migrations to prepare the database:

```bash
python manage.py makemigrations
python manage.py migrate
```

## Usage

To run the CRM application, use:

```bash
python manage.py runserver
```

Navigate to `http://localhost:8000` in your web browser to access the CRM interface.

## Features

- **Customer Management**: Easily add, update, and remove customer information.
- **Interaction Tracking**: Keep track of all customer interactions, including calls, emails, and meetings.
- **Sales Pipeline**: Manage and track sales opportunities through different stages of the sales process.
- **Reporting**: Access various reports to gain insights into customer behavior and sales performance.

## Contributions

We welcome contributions to improve this CRM system. If you have suggestions or encounter issues, please open an issue or submit a pull request.

## License

This project is open-sourced under the MIT License.
