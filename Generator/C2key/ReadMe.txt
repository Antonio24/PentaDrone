HOW TO USE IT
-------------------------------------

It's IMPORTANT that your C2 URL not be static. You will change it at your convenience by using an encrypted file stored over Internet.
Each time the zombie want to contact C2, it will check for actual C2 URL by obtaining and decrypt the C2 URl stored in you file
This file will help you setup this process.


1- Run PrepareC2Key.bat
Type your C2 URL, it will encrypt it and produce the result to you in file named: prepareC2.txt

2- Change the "keytoreadgetc2" value in your "CONFIG.ini".
By doing so, your agent can decrypt C2 value stored in Internet web page

exemple: Edit "CONFIG.ini" with keytoreadgetc2 ---->   jH2R5h/2lJF5r42yAXj6RS7wBsxfw=

3- Store your C2 value 
You need to host or store a file over Internet and put the value provided in your "prepareC2.txt" file
Exemple: Edit "getC2" value in "CONFIG.ini"to point to pastebin URL --> https://https://pastebin.com/raw/xxxxx
	and Edit Pastebin value with C2 encrypted value ---->   TUtAdo8fKzUeKEdcO3LWyJW/LWsZfayDHHeLHqerEKK


