# PHP Simple Form

A basic PHP form example demonstrating how to create an HTML form and handle form submissions securely using PHP.

## Features

- Simple form with **Name** and **Email** fields
- Basic form validation (required fields)
- PHP script to process form data and sanitize inputs to prevent XSS
- Easy to understand and extend for beginners

## Getting Started

### Prerequisites

- A local or remote web server with PHP support (e.g., XAMPP, WAMP, MAMP, or a live server)

### How to Use

1. Clone or download this repository.
2. Place the files (`form.html` and `process.php`) in your web server’s root directory or a subfolder.
3. Open `form.html` in your browser (e.g., `http://localhost/form.html` if running locally).
4. Fill out the form and submit.
5. The form data will be sent to `process.php` and displayed on the page.

## File Structure

- `form.html` — The HTML form for user input.
- `process.php` — PHP script to handle form submission and display sanitized input.

## Security

- User inputs are sanitized using `htmlspecialchars()` to prevent Cross-Site Scripting (XSS) attacks.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to contribute or suggest improvements!
