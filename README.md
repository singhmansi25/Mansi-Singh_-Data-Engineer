# Mansi-Singh_Data-Engineer
This repo contains submission for SteelEye task for Python Engineer

# Brief:

- The requirement needs to be developed in Python 3
- Code should follow pep8 standards and should include pydoc, logging & unit tests
- Please provide github link for review.

# Requirement:

- Download the xml from this link
- From the xml, please parse through to the first download link whose file_type is DLTINS and download the zip
- Extract the xml from the zip.
- Convert the contents of the xml into a CSV with the following header:
    - FinInstrmGnlAttrbts.Id
    - FinInstrmGnlAttrbts.FullNm
    - FinInstrmGnlAttrbts.ClssfctnTp
    - FinInstrmGnlAttrbts.CmmdtyDerivInd
    - FinInstrmGnlAttrbts.NtnlCcy
    - Issr
- Store the csv from step 4) in an AWS S3 bucket
- The above function should be run as an AWS Lambda (Optional)

# Assessment criteria:

- Percentage of requirements satisfied
- How clean the code is - in particular simplicity, adhering to python code style conventions and error handling.
- Follows PEP 8 guidelines
- We expect pydoc for each class and function with optional type hints(nice to have)
- Follows standard logging (no print statements). Logs are essential part of troubleshooting application.
- Unit tests with good code coverage


# Approach
- Importing required libraries
- Creating a class for various tasks
- Logging & Unit-testing
- ZIP -> XML -> CSV
- AWS S3 bucket creation
- I have not applied Lambda function
