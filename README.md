# Email Username & Domain Extractor

A simple Python program that extracts the username and domain from an email address entered by the user.

## Features

* Accepts an email address as input.
* Extracts the username (before `@`).
* Extracts the domain (after `@`).
* Displays the separated username and domain.
* Demonstrates Python string slicing and indexing.

## Requirements

* Python 3.x

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/rohitdahiya04/email-username-domain-extractor.git
```

2. Navigate to the project directory:

```bash
cd email-username-domain-extractor
```

3. Run the program:

```bash
python main.py
```

## How It Works

The program:

1. Takes an email address as input.
2. Finds the position of the `@` symbol.
3. Extracts:

   * Username: Everything before `@`
   * Domain: Everything after `@`
4. Displays the extracted information.

## Example

```text
Enter your email: rohitdahiya04@gmail.com

Your username is rohitdahiya04 and domain is gmail.com
```

## Project Structure

```text
email-username-domain-extractor/
│
├── main.py
└── README.md
```

## Skills Demonstrated

* String Manipulation
* String Slicing
* String Methods
* User Input Handling
* Variables and Data Processing

## Future Improvements

* Validate email format before processing.
* Handle invalid email addresses gracefully.
* Extract top-level domains (e.g., `.com`, `.org`, `.de`).
* Support multiple email addresses at once.

## Author

Rohit Dahiya

* GitHub: https://github.com/rohitdahiya04

## License

This project is open source and available under the MIT License.
