# License-O365Users
This script will set or update the UsageLocation and licenses assigned to the users in the specified CSV file. If the CSV does not already exist, the script can create it with the current set of licenses using the GenerateCSVFile parameter. To add a feature of a license to a user, put a 1 in the field. To add all features of a license to a user, put a 1 in all fields for the license. To remove a feature of a license from a user, put a 0 in the field. To remove all features of a license from a user, put a 0 in all fields for the license. To not modify a feature, license or UsageLocation for a user, leave the field blank.
