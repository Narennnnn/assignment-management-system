# Assignment Management System

The Assignment Management System is a Flask-based web application designed to manage student assignments, allowing teachers to grade assignments and principals to oversee the process.

## Setup Instructions

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Narennnnn/assignment-management-system.git
   ```

2. **Navigate to the project directory:**
   ```bash
   cd assignment-management-system
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Running with Docker

1. **Build the Docker image:**
   ```bash
   docker build -t assignment-management-system .
   ```

2. **Run the Docker container:**
   ```bash
   docker run -p 5000:5000 assignment-management-system
   ```

3. **Access the application:**
   Visit \`http://localhost:5000\` in your browser.

## Testing

To run the tests, use pytest:
```bash
pytest
```

This will execute the test suite and display the results.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License

This project is licensed under the [MIT License](LICENSE).
EOF
