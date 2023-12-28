# BMIProCalc

BMIProCalc is a web application that allows users to calculate their Body Mass Index (BMI) based on their height, weight, age, gender, and preferred unit system (metric or imperial). The application also provides a history feature to view past BMI calculations.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository to your local machine.

    ```bash
    git clone https://github.com/your-username/BMIProCalc.git
    ```

2. Navigate to the project directory.

    ```bash
    cd BMIProCalc
    ```

3. Install the required npm packages.

    ```bash
    npm install
    ```

4. Create a `.env` file in the root directory and set the desired port (default is 3000).

    ```
    PORT=3000
    ```

## Usage

1. Start the server.

    ```bash
    npm start
    ```

2. Open your web browser and go to `http://localhost:3000`.

## Features

### Calculate BMI

Click on "Calculate BMI" in the navigation to access the BMI calculator. Enter your details, choose the unit system, and click "Calculate" to see your BMI and category.

### View History

Click on "History" in the navigation to view the history of BMI calculations. It displays a list of previous BMI results.

### About

Click on "About" in the navigation to learn more about BMIProCalc and its purpose.

## Dependencies

- [Express](https://www.npmjs.com/package/express): Fast, unopinionated, minimalist web framework for Node.js.
- [Body-parser](https://www.npmjs.com/package/body-parser): Parse incoming request bodies in a middleware before your handlers, available under the req.body property.
- [Dotenv](https://www.npmjs.com/package/dotenv): Dotenv is a zero-dependency module that loads environment variables from a .env file into process.env.

## Contributing

Feel free to contribute to the project by opening issues or submitting pull requests.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
