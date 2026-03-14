# Install Autopsy and Analyze the Disk File and Folder Configuration
## NAME: Abishai K C
## Reg no:2122223240002
## AIM
To install **Autopsy** and use it to analyze the disk’s file and folder configuration for forensic investigation.

## REQUIREMENTS
- **Operating System**: Windows 10/11, macOS, or Linux
- **Tools**:  
  - [Autopsy Digital Forensics Platform](https://www.autopsy.com/)  
  - Optional: Sleuth Kit CLI tools for deeper analysis
- **Test Data**: Disk image file (`.dd`, `.img`, `.E01`)

## ARCHITECTURE DIAGRAM
```mermaid
flowchart TD
    A[Disk Image / Physical Drive] --> B[Install Autopsy]
    B --> C[Create New Case in Autopsy]
    C --> D[Add Data Source: Disk Image]
    D --> E["Autopsy Modules Run: File System, Metadata, Keywords"]
    E --> F[File & Folder Structure View]
    F --> G[Export / Recover Files]
```
## DESIGN STEPS:
### Step 1:
Download Autopsy from the official website and install it on your system.

### Step 2:
Launch Autopsy and create a new case.

### Step 3:
Add your disk image or physical drive as the data source.

### Step 4:
Allow Autopsy to run its built-in ingest modules (file system analysis, hash lookup, keyword search, metadata extraction).

### Step 5:
View the file and folder hierarchy in the left-hand tree panel.

### Step 6:
Export or recover files if required for the investigation.

## PROGRAM(Windows)

1. Download Autopsy from autopsy.com.
2. Install and launch the application.
3. Select **New Case → Name your case → Choose case folder**.
4. Click Add **Data Source → Select Disk Image → Browse to file**.
5. Choose ingest modules (file system, metadata, hash lookup, keyword search).
6. Wait for processing to finish.
7. Explore file/folder structure in the navigation pane.
8.Export selected files for further examination.

## OUTPUT:
File and Folder Configuration Analysis Results
<img width="1697" height="993" alt="image" src="https://github.com/user-attachments/assets/d1f9c7e7-adcc-46e9-93d4-57261883ce54" />

<img width="1702" height="1003" alt="image" src="https://github.com/user-attachments/assets/1153e999-15ff-4274-9646-ebb1f6828627" />

<img width="1720" height="966" alt="image" src="https://github.com/user-attachments/assets/786363ec-ca0e-4d48-82cc-ba37ec89df69" />

<img width="1650" height="969" alt="image" src="https://github.com/user-attachments/assets/c8ae6de7-1108-4890-8887-fede73dc27e6" />

<img width="1733" height="985" alt="image" src="https://github.com/user-attachments/assets/ab4d42ad-ffb8-4437-a975-af9c945ca6fb" />

<img width="1345" height="806" alt="image" src="https://github.com/user-attachments/assets/0acbf083-9c00-4668-b06c-39df8b5848b8" />

<img width="1493" height="878" alt="image" src="https://github.com/user-attachments/assets/58aad088-17b8-40a4-9d7f-846f0286d1e3" />

<img width="1521" height="899" alt="image" src="https://github.com/user-attachments/assets/34be5143-7db3-42d0-8906-450ea4c0f310" />

## RESULT:
Autopsy was installed successfully and used to analyze disk, file, and folder configuration for forensic investigation.
