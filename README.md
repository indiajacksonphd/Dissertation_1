# Solar Survival Package

The Solar Survival Package is a tool designed to replicate the statistical survival analysis performed in the research project for space weather prediction of solar energetic particles. This package allows you to easily perform the same analysis steps and generate visualizations as presented in the project.

## Installation

To install the Solar Survival Package, use the following command:


## Usage

After installing the package, you can use it to replicate the analysis steps and generate visualizations as follows:

```python
import solarsurvival

# Perform data extraction first
solarsurvival.data_extraction()

# Call the wrapper function to execute all the steps
solarsurvival.results()

Running the above code will execute the entire analysis pipeline, including data extraction and generating various plots and summaries. Please note that this usage is intended to replicate the project's analysis and may not be immediately reusable for other purposes.


## Requirements
The Solar Survival Package relies on the following libraries and dependencies. They will be automatically installed when you install the package:

pandas
boto3
numpy
seaborn
matplotlib
scipy
tabulate
lifelines

## Additional Resources
For more information about the project, including the source code and detailed documentation, you can visit the GitHub repository.

## License
This package is provided under the MIT License.

## Contact
For any questions or inquiries, please contact India Jackson at ijackson1@gsu.edu.

