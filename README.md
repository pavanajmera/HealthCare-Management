# HealthCare-Management

LINK: https://share.streamlit.io/pavanajmera/healthcare-management/HIMS_app/hims_app.py

INSTRUCTIONS:

Requirements: Python 3.7.4 or any higher version

Steps:

(1) Download zip folder and extract it.

(2) Go to command prompt/terminal and install pandas and streamlit by running the following commands (internet connection needed for this step):
	
	> pip install pandas

	> pip install streamlit

(3) In the command prompt/terminal, go to the project folder (the one that you have just extracted):

	For example, if I have downloaded and extracted the project folder as 'HIMS_app' in the 'Downloads' folder of my system, I'd write the following command in the command prompt:
		
		cd Downloads\HIMS_app

(4) Once you have moved into the project folder in the command prompt/terminal, write the following command and hit enter:

	> streamlit run hims_app.py

	(Running this command will open the app in a new tab in your default browser automatically; you don't need internet connection to work with this app)

CONFIDENTIAL CREDENTIALS:

	* home screen user password:			15081812
	
	* edit mode password:				allow_edit
	
	* doctor/ medical lab scientist access code:	access_auth	

NOTE:

The changes in the updated version include:

	* Edit mode password - this is to ensure that only the people who are authorised to add, delete and update the records can do so. Viewing data doesn't require this second level of 
	authentication.

	* Doctor/ Medical Lab Scientist access code - this is to ensure that only doctors and medical lab scientists are able to add, delete and update prescription and medical test 
	details. Viewing prescriptions and medical tests of a patient doesn't require this second level of authentication.

	* The fucntionality of 'Listing doctors of a particular department using the department unique ID' has been moved from the Doctor module to the Department module.
