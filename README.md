# Surveying and Preserving the Digital Crime Scene

## **Aim:**
Data recovery from unallocated space, using forensic tools(Autospy) to extract and analyze data.

## **Implementation steps:**

### **1. Copy Files to the Virtual Disk**  
- Open **File Explorer** → Go to the new drive (`C: or D:`), where the folder created in the New Virtual Disk
- Create a new folder (`Autospy`) and copy **images or files** into it.  

### **2. Delete the Files**  
- Select any one or two images → Press **Delete**.  
- Empty the **Recycle Bin** to permanently delete them.  

### **3. Recover Deleted Files Using Autopsy**  
### **Open Autopsy & Create a New Case** 

- Launch **Autopsy** and **Run as a administrator**  
- Click **Create New Case**.  

![Screenshot 2025-03-27 214747](https://github.com/user-attachments/assets/41aa5c92-3329-4595-a283-9ad6b202926e)


- Enter a **Case Name** (e.g., `Autopsy1`).  
- Choose a **Case Folder** location.  
- Click **Next** → Click **Finish**.  

<img width="584" alt="image" src="https://github.com/user-attachments/assets/9e055294-3e6c-4b1a-9b98-0118420d6297" />


### **Add the Virtual Disk as an Evidence Source**  
- Click **Add Data Source**  → **Select Host**

<img width="643" alt="image" src="https://github.com/user-attachments/assets/52048bce-12b8-4768-9e78-e8d79c7e6743" />


- Select **Local Disk** → **next** 

<img width="644" alt="image" src="https://github.com/user-attachments/assets/482cd74a-8b24-482a-9cfd-5535ac371b41" />


- Select Disk → **Choose the VHD drive (`Drive1`)**

<img width="453" alt="image" src="https://github.com/user-attachments/assets/5772ccd1-96e9-4db6-a90a-62d07f2372bf" />


- Click **Next** → Keep default settings → Click **Finish**.  
- Wait for Autopsy to process the disk.  

### **Recover Deleted Files**  
- Go to **File Views** (left panel).  

<img width="614" alt="image" src="https://github.com/user-attachments/assets/50a54b9e-0e2a-48f7-8fab-db25bd1ba0b8" />

<img width="617" alt="image" src="https://github.com/user-attachments/assets/e1e3be9c-a047-4855-a89d-d2331e1b03bb" />






- Click **Deleted Files** → Find your deleted images.  
- Right-click an image → Click **Extract File**.  

<img width="620" alt="image" src="https://github.com/user-attachments/assets/d9627ddb-6ae4-4ecb-9182-b9fb2befbfb0" />


- Select a folder to see the recovered files (e.g., `C:\forensic`).  
- Image is recovered successfully.


## Output :
### Folder before deleting the files
<img width="620" alt="image" src="https://github.com/user-attachments/assets/0b16773a-c173-4614-83b1-22c104236f64" />


### Folder after deleting the files
<img width="618" alt="image" src="https://github.com/user-attachments/assets/7031c429-684a-4683-a753-7e887e5ed375" />


### Folder after extracting the deleted images using autopsy
<img width="619" alt="image" src="https://github.com/user-attachments/assets/2db16db7-48b1-4869-8274-6b39e43511c0" />


## Result:
Successfully extracted the deleted files from unallocated space using the Autospy tool.
