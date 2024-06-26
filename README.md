# Set or Reset DNS Servers using Python and PowerShell

This script allows you to set or reset DNS servers on your Windows system to connect to [Shecan](https://shecan.ir/) DNS using Python and PowerShell.

## Installation

1. Ensure you have Python installed on your system.
2. Clone this repository:

    ```bash
    git clone https://github.com/MoeeinAali/SheCan/
    ```

3. Navigate to the project directory:

    ```bash
    cd SheCan
    ```
4. Make sure you have **administrative privileges** to run the script.

## Usage

### Set DNS Servers

To set DNS servers to Shekan DNS addresses, run the script with the argument `1`. For example:

```bash
python SheCan.py 1
```
This will set the DNS servers to Shekan DNS addresses specified in the script.

### Reset DNS Servers

To reset DNS servers to obtain automatically, run the script with the argument `0`. For example:

```bash
python SheCan.py 0
```
This will reset DNS servers to obtain automatically.



