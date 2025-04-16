# Organ Donation App

## Application Features
1. Donor Registration: Users who wish to become organ donors can easily register through the app. 
They will have the option to specify their organ donation preferences, blood type, age, addresses 
and phone number.
2. Organ Donation Hospitals: The app offers a directory of nearby organ donation centres and hospitals. 
Users can search for centres based on location, availability of specific organs, and other relevant 
criteria.
3. Blood Specification: The app offers a directory of specific donors based on the blood types of the 
donors so that they can easily find the most compatible organs.
4. Organ Specification: The app offers a directory of specific organs so that they can easily find 
the exact organs that they might be looking for.

## Requirements
1. Android Studio (Java)
2. Firebase Hosting & Database

## File Description
 
1. Manifest File (AndroidManifest.xml): The manifest file gives the Android system crucial details about your app, including the package name, activities, services, permissions, and hardware requirements.
2. Java Class Code (com.example.orgdon) : There are multiple classes in our project. Dividing our whole project into these multiple classes offers advantages such as modularity, code organisation, reusability, scalability, maintainability, and improved readability and debugging. The whole code can be divided into five types:
    a. Organ List and Classes
    b. Blood List and Classes
    c. Donor and Hospital Lists Classes
    d. Main Activity and Firebase Classes
    e. Adapter Class
3. Resources:
    a. drawables: Contains the icons/vectors required for the application.
    b. layout: Contains the basic designs of the different pages of the application.
    c. values: Contains the references to different values used in the application
    d. menu: Contains the layout of search menu option
4. Gradle Scripts: Contains all the dependencies and libraries that we will import in our project.

## Installation
1. Download the source code.
2. Open Android Studio and click on “Open an Existing Project”.
3. Locate and select the source code folder.
4. Make sure the gradle scripts and the settings are suitable for your IDE and SDK.
5. Work around the files and try to figure out what they all do. Start with AndroidManifest.xml and follow the different codes to different ends.
6. Press the run button at the top bar, it will install the application on a virtual device.
9. Test if the application runs correctly.
10. Customise to your taste.

## Screenshots
<p float="left">
    <img src="https://github.com/YRKaflay/OrgDon/blob/main/Screenshots/HomeScreen.png" width="250" title="HomeScreen" alt="Home Screen of App"/>
    <img src="https://github.com/YRKaflay/OrgDon/blob/main/Screenshots/BloodGroup.png" width="250" title="BloodGroup" alt="Show Blood Groups"/>
    <img src="https://github.com/YRKaflay/OrgDon/blob/main/Screenshots/AddRecord.png" width="250" title="AddRecord" alt="Add a new record"/>
    
</p>
<p float="left">
    <img src="https://github.com/YRKaflay/OrgDon/blob/main/Screenshots/Donors.png" width="250" title="Donors" alt="Show Donor Details"/>
    <img src="https://github.com/YRKaflay/OrgDon/blob/main/Screenshots/Hospital.png" width="250" title="BloodGroup" alt="Show Hospitals"/>
    <img src="https://github.com/YRKaflay/OrgDon/blob/main/Screenshots/RecordsUpdate.png" width="250" title="AddRecord" alt="Update an old record"/>
</p>
