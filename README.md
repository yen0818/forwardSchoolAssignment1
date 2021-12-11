Question:
Kindly create a new repository with 2 new files(any random text files) and create a README.MD with instructions on how you created the repository and how you pushed your files to repository. Do also state the use of having SSH keys how one can generate it in your README.MD. Once done, key in you repository link below.

1. mkdir forwardSchoolAss1 in my local
2. cd forwardSchoolAss1
3. echo "# forwardSchoolAssignment1" >> README.md
4. git init
5. git add README.md
6. git commit -m "first commit"
7. git remote add origin https://github.com/yen0818/forwardSchoolAssignment1.git
8. git push -u origin main

To create a new file:
1. create new file locally
2. git add .
3. git commit -m "add new files"
4. git push -u origin main

For the SSH, I will need to 
1. open up cmd prompt as Admin and generate ssh key by command *ssh-keygen -t rsa*.
2. Enter passphrase
3. Copy the ssh public key to github setting.
