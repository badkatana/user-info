## VK User Info Console Application

This is a console application that retrieves information about a VK user using the VK API.

##Prerequisites
Python 3.0
Obtain your VK API access token.

## Usage

1. Open Terminal.
2. Unzip the downloaded repository. You need to be in the same folder with the script or you may need write a full path.
3. Run the Application:

Ubuntu:

```bash
python3 vk_user_info.py <user_id> <access_token> <output_path>
```

Windows:

```bash
python vk_user_info.py <user_id> <access_token> <output_path>
```

4. Done!
   If you do not specify a path to save the result file, an apiData folder will be automatically created in the current directory where you ran the application. This folder will contain the result.
