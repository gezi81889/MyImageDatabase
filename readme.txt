
Hi users,

MyImageDatabase comes with this file folder, please put this folder on your desktop and do not change any file name. They are just txt files and png files(after you upload images),storing information for your database. After you become familiar with the functions of MyImageDatabase, you can even manually edit them in the way you want your database to be. This is a very simple application and not very good at reporting errors, please do read following simple instruction before using it. If you have any questions, please do not hesitate to ask me or email me at minming.wang@yale.edu . Thanks for using MyImageDatabase! Hooray!!

---PREPARATION----
Make sure your computer has Java Runtime Environment(JRE) installed. My version is macOS x64 18.0.1.1. If it shows failure launch blablah, you can try launch it again in terminal by typing "java MyImageDatabase.jar", which works well on my another computer. 

----LAUCH APPLICATION----
1.Double click the "MyImageDatabase.jar". A welcome interface will show up.Make sure you change you security&privacy in system preference setting. 
2.click either "Add" to upload, or "Search" to look up images you want. 

----HOW TO UPLOAD-----
1. Click "Add", an uploading interface will show up.
2. Drag and drop any images from your desktop(e.g a screenshot, need to be fully settled screenshot, meaning it is already exist on your desktop) on to the left panel, fill in the information on the write table. Avoid using ";" in any of those blanks. 
  
  -Gene:Fill in the gene name, in a consistent way you prefer (easier for searching)
  -Stage:Fill in the stage, in a consistent way you prefer (easier for recording)
  -Keywords: Support multiple keywords input(separate with ",") 
  -Method: Fill in the method, in a consistent way you prefer (easier for recording)
  -Pmid: Fill in the PMID code, in a consistent way you prefer (easier for recording)

  You can also leave any of those blank, and manually add those information in "MyImageTable.txt" later(Make sure you understand how MyImageDatabase works). 

3. Click "UPLOAD", your image will be copied into the same folder named with a specific id (default user name of your computer + number),and the information of this image will be added to "MyImageTable.txt". The total number of your unloaded images stores in "MyImageCounter". please do not change it (unless you know the result it will cause), because it determines the specific id of each uploaded image. 

4. A message window will show, telling you the image is successfully uploaded. 

5. The "wmm1.png" and first line in "MyImageTable" is for testing. You can delete them once you successfully upload your first image.


----HOW TO SEARCH-----
1. Click "Search", a searching interface will show up with a table storing all uploaded images. 

2. Currently, MyImageDatabase only support "Gene" and "Keyword" searching. Input one gene name and one keyword one time, and click "Search". The inquired image and related information will show up. You can drag to change the column order (but not row order).

3. You can also delete any images by clicking and selecting a specific row, and click "Delete", and flash the table by clicking "Search". 

4. The deleted image and related information will be removed, but their ID will not be skipped. 

