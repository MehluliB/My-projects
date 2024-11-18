## **Setting Up Visual Studio 2022 and Device Specifications**

### **Device Specifications**
To ensure the smooth operation of the application, here are the minimum and recommended device specifications:
- **Operating System**: Windows 10 or higher
- **Processor**: Intel Core i5 or AMD equivalent (or better)
- **RAM**: 8GB minimum (16GB recommended for optimal performance)
- **Storage**: At least 10GB of free space
- **Graphics**: DirectX 11 compatible graphics card

---

### **Steps to Set Up Visual Studio 2022**
1. **Download Visual Studio 2022**:
   - Visit the [Visual Studio website](https://visualstudio.microsoft.com/) and download the **Community Edition**.

2. **Install Workloads**:
   - During installation, select the following workload:
     - **.NET desktop development**: For creating Windows Forms applications.

3. **Create a New Project**:
   - Open Visual Studio and choose **Create a new project**.
   - Select **Windows Forms App (.NET Framework)** from the list and click **Next**.

4. **Set Up Your Project**:
   - Follow the prompts to configure your project. 
   - Ensure you select **.NET 6.0 or later** for compatibility with the latest features.

Once Visual Studio is set up, you’re ready to begin developing and running the **Municipal Services Application**.

---

## **Welcome to the Municipal Services Application**

### **How the App Works**

#### **Dashboard Navigation**
<img width="959" alt="Home" src="https://github.com/user-attachments/assets/05d0352c-edaf-4688-b087-52c9bb57f4e4">



Upon opening the app, you’ll be greeted with the dashboard, featuring two main options:
1. **Menu Tab**: Access the various functionalities of the application.
2. **Exit Button**: Close the application.

---

### **Menu Options**
<img width="955" alt="buttons" src="https://github.com/user-attachments/assets/14e99462-e5ac-40c4-9f53-fa1cc2920d6e">



Clicking the **Menu Tab** reveals the following options:
1. **Report Issues**
2. **Local Events and Announcements**
3. **Service Request Status**

---

### **Key Features**

#### **1. Report Issues**
<img width="959" alt="Screenshot 2024-11-18 084811" src="https://github.com/user-attachments/assets/a364b076-790f-4a11-9a0e-80880ce20392">



The **Report Issues** page allows users to log issues in their area:
- **Location**: Specify the location of the issue.
- **Category**: Choose the type of issue (e.g., roadblock, water outage).
- **Description**: Provide a detailed description of the issue.
- **All files**: Optionally attach an file to support your report.

**Submitting Your Report**:
- Once all required information is filled out, click **Submit**.
- A confirmation message will notify you that the report has been successfully saved.

---

#### **2. Local Events and Announcements**
<img width="959" alt="Screenshot 2024-10-15 141659" src="https://github.com/user-attachments/assets/50a771b6-2d08-459a-bd48-83d4b89f5bbc">


The **Local Events and Announcements** page provides an organized list of upcoming events. Users can:
- Browse events in a clear, table-based format.
- Use **search and filter** options to refine results by keyword, category, or date.

**Recommendations**:
<img width="959" alt="Screenshot 2024-10-15 141630" src="https://github.com/user-attachments/assets/409a6dbe-983f-4093-9d80-4fc3002010ec">



At the bottom of the page, a recommendation table dynamically displays the most frequently searched event categories. This helps users discover popular or trending events.

---

#### **3. Service Request Status**
<img width="959" alt="Screenshot 2024-11-18 082044" src="https://github.com/user-attachments/assets/a29a5be8-edf4-424b-a0c8-4f9557c8a883">


The **Service Request Status** page provides a comprehensive overview of logged service requests. Key features include:

1. **List of Service Requests**:
   - Displays up to 10 logged requests, each with a title and ID.
   - Users can select a request to view detailed information.

2. **Progress Bar Integration**:
   - Visually represents the completion percentage of a selected request.
   - Enhances the UI by offering a clear and intuitive way to track progress.

3. **Request Details Panel**:
   - Located on the right side of the page.
   - Displays detailed information about the selected request, including:
     - Request ID
     - Title
     - Status
     - Description

4. **Heaps Panel**:
   - Displays a sorted list of requests using a **heap data structure**, sorted by ID.
   - Provides insights into how requests are prioritized and organized.

---

### **How It Works**
<img width="959" alt="Screenshot 2024-11-18 082113" src="https://github.com/user-attachments/assets/9045a217-3138-4826-a9db-f3e389286813">

1. **Tracking User Actions**:
   - The app tracks user searches and interactions with service requests and events.

2. **Dynamic Updates**:
   - The recommendation table and sorted lists are updated dynamically based on user input and search history.

3. **UI Enhancements**:
   - The integration of a progress bar and structured layout ensures users can navigate the app seamlessly and access critical information quickly.
  
-----------------------------------------------------------
Youtube app demo:https://youtu.be/pymzm2QaSJQ?si=4KwmTkzkq2uC3QAj
