# Data Privacy Analyzer

## Overview

The Data Privacy Analyzer is a lightweight embeddable JavaScript tool designed to help website owners and developers assess the data privacy implications of their web applications. This script analyzes various aspects of a website's client-side implementation to identify potential data collection mechanisms, third-party resources, and data privacy-related features.

## Features

- **Comprehensive Tracking Detection**: Identifies potential tracking mechanisms in scripts, stylesheets, cookies, local storage, and session storage.
- **Data Privacy Feature Analysis**: Detects the presence of privacy policies, cookie consent banners, and Global Privacy Control (GPC) support.
- **Sensitive API Usage Detection**: Identifies the use of privacy-sensitive browser APIs like Geolocation and Camera/Microphone access.
- **Third-Party Resource Analysis**: Detects and lists third-party resources loaded by the website.
- **Categorization**: Categorizes detected items into Analytics, Advertising, Functionality, Social Media, and Unknown.
- **Detailed Reporting**: Generates a comprehensive report with findings, implications, and recommendations.

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/Data-Foundation-Lab/DataPrivacyAnalyzer.git
   ```
2. Include the script in your HTML file:
   ```html
   <script src="path/to/DataPrivacyAnalyzer.js"></script>
   ```

## Usage

To use the Data Privacy Analyzer, simply call the `analyze` method:

```javascript
const results = DataPrivacyAnalyzer.analyze();
console.log(results.report);
```

This will run the analysis and log the detailed report to the console.

## Report Structure

The generated report includes:

1. Tracking items categorized by type (Analytics, Advertising, etc.)
2. Description and privacy implications for each category
3. List of detected items in each category
4. Analysis of privacy features (privacy policy, cookie consent, GPC)
5. Detection of privacy-sensitive API usage
6. List of third-party resources
7. Summary with overall privacy assessment and recommendations

## Contributing

Contributions to improve the Data Privacy Analyzer are welcome! Please follow these steps:

1. Fork the repository
2. Create a new branch (`git checkout -b feature/your-feature-name`)
3. Make your changes
4. Commit your changes (`git commit -am 'Add some feature'`)
5. Push to the branch (`git push origin feature/your-feature-name`)
6. Create a new Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Projects That Uses DataPrivacyAnalyzer
- [Find My Data Rights (DFLab)](https://findmydatarights.com)
    - [Github](https://github.com/Data-Foundation-Lab/Find-My-Data-Rights/tree/with-tests/tests)

## Disclaimer

This tool is designed for informational purposes only and should not be considered as legal advice. Always consult with a qualified legal professional for compliance with data privacy laws and regulations.

## Contact

If you have any questions, issues, or suggestions, please open an issue in this repository.