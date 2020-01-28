# RPA_UiPath-Generate-Yearly-Report
Level 3 - Advanced Training assignment
Business process to automate

1.1 : Open the ACME System 1 Web Application.

1.2 : Log in to System 1. Required input data: email and password.

1.3 : Access the Dashboard - the central location, where the user can pick a specific menu item.

1.4 : Access the Work Items listing to view all the available tasks to be performed (Output data: list of tasks).

1.5 : For each activity of type WI4, perform the following steps:

1.5.A : Open the Details page of the selected activity to retrieve the Vendor Tax ID (Output data: Tax ID).

1.5.B : Go back to the Dashboard and access the Download Monthly Report section in the Reports menu.

1.5.C : Fill in the Vendor Tax ID and download all the monthly reports for previous year.

1.5.D : Group the downloaded monthly reports into a single Excel file with the naming convention
“Yearly-Report-[Year]-[Tax ID].xlsx”.

1.5.E : Upload the resulting yearly report file in the “Upload Yearly Report” section in the Reports menu.

1.5.F : Fill in the Vendor Tax ID, set the year, and select the file on your hard drive. This will return a unique upload ID.
Output: Upload ID.

1.5.G : Go back to the Work Item Details page and select Update Work Item.

1.5.H : Set the status to “Completed”. Add the following comment: “Uploaded with ID [Upload ID]”.

1.6 : Continue with the next WI4 Activity.

Other expectations

Shold be based on REFramework template
Exception handling
