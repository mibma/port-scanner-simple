# Simple Port Scanner

This is a simple port scanner script written in Python. It allows you to scan a range of ports on a target IP address or hostname to check if they are open.

## Features

- Scans a specified range of ports on a target IP address or hostname
- Displays which ports are open
- Handles exceptions and provides informative error messages

## Requirements

- Python 3.x

## Installation

1. Clone the repository or download the script file.

    ```sh
    git clone https://github.com/yourusername/repository-name.git
    ```

2. Navigate to the project directory.

    ```sh
    cd repository-name
    ```

## Usage

1. Open a terminal or command prompt.
2. Navigate to the directory containing the `scanner.py` script.
3. Run the script with the target IP address or hostname.

    ```sh
    python scanner.py <target>
    ```

    Replace `<target>` with the IP address or hostname you want to scan. For example:

    ```sh
    python scanner.py 192.168.154.1
    ```

## Example

```sh
$ python scanner.py example.com
--------------------------------------------------
Scanning target example.com
Time started: 2024-07-03 12:34:56.789012
--------------------------------------------------
Checking port 50
Checking port 51
Checking port 52
...
Checking port 84
Port 80 is open
--------------------------------------------------
Scan completed
--------------------------------------------------
