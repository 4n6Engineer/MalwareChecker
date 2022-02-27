Malware Checker Tool generates an HTML report by comparing Hashes, Ip Addresses and URL Addresses through the VirusTotal database.

**Features:**
* Hash Scan (MD5,SHA1, SHA256)
* IP Scan
* URL Scan

<h1>Pre-Setup (Python2):</h1>

>pip install virustotal-api

or

>python.exe -m pip install virustotal-api

<h1>Example Usage:</h1>

python MalwareChecker.py source_ioc_list.txt


**Note:** VirusTotal Public API offers 4 queries per minute, and a total of 1000 queries per day. Due to this situation, it takes approximately 20 minutes to calculate and report your 100 hash lists. 

Registering to the VirusTotel page, you can get your own API value. You can add the API value you have received to the VirusTotal Public section in the MalwareChecker.py file. (Since the current API will be used by every user downloaded, I recommend using your own API value to avoid restrictions.)


![image](https://user-images.githubusercontent.com/65830370/155898708-f7a070b8-44c9-44d4-abbe-df0b89bcd97b.PNG)


<h1>REPORT OUTPUT:</h1>

![image](https://user-images.githubusercontent.com/65830370/155898748-17908972-45c6-4ed7-9aae-64849d03478f.PNG)


<h1>HASH FILTER:</h1>

![image](https://user-images.githubusercontent.com/65830370/155898806-9e718779-dd59-4333-b1b9-6acf6c35728f.PNG)


<h1>CSV, EXCEL, PDF OUTPUT and COPY ALL ROWS:</h1>

![image](https://user-images.githubusercontent.com/65830370/155898826-de8e8023-8256-438f-a5f6-55b3eafee6fd.PNG)


<h1> COLUMN VISIBILITY </h1>

![image](https://user-images.githubusercontent.com/65830370/155898883-af830bb5-16f0-44ca-9b2b-529f98509de1.PNG)

