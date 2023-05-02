# Blog Application using Django 4

This is a project repository for the Blog Application created using Django 4, as demonstrated in the "Django 4 By Examples" book by Antonio Mele.

The application allows users to view blog posts, add comments to posts, and manage the posts (create, update, and delete) through an admin interface. The project also includes authentication and authorization features to ensure that only authorized users can access the admin interface and perform management operations.

The code in this repository is a step-by-step implementation of the project described in the book, along with some additional enhancements and modifications. It's intended as a learning resource for anyone who wants to get started with Django and build a simple web application.

## Installation and Usage
To run the application, you need to install Python 3.x and Django 4.x on your local machine. Then, clone the repository and navigate to the project directory.

```sh
git clone https://github.com/osman-yasser/Blog-Application.git
cd Blog-Application
```

Next, create a virtual environment and activate it:

```sh
python3 -m venv venv
source venv/bin/activate
```

Install the required packages:

```sh
pip install -r requirements.txt
```

Finally, run the application using the following command:

```sh
python manage.py runserver
```

Open your browser and navigate to `http://localhost:8000` to access the blog application.

## Contributing
Contributions are welcome! If you find any bugs or issues with the application, feel free to create an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the `LICENSE` file for details.