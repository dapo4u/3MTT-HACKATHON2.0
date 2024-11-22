

🚀 CLICK2VOTE TEAM
🌟 Empowering Seamless, Secure, and Cost-Effective Voting Solutions

We are the CLICK2VOTE TEAM, proud participants in the 3MTT Hackathon 2.0! We developed several innovative apps during the event, but the standout is our flagship app:

🎉 Click2Vote App
This app ensures seamless, efficient, secure, and cost-effective voting, solving critical problems in the electoral process.

🛠️ Problem the Click2Vote App Solves
The Click2Vote App is a highly secure Django-based electronic voting platform designed to address several key issues in Nigerian elections:

🗳️ Ballot Snatching
🛡️ Election Manipulation and Rigging (especially at the LGAs in Nigeria)
⏳ Unnecessary Delays in the declaration of results
As an Adhoc INEC officer, I can personally attest to how election rigging starts at the local government level.

🗳️ About the Click2Vote App
The Click2Vote App works smoothly on Linux and Ubuntu laptops, but there are a few potential issues when running it on Windows systems:

🖥️ Linux: No errors detected during testing on Kali Linux and Ubuntu.
💻 Windows: Errors may occur due to missing GTK runtime and DLL files (especially on Windows 7).
Solution: I used MSYS2 to resolve these issues and ran the app successfully on Windows 10.
Note: The issue is not with the app itself, but rather with Windows not having the necessary dependencies.
🎥 Watch our upcoming video tutorial on how to fix the error on Windows!

⚙️ How to Run the App on Linux
1️⃣ Install Python 3.7 (If Not Already Installed)
Make sure Python 3.7+ is installed on your system:

bash
Copy code
sudo apt update
sudo apt install python3.7 python3.7-venv python3.7-pip
2️⃣ Create a Project Folder
Choose a directory where you want to store the project and create a folder for it:

bash
Copy code
mkdir my_project
cd my_project
3️⃣ Create and Activate a Virtual Environment
Set up a virtual environment for the project:

bash
Copy code
# Navigate to your project directory
cd /path/to/your/project

# Create the virtual environment
python3 -m venv venv

# Activate the virtual environment
source venv/bin/activate
4️⃣ Clone the Repository
Clone the repository from GitHub:

bash
Copy code
git clone https://github.com/dapo4u/3MTT-HACKATHON2.0.git
5️⃣ Navigate to the Project Directory
bash
Copy code
cd 3MTT-HACKATHON2.0
6️⃣ Install Dependencies
Install all required Python dependencies:

bash
Copy code
pip3 install -r requirements.txt
7️⃣ Run the App
Start the development server:

bash
Copy code
python manage.py runserver
Alternatively, use python3:

bash
Copy code
python3 manage.py runserver
8️⃣ Log In to the App
Use these credentials to log in to the application:

Email: daporaphael@gmail.com
Password: ola2nj
🌐 Check Out Our Other Projects
We’ve developed several other apps for the Hackathon. Explore them here:

🔍 Trojan PDF File Detector
⚖️ Equation Balancer
🔐 PDF Encryptor
🔧 Get Involved
We welcome contributions! Feel free to open issues, submit pull requests, or contact us if you have any questions. Together, we can make voting systems more secure and efficient for everyone!

💬 Stay Updated
📹 A video tutorial on fixing Windows-related errors will be available soon.
Stay tuned for more updates and improvements!

Final Thoughts
Thank you for exploring the Click2Vote App! We are committed to improving the way elections are conducted and ensuring a more secure and efficient voting process for everyone
