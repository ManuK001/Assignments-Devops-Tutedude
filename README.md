# Assignment-1-Devops-Tutedue

Assignment 1 - Linux- Devops Tutetude - Manas

https://docs.google.com/document/d/1i2xaSp1lzynG6xCkTd7TYEYPT0Qul7fTnxTwKBSuaK4/edit?usp=sharing


1 Creating and Renaming Files/Directories

1.1 Create a directory named test_dir using mkdir.
1.2 Inside test_dir, create an empty file called example.txt.
1.3 Rename example.txt to renamed_example.txt using mv

mkdir test_dir

cd  test_dir

touch example.txt

mv example.txt renamed_example.txt


2. Viewing File Contents
2.1 Use cat to display the contents of /etc/passwd.
2.2 Display only the first 5 lines of /etc/passwd using head.
2.3 Display only the last 5 lines of /etc/passwd using tail.

cat /etc/passwd

head -n 5 /etc/passwd

tail -n 5 /etc/passwd


3.Searching for Patterns
Use grep to find all lines containing the word "root" in /etc/passwd.


grep "root" /etc/passwd


4. Zipping and Unzipping
4.1 Compress the test_dir directory into a file named test_dir.zip using zip.
4.2 Unzip test_dir.zip into a new directory named unzipped_dir.

zip -r test_dir test_dir.zip

unzip test_dir.zip -d unzipped_dir


5. Downloading Files
Use wget to download a file from a URL (e.g., https://example.com/sample.txt).


wget  https://example.com/sample.txt -o sample.txt



6. Changing Permissions
Create a file named secure.txt and change its permissions to read-only for everyone using chmod.

touch secure.txt

chmod +r secure.txt


7. Working with Environment Variables
Use export to set a new environment variable called MY_VAR with the value "Hello, Linux!".


export MY_VAR = “Hello, Linux!”






