# Metadata-Extraction-using-ExifTool-log2timeline-and-Hidden-Data-Search-using-Steganography-Tools
# RITHIVK S
# 212223100045
## AIM:
To extract metadata, perform timeline analysis, and search for hidden data using forensic tools like ExifTool, log2timeline, and steganography detection tools.

## DESIGN STEPS:
### Step 1:
Use exiftool to extract metadata from files such as images, documents, and videos.

### Step 2:
Use log2timeline and plaso to create and analyze event timelines from system logs and file metadata.

### Step 3:
Apply steganography detection tools like steghide, zsteg, or binwalk to uncover hidden data in media files.

## PROGRAM:
Metadata and Timeline Forensics, Steganography Analysis Steps

## OUTPUT:
Extracted Metadata, Timeline Events, and Hidden Data Detection Results


## INSTALL ExifTool
```
sudo apt update
sudo apt install exiftool -y
```
## EXTRACT METADATA FROM A FILE:
```
exiftool image.jpg
```
## Batch process a folder:
```
exiftool -r /path/to/folder
```
 ![435680836-861dc1d1-4932-460d-9261-2e3295ee9f42](https://github.com/user-attachments/assets/53eba268-52c0-4fc9-9029-e94e18e16b47)

 ## install log2timeline
 ```
sudo apt install plaso -y
```
```
sudo apt install steghide -y
```
## Embed data
```
steghide embed -cf /home/kali/Downloads/wallpaper.jpg -ef /home/kali/Downloads/secret.txt
```
![435685839-d34970ca-ee2c-4a7f-9980-518b74962f02](https://github.com/user-attachments/assets/5802db80-38cd-4f5a-917b-2a150f680058)
## Extract hidden data:
```
steghide extract -sf hidden.jpg
```
![435686036-85520110-9150-417a-b6a9-28e559100cf7](https://github.com/user-attachments/assets/672cd746-22ab-4588-9d39-211e515e5393)
## Using binwalk – for file analysis
```
sudo apt install binwalk -y
binwalk suspicious.jpg
```
![435687161-b26be271-0680-491f-8868-1216de6fd7eb](https://github.com/user-attachments/assets/f58fdef5-9929-40ee-aa2c-4a2d79a3c116)



## RESULT:
Metadata was successfully extracted, timeline analysis was completed, and hidden data was identified using steganography tools.

