# 7zip-instant-zipping-strategy
Create Zip of Artifact After Build With Less Time

For windows Install:
 on powershell:
  choco install 7zip -y

Zip using 7-Zip: 
"C:\Program Files\7-Zip\7z.exe" a -mx=1 D:\Build\aws.zip D:\Aws-Console-Learning-Platform\*

"C:\Program Files\7-Zip\7z.exe" ---> This is the path where you installed 7-Zip
a ---> for archive the data
-mx=1 ---> for instant transfer
D:\Build\aws.zip ---> after zip this is the location where your zip file get stored
D:\Aws-Console-Learning-Platform\* ---> this is the actual file location which you zipped
