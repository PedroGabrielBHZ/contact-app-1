# Contacts App

This is a simple Flask-based web application for managing contacts. It provides functionalities for creating, viewing, editing, and deleting contacts. It also includes a feature to archive and download all contacts.

## Project Structure

The project is structured as follows:

- [`app.py`](command:_github.copilot.openRelativePath?%5B%22app.py%22%5D "app.py"): This is the main application file. It contains the Flask application and all the route handlers.
- [`contacts_model.py`](command:_github.copilot.openRelativePath?%5B%22contacts_model.py%22%5D "contacts_model.py"): This is the model file. It contains the `Contact` and `Archiver` classes which handle the contact data and archiving functionality respectively.
- [`requirements.txt`](command:_github.copilot.openRelativePath?%5B%22requirements.txt%22%5D "requirements.txt"): This file lists all the Python dependencies that need to be installed.
- [`static/`](command:_github.copilot.openRelativePath?%5B%22static%2F%22%5D "static/"): This directory contains static files like CSS and JavaScript files.
- [`templates/`](command:_github.copilot.openRelativePath?%5B%22templates%2F%22%5D "templates/"): This directory contains all the HTML templates.

## Setup

1. Clone the repository.
2. Install the dependencies using pip:

```sh
pip install -r requirements.txt
```

3. Run the application:

```sh
python app.py
```

The application will start on `localhost:5000`.

## Features

- **View Contacts**: The home page displays a list of all contacts. You can also search for contacts.
- **Add Contacts**: You can add a new contact by clicking on the "Add Contact" link.
- **View Contact Details**: Click on a contact to view their details.
- **Edit Contacts**: From the contact details page, you can click on "Edit" to edit the contact.
- **Delete Contacts**: From the contact details page, you can click on "Delete" to delete the contact.
- **Archive Contacts**: You can archive all contacts. The archive is a JSON file that can be downloaded.

## Technologies Used

- Python
- Flask
- HTML/CSS/JavaScript
- htmx
- hyperscript

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)
