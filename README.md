# FileUploadTests

This repo contains various test files for file upload testing. The files used are created with proper applications. All files have the name of 'Test" follwed by their extension. Files with an extension type in the file name have had their extensions changed. Files with multiple extensions have the original extension as the first extension.

**ToDo**

- Add an exe file
- Add a file between 10 and 20 MB
- Add some files between 5 and 10 MB


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

>TestLargeFile.pdf





- [ ] Check virus protection

>TestEicar.com.txt

>Test.Eicar.txt




- [ ] Check zipped files to see if files in it are scanned

> TestEicars.zip



- [ ] Check a filename with spaces
   
>Test a filename with spaces.GIF


- [ ] Check filename length

   *Add various filename lengths, up to 257 characters*


- [ ] Check access controls

   *Can one user access a file uploaded by another user*


- [ ] Try overwriting files
   
   *Upload a file. Then attempt to overwrite is on the file system*


- [ ] Try POST, GET and PUT



- [ ] Check x-content-type-options header
   
   *Does the header include 'x-content-type-options'*


- [ ] Check path traversal
   
   *Attempt to add a path (i.e ../../../../) to the filename and see what may happen*

- [ ] Check logging
   
   *Is the file upload (successes, failures, and accesses) being logged*


- [ ] Check for cross-site request forgery


- [ ] Check if authentication is needed to upload
  
  *Does the service used require authentication? Is it the same authentication required of the application?*


