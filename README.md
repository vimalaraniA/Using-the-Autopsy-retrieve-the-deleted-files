# Using-the-Autopsy-retrieve-the-deleted-files
Name:Vimala Rani A

Reg No:212223040240
## AIM:
To use Autopsy in Kali Linux to retrieve and analyze deleted files from a disk image.

## DESIGN STEPS:
### Step 1:
Open Autopsy and create a new case with appropriate case details.

### Step 2:
Add a disk image as a data source and let Autopsy analyze the content.

### Step 3:
Navigate to the "Deleted Files" section in Autopsy and examine or recover the deleted files.

## PROGRAM:
### *1. Copy Files to the Virtual Disk*  
- Open *File Explorer* → Go to the new drive (C: or D:), where the folder created in the New Virtual Disk
- Create a new folder (Autospy) and copy *images or files* into it.  

### *2. Delete the Files*  
- Select any one or two images → Press *Delete*.  
- Empty the *Recycle Bin* to permanently delete them.  

### *3. Recover Deleted Files Using Autopsy*  
### *Open Autopsy & Create a New Case* 

- Launch *Autopsy* and *Run as a administrator*  
- Click *Create New Case*.  

![Screenshot 2025-04-21 135250](https://github.com/user-attachments/assets/3540b979-3ea1-43df-b623-a8a81a4858b2)


- Enter a *Case Name* (e.g., Autopsy1).  
- Choose a *Case Folder* location.  
- Click *Next* → Click *Finish*.  

![Screenshot 2025-04-21 135305](https://github.com/user-attachments/assets/09e57945-5279-4948-bfb0-ac70460eb989)

### *Add the Virtual Disk as an Evidence Source*  
- Click *Add Data Source*  → *Select Host*

![Screenshot 2025-04-21 135318](https://github.com/user-attachments/assets/d15fcc45-a5e8-49d7-b438-84b225044010)


- Select *Local Disk* → *next* 

![Screenshot 2025-04-21 135332](https://github.com/user-attachments/assets/05a1eeec-bac5-42ac-9945-841b9bc644f7)


- Select Disk → **Choose the VHD drive (Drive1)**

![Screenshot 2025-04-21 135348](https://github.com/user-attachments/assets/8a96a9a8-628e-4598-a033-08e474e0a5a3)


- Click *Next* → Keep default settings → Click *Finish*.  
- Wait for Autopsy to process the disk.  

### *Recover Deleted Files*  
- Go to *File Views* (left panel).  

![Screenshot 2025-04-21 135412](https://github.com/user-attachments/assets/9fb809b8-ea16-46d2-9aa5-75fd9770720a)


![Screenshot 2025-04-21 135427](https://github.com/user-attachments/assets/917d8037-1c5f-4495-951a-ebb26681acb2)


- Click *Deleted Files* → Find your deleted images.  
- Right-click an image → Click *Extract File*.  

![Screenshot 2025-04-21 135452](https://github.com/user-attachments/assets/dba288ab-bf1d-4edf-8f47-3f2da25f77b0)


- Select a folder to see the recovered files (e.g., C:\forensic).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
![Screenshot 2025-04-21 135511](https://github.com/user-attachments/assets/d190a167-ad77-4f90-a150-7c4d898c884d)

### Folder after deleting the files
![Screenshot 2025-04-21 135521](https://github.com/user-attachments/assets/e6c83bc6-853b-4a6d-bda0-6872d06adb37)

### Folder after extracting the deleted images using autopsy
![Screenshot 2025-04-21 135530](https://github.com/user-attachments/assets/d9d17cde-a820-472f-b276-0aaab02080dc)

## RESULT:
Deleted files were successfully retrieved and analyzed using Autopsy.
