# From Text to Cement: Developing Sustainable Concretes with In-Context Learning

This repository contains the code and dataset for the study "From Text to Cement: Developing Sustainable Concretes with In-Context Learning". The project aims to improve the development of sustainable concrete formulations using in-context learning (ICL) and large language models (LLMs). By leveraging the potential of LLMs, this research aims to overcome the limitations of traditional methods and accelerate the discovery of novel, sustainable, and high-performance materials.

#### Overview

The primary goal of this study is to compare the prediction performance of compressive strength using ICL and the text-davinci-003 model against established methods such as Gaussian Process Regression (GPR) and Random Forest (RF). The dataset comprises 240 alternative and more sustainable concrete formulations based on fly ash and ground granulated slag binders, along with their respective compressive strengths.

#### Key findings of this study include:

ICL performs just like GPR and  matches the performance of RF when supplied with small training data sets.
Fine-tuning LLMs with general concrete design knowledge reduces prediction outliers and outperforms RF.

![Uploading Bildschirmfoto 2023-04-21 um 13.33.38.png…]()


## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Installation

To install the software, follow these steps:

1. Clone the repository to your local machine using `git clone`:

    ```bash
    git clone https://github.com/username/repo.git
    ```

2. Change directory to the cloned repository:

    ```bash
    cd repo
    ```

3. Install the dependencies using a package manager such as `npm` or `pip`:

    ```bash
    npm install
    ```

    or

    ```bash
    pip install -r requirements.txt
    ```

4. Start the application using the provided command or script:


    ```bash
    jupyter notebook
    ```

6. Open a web browser and navigate to `http://localhost:3000` to access the application.
7. Create an OpenAI API key from the OpenAI website '(https://beta.openai.com/)'.
8. Replace the placeholder API key in the code with your actual OpenAI API key.
9. Prepare a CSV file with prompts and completions as input data. Update the file path in the code to point to your CSV file.

## Usage
1. Run the code in a Python environment to train the completion predictor using text-davinci-003 and generate completions for test data.
2. The completion predictor's performance will be evaluated using R-squared, MSE, and MAE metrics, which will be printed on the console.
3.You can modify the code to customize the prompts, completions, and other parameters as needed for your specific use case.

## Contributing
Contributions to this project are welcome! If you would like to contribute, please follow standard GitHub practices, such as forking the repository, creating a branch for your changes, and submitting a pull request with a clear description of your changes. Please ensure that your changes are well-tested and adhere to the project's coding standards.

## License
This software is released under the [MIT License](https://opensource.org/licenses/MIT).

## Acknowledgements

The following resources were used in the development of this project:

- [OpenAI](https://openai.com) for providing the GPT-3.5-turbo API that powers the completion predictor.
- [Pandas](https://pandas.pydata.org/) and [scikit-learn](https://scikit-learn.org/) libraries for data manipulation and machine learning capabilities in Python.

