# MAS-Dignosis

This document describes the scenario of the multi-agent system, and the setup instructions.

## Setup
### 1. Download and Decompress
    1.1. Download the "health.zip" file that contains all files of the project.

    1.2. Decompress it and move the folder to your jason environment directory.
         Please NOTE: the tree of the project directory should be like the following structure:
    
    ├── Readme.txt
    ├── bin
    │   ├── classes
    │   └── health.xml
    ├── health.mas2j
    └── src
        ├── asl
        │   ├── doctorA.asl
        │   ├── doctorB.asl
        │   ├── patient.asl
        │   └── stock_manager.asl
        └── java
    
### 2. Import the Project
    2.1. Open "Eclipse";
    
    2.2. Click "File", then choose "Open Projects from File System";
    
    2.3. Click "Directory", which is at the end of "Import source" bar;
    
    2.4. Select "health" folder in your workspace folder, whose names are "eclipse-workspace" in Mac OS and Windows;
    
    2.5. Tick the square before "health", click "Finish";


### 3. Run the Project
    3.1. After successfully import the project via Eclipse, select the "health" in the Jason Navigator bar, we may find that            there are 2 errors in the Problems tab, one of which's type is "Build Path Problem", right click it. Select the                "Quick Fix";
    
    3.2. Select "Configure build path...", then click "Finish";
    
    3.3. Select "Libraries" tab, remove MY library, in which case whose name starts with "jason-2.4.jar - ...";
    
    3.4. Switch to "Order and Export" tab, click "JRE System Library [jdk-version]" in Windows and in Mac OS. Click "Apply and          Close";
    
    3.5. Now, please feel free to run the project by clicking "Run Jason Application".
