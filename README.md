▎VK User Info Console Application

This is a console application that retrieves information about a VK user using the VK API.

▎How to Launch

▎Prerequisites

• Ensure you have Python 3.0

• Obtain your VK API access token.

▎Steps to Run the Application

1. Open Terminal.

2. Access the Repository Folder:

    • Unzip the downloaded repository.

3. Run the Application:

    • For Ubuntu:

    python3 vk_user_info.py <user_id> <output_path> <access_token>

    • For Windows:

    python vk_user_info.py <user_id> <access_token> <output_path>

4. Done!

    • If you do not specify a path to save the result file, an apiData folder will be automatically created in the current directory where you ran the application. This folder will contain the result.

▎Example Usage

# Ubuntu Example

python3 vk_user_info.py 123456 /path/to/output/folder your_access_token

# Windows Example

python vk_user_info.py 123456 your_access_token /path/to/output/folder

▎Notes

• Replace <user_id> with the VK user ID you want to query.

• Replace <output_path> with the desired path to save the output file.

• Replace <access_token> with your valid VK API access token.

Feel free to contribute or raise issues if you encounter any problems!
