# 👁️ Pimeyes Free
A proof of concept exploit tool to bypass Pimeyes' obfuscation and provide full premium search results.
Despite attempts to contact Pimeyes, no response was received, leading to the publication of the tool.
It enabling retrieval of unobfuscated web links from search results.  
  
Use:
1. Clone the directory "git clone [https://github.com/airborne-commando/Pimeyes-Free-GUI.git](https://github.com/airborne-commando/Pimeyes-Free-GUI.git)"
* OR Clone the main git repo directory "git clone [https://github.com/addycb/Pimeyes-Free-POC.git](https://github.com/addycb/Pimeyes-Free-POC.git)"
3. Navigate into the directory "cd Pimeyes-Free-GUI"
4. Run the tool :: "python main-gui.py"
5. Select the image you want to search
6. Save the results
7. ????
8. Profit

Will still get rate limited to at least 10ish searches, if you really need to search for a face this bad; use a VPN like [mullvad](https://mullvad.net/en) or use TOR SOCKS that's built inside the script.
Will also add that copy and paste is a hit or miss; some images may be WAY too big for a copy paste; best to save on your device if it doesn't work.
For images that are not found within it's database, it will throw up this error here:

![image](https://github.com/user-attachments/assets/c73ee23e-8fee-4a61-bd8f-5cc7b082eff5)

That's normal; it means it can't find anything on it's database.

# Functions added include:

* Weather the site is from an adult site or market site
* Ability to search VIA TOR SOCKS  (they rate limit with IP)
* Drag and drop functions, along with paste from clipboard

All in the flask application.


# For a HTML page using flask

    python -m venv venv

</br>

    source venv/bin/activate

</br>

    pip install -r requirements.txt

  For tor proxy you'll need to enable or start the service Inside linux:

    systemctl start tor


Result: You will receive a collection of unobfuscated results, namely links to where that face was found.


Will probably change the title of this repo; so long as the maintainer of the original is ok with this, seems to work.

Visual example of the results page inside the flask app:

![image](https://github.com/user-attachments/assets/6b9d135b-0779-40bb-9799-9fb8e906994d)

