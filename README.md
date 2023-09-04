# Photobook - Django Browser Extension for Bookmarking Pictures

Photobook is a Django-based browser extension designed to simplify the process of bookmarking and saving images from any website. With Photobook, users can create an account, log in, and effortlessly save their favourite images for later viewing. This extension streamlines image bookmarking, making it a convenient tool for anyone who loves collecting and organizing visual content.

## Setting Up the Application

To set up Photobook, follow these steps:

### Prerequisites

- **Python:** Ensure you have Python (3.6 or higher) installed on your system.

### Installation

1. Clone the Photobook repository to your local machine:
   `git clone https://github.com/Codestronomer/Photobookmarker`
2. Navigate to the project directory:
  `$ cd photobookmarker`
3.  Install the required Python packages:
   `pip install -r requirements.txt`
4.  Create the database and apply migrations:
   `python manage.py migrate`
5. Start the development server:
  `python manage.py runserver`
6. Access the Photobook in your web browser at `http://localhost:8000/`.

## Usage

Using Photobook is simple:

1. **Create an Account or Log In:** If you're a new user, sign up for an account to access the full functionality of Photobook. Existing users can simply log in.

2. **Install the "Bookmark It!" Button:** Drag the "bookmark it!" button to your browser's bookmark toolbar. This button will serve as your quick access to saving images.

3. **Bookmark Images:** Whenever you find an image you want to save, click the "bookmark it!" button in your browser. This will initiate the image-saving process.

4. **Select and Save:** On the webpage with the desired image, select the image you want to bookmark. Photobook will capture your selection and prompt you to submit the form.

5. **Access Your Image Collection:** Log in to your Photobook account anytime to view your saved images. You can organize, categorize, and manage your collection effortlessly.

## Technologies Used

Photobook is built using the following technologies:

- **Django:** The web framework that powers the server side of the extension.
- **HTML and CSS:** For the front-end interface and user interaction.
- **Browser Extension:** To provide seamless integration with web browsers.
- **Database:** A database system (SQLite) to store user accounts and bookmarked images.

## Features

Photobook offers several features to enhance your image bookmarking experience:

- **User Authentication:** Create a secure account and log in to access your saved images.
- **One-Click Bookmarking:** Use the "bookmark it!" button to save images quickly and easily.
- **Image Selection:** Select specific images on a webpage for bookmarking.
- **Image Organization:** View, manage, and categorize your saved images within the extension.
- **Browser Compatibility:** Compatible with popular web browsers, including Chrome, Firefox, and Edge.

## Contributing

We welcome contributions from the community to make Photobook even better. If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.
3. Make your changes and submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions, or suggestions, or encounter any issues, please feel free to contact us at [johnrumide6@gmail.com](mailto:johnrumide6@gmail.com).

Start saving and organizing your favourite images with Photobook today!
