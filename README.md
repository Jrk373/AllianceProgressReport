# progressReport
This is a project designed to generate a periodic report for an Accountable Care Organization

The project includes the following folders:
- analyses
- archive
- data
- documents
- images
- source

Update the README files in the project as you work through the investigation

If using GitHub, a README file might be automatically created. Copy the information in this file to that file, and archive this file.

#  START HERE

**Source data from outside this project**

  1.  Alliance Enrollment Roster: Community Health Outreach
  2.  VBP Quality Roster: Value Based Data

## Notes:

2/5/24: Updates

- Member Enrollment roster is now generated from the Community Health Outreach project.
  - Power automate updates this data nightly
  
5/22/23: 

- Alliance Progress Report is migrated to quarto .qmd file
- VBPQR_AllProvidersCombined_Cleaned is copied into the data folder from the VBPValidation Report
- Global Members is imported from SQL query of HCA data warehouse

# Step-by-step
1. Create copy of most recent Quarto file, redate for current date
2. Update dates throughout the document for the current date
3. Copy most recent "VBPQR_AllAPsCombined_Cleaned_complete_YYYY-MM-DD" from ./VBPValidationModel_FUH/data/output to  ./progressReport/data
4. Update the dates for the inlince code