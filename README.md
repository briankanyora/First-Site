# First-Site

## Project Title: First-Site
## Description:
First-Site is a web project dedicated to the exploration, development, and testing of dynamic web applications. The primary objective of this project is to create a versatile website that serves as a movie library, allowing users to rent or buy movies. This project will leverage various technologies, including Python, Flask, HTML, CSS, JavaScript, and a suitable database to deliver an interactive and engaging user experience.

## Project Overview
The First-Site project is initiated and maintained by an associate software engineer who is eager to enhance and put their software engineering skills to the test. The project will encompass various aspects of web development and software engineering, making it an excellent opportunity to learn and grow in the field.

## Features
- Movie Database: A comprehensive collection of movies with detailed information such as title, genre, release date, and synopsis.

- User Accounts: Users can create accounts, log in, and manage their profiles.

- Movie Rental and Purchase: Users can browse movies and choose to either rent or purchase them.

- Search and Filter: A search feature and filters allow users to easily find the movies they want.

- Reviews and Ratings: Users can leave reviews and rate the movies they have watched.

- Responsive Design: The website will be designed to work seamlessly on various devices and screen sizes.

- Secure Transactions: Payment processing will be securely implemented to ensure user data safety.

## Getting Started
### Windows Prerequisites
Before setting up and running First-Site, ensure you have the following software installed:
 - Python 3.10 >
 - Flask

Installation
1. Clone this repository to your local machine.
```
git clone https://github.com/briankanyora/First-Site
```
2. Navigate to the project directory. 
```
cd first-site
```
3. Create a virtual environment and activate it.
```
python -m venv venv
venv\Scripts\activate
```
4. Install project dependencies. 
```
pip install -r requirements.txt
```
### MacOS Prerequisites
Before setting up and running First-Site, ensure you have the following software installed:

 - Python 3.10 >
 ```
 https://www.python.org/downloads/macos/
 ```
 - Homebrew: Paste the code below in macOS Terminal
 ```
 /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
 ```
You may need to restart your machine after the software is installed.

Installation
1. Clone this repository to your local machine:
 ```
 git clone https://github.com/briankanyora/First-Site
 ```
2. Navigate to the project directory:
 ```
 cd First-Site
 ```
3. Install virtualenv.
 - Open terminal window. 
 - If you dont have virtualenv installed, run the following command:
```
 pip install virtualenv
```
4. Create the virtual environment.
 - Run the following command to create a virtual environment named ```venv```:
```
 virtualenv venv
```
 - If you want to use a specific Python version, use the `-p` flag:
 ```
 virtualenv -p python3.10 venv
 ```
5. Activate the virtual environment.
 - Run the following command to activate the virtual environment:
 ```
 source venv/bin/activate
 ```
 - You'll see the name of the virtual environment in parentheses at the beginning of your terminal prompt.
6. Install project dependencies. 
 ```
 pip install -r requirements.txt
 ```
7. Deactivate the virtual environment.
 - When you are done working in the virtual environment, deactive using;
 ```
 deactivate
 ```
8. Additional Tips:
 - Add `venv` to `.gitignore`: If you're using Git, add the virtual environment directory to your `.gitignore` file to prevent it from being committed to your repository.

> [!NOTE]
> Add the following two later:
> 5. Set up your database and update the configuration in config.py to point to your database.
> 6. Initialize the database.

## Contributing
Contributions to this project are welcome! Feel free to open issues, submit pull requests, or provide feedback to help improve First-Site.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
If you have any questions or need further information, you can contact the project owner at briankanyora@gmail.com.

Thank you for your interest in the First-Site project. We hope you enjoy working on this dynamic movie library and expanding your software engineering skills. Happy coding!