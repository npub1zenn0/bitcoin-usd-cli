# Bitcoin to USD Converter

This is a Python script that converts a specified amount of Bitcoin in Satoshis to its equivalent value in US Dollars using the XBT/USD price from the Kraken API.

## Requirements

- Python 3.x
- `requests` module (you can install it using `pip install requests`)

## Usage

Run the script with the desired amount of Satoshis as a command-line argument. You can specify the amount as an integer or a floating-point number, optionally followed by a suffix "k" or "M" to represent thousands or millions of Satoshis, respectively.

For example, to convert 500,000 Satoshis to its equivalent value in US Dollars, run:

```python3
./bitcoin-usd 500000
./bitcoin-usd 500k
./bitcoin-usd 0.5M
```

The script will output the USD value rounded to 2 decimal places.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Attribution

The code and this readme were all written by chatGPT.
