# **BizCard OCR Project**


# **Overview**
The BizCard OCR (Optical Character Recognition) project is designed to extract and manage business card information using image processing techniques. It utilizes the Streamlit framework for creating a user interface and integrates with an OCR library (EasyOCR) for text extraction. The extracted information is stored and managed in a MySQL database.

# **Features**
        Extract Information: Upload an image of a business card to extract relevant information such as name, designation, contact details, email, company, website, city, state, pincode, and image.

        Create Business Card: Manually enter your business card details and upload an image to create a new entry in the database.

        Read Database Entries: View a tabular representation of all stored business card entries.

        Update Information: Select a business card entry to update and modify its details.

        Delete Entries: Remove a business card entry from the database.

# **Technologies Used**
Streamlit: Web framework for creating interactive and user-friendly applications.
EasyOCR: Optical Character Recognition library for extracting text from images.
MySQL: Database management system for storing and managing business card information.
PIL (Pillow): Python Imaging Library for handling images.
Matplotlib: Plotting library for visualizing image previews.
OpenCV: Computer vision library for image processing.
Pandas: Data manipulation and analysis library.
# **Setup Instructions**
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/bizcard-ocr.git
Install dependencies:

bash
Copy code
cd bizcard-ocr
pip install -r requirements.txt
Configure MySQL:

Set up a MySQL server with the necessary credentials.
Create a database named bussiness_card (or adjust the database name in the code).
Update the MySQL connection details in the code (host, user, password).
# Run the application:

bash
Copy code
streamlit run your_script.py
Access the application in your web browser at the provided address (usually http://localhost:8501).

# **Project Structure**
images: Directory for storing uploaded business card images.
streamlit_option_menu: Custom Streamlit component for creating a vertical navigation menu.
your_script.py: Main script containing the Streamlit application.
# **Acknowledgments**
Thanks to the developers of Streamlit, EasyOCR, and other open-source libraries used in this project.# Bizcard
