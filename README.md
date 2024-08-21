# Hitop

Hitop is a simple web application that displays system process information, similar to `htop`, directly in your web browser. It's built with Flask and can be used on any Linux server, cloud environment, or localhost.

## Features

- View running processes and system information in real-time
- Accessible from any web browser

## Getting Started

Follow these steps to get Hitop up and running:

1. **Clone the Repository**

    ```bash
    git clone https://github.com/abisecops/hitop.git
    ```

2. **Navigate to the Project Directory**

    ```bash
    cd hitop
    ```

3. **Install the Required Packages**

    Ensure you have `pip` installed, then run:

    ```bash
    pip install -r requirements.txt
    ```

4. **Run the Application**

    ```bash
    python app.py
    ```

5. **Open Your Web Browser**

    Go to `http://127.0.0.1:5000` to access Hitop. If you're running it on a remote server, replace `127.0.0.1` with the server's IP address.

## Usage

- **Localhost**: Run the application on your local machine and access it via `http://127.0.0.1:5000`.
- **Linux Server**: Deploy Hitop on any Linux server and access it through the server's IP address.

## Files

- `app.py`: Main application code
- `requirements.txt`: Lists necessary Python packages
- `templates/running_services.html`: HTML template for displaying running services

## Contributing

Contributions are welcome! Open issues or submit pull requests to help improve Hitop.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Inspired by `htop`
- Built using Flask

