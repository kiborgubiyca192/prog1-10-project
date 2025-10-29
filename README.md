# Program Tester

**Program Tester** is a lightweight tool designed to help developers test, benchmark, and compare different programs or scripts with ease. It provides a flexible framework for running multiple programs under consistent conditions and gathering results for analysis.

## Features

- 🧪 Run and test multiple programs automatically  
- ⚙️ Support for custom test cases and configurations  
- 📊 Collect and compare performance metrics  
- 🧾 Generate simple test reports  

## Usage

```bash
# Clone the repository
git clone https://github.com/yourusername/program-tester.git
cd program-tester

# Run tests
python tester.py --config config.json

# Configuration

You can define which programs to test and how to test them in a config.json file. Example:

{
  "tests": [
    {
      "name": "Example Program",
      "command": "python example.py",
      "input": "input.txt"
    }
  ]
}

# Requirements

Python 3.8+

Any dependencies listed in requirements.txt

Contributing

Contributions, bug reports, and feature requests are welcome!
Please open an issue or submit a pull request.

License

This project is licensed under the MIT License.
