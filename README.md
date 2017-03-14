# FileUploadTests

- [ ] Check extension

   *An exe file should be added*

name|name|name|name
---------|-----------|----------|------------
Test.cvs | Test.html | Test.png | Test.txt.gz
Test.doc | Test.jar | Test.ppt | Test.xls
Test.docm | Test.jpeg | Test.pptm | Test.xlsm
Test.docx | Test.jpg | Test.pptx | Test.xlsx
Test.GIF | Test.pdf | Test.TIF | Test.zip




- [ ] Check content type

   *Files have had their extension changed*

>Test Jar.pdf

>Test Text.jpg




- [ ] Check for adding an extension

   *File has the original extension and added a second extension*

>Test.html.jpg




- [ ] Check file size

   *This file is 30+MB*

>Test Large File.pdf




- [ ] Check virus protection

>Eicar.com.txt




- [ ] Check zipped files to see if files in it are scanned

   *If your application accepts compressed files, create a archive with the eicars file*



- [ ] Check filename length

   *Add various filename lengths, but to 200 characters


- [ ] Check access controls

   *Can one user access a file uploaded by another user


- [ ] Try overwriting files
   
   *Upload a file. Then attempt to overwrite is on the file system


- [ ] Try POST, GET and PUT



- [ ] Check x-content-type-options header
   
   *Does the header include 'x-content-type-options'


- [ ] Check path traversal
   
   *Attempt to travers the file path filename="../../../../" and see what may happen

- [ ] Check logging
   
   *Is the file upload (successes, failures, and accesses) being logged


- [ ] Check for cross-site request forgery



- [ ] Check if authentication is needed to upload
  
  *Does the service used require authentication? Is it the same authentication required of the application?


