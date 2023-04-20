# LLMs-for-the-Design-of-Sustainable-Concretes

Summary:
This repository showcases a novel approach to accelerate the discovery of sustainable concretes using large language models (LLMs) and compares it with traditional methods such as Gaussian Process Regression (GPR) and Random Forest (RF). The project addresses the inherent complexity and variability of building materials, which has historically limited the development of sustainable concretes due to labor-intensive laboratory testing. The use of LLMs offers advantages such as incorporating context and general knowledge into predictions, flexibility in handling non-numeric inputs, and effective integration of domain knowledge. The experimental results demonstrate the potential of LLMs to outperform traditional models by more than 40 percent, even with limited datasets. The project highlights the democratizing potential of LLMs in material science, making the development of sustainable concretes more accessible to experts and contributing to the quest for sustainability in the construction industry. Future research directions include refining LLMs for material design applications, integrating domain knowledge more effectively, and addressing other complex material design challenges.

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
1. Run the code in a Python environment to train the completion predictor using GPT-4 and generate completions for test data.
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

