# Movie Review Classification with UiPath Document Understanding and AI Center

## Project Overview

The "Movie Review Classification" project focuses on classifying movie reviews as positive, negative, or neutral using UiPath Document Understanding and the EnglishTextClassification machine learning model. The process involves training the ML model within UiPath AI Center and then integrating the trained model as a skill in UiPath Studio for automated classification. Additionally, if the confidence score for a classification is less than 50, the process triggers human validation in UiPath Action Center.

## Features

- **Document Classification:** Utilizes the EnglishTextClassification ML model for accurate movie review classification.
- **Integration with UiPath AI Center:** Trains and manages the machine learning model within UiPath AI Center for seamless integration with UiPath Studio.
- **Human Validation in Action Center:** If the classification confidence score is less than 50, the process initiates human validation in UiPath Action Center for further review.

## Getting Started

### Prerequisites

- UiPath Studio
- UiPath AI Center
- UiPath Action Center
- EnglishTextClassification ML model 

### Installation

1. Clone the repository:

   ```bash
   git clone (https://github.com/sudarshanbhikane/movie-review-classification)
   ```

2. Open the project in UiPath Studio.

3. Configure the necessary connection settings for UiPath AI Center.

4. Update the link to the ML model in the project settings.

## Usage

1. Run the main workflow in UiPath Studio for movie review classification.

2. Monitor the UiPath Action Center for human validation tasks if the confidence score is below 50.

## Contributing

If you'd like to contribute to the project, please follow the [contribution guidelines](CONTRIBUTING.md).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

- Special thanks to the contributors and the UiPath community.
- EnglishTextClassification ML model details: [link](link)

Feel free to modify this template according to your project specifics.
