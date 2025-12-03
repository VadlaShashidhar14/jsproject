# 📘 ICN (IBM Content Navigator) – Complete Overview

## 🧩 What is ICN (IBM Content Navigator)?

IBM Content Navigator (ICN) is a web-based user interface for interacting with IBM FileNet and other ECM repositories.  
It serves as the front-end UI that allows users to:

- Upload and manage documents  
- View and edit metadata  
- Search documents  
- Handle workflows  
- Connect to FileNet Content Engine (CE) and Process Engine (PE)

---

## 🏆 Why We Use ICN

### ✔️ 1. Unified Interface
Access multiple repositories in one place:
- FileNet CE  
- IBM Case Manager  
- IBM Datacap  
- Multiple FileNet Object Stores

### ✔️ 2. Document Management
- Upload / Download  
- Edit metadata  
- Version control  
- Folder browsing  
- Property-based search  

### ✔️ 3. Workflow Handling
- View workflow inbox  
- Process work items  
- Submit responses  
- Add comments / attachments  
- Dispatch workflow steps  

### ✔️ 4. Extensibility
Supports custom:
- Plugins  
- Actions  
- Menus  
- Widgets  
- JavaScript extensions  

### ✔️ 5. Secure Centralized Access
Includes:
- Authentication

### 2. Select Desktop
Desktops are customized environments, e.g.:
- HR Desktop  
- Admin Desktop  
- Claims Desktop  

### 3. Browse or Search Documents
- Navigate folders  
- Use advanced search  
- Use saved searches  
- Access teamspaces  

### 4. Upload or Edit Documents
- Add new documents  
- Edit properties (metadata)  
- Check-in / Check-out  
- Version updates  

### 5. Work on Workflows
If connected to Process Engine:
- Open **Work → Inbox**  
- Select work item  
- Fill data fields  
- Add attachments  
- Click **Complete / Dispatch**  

### 6. Customize ICN (Admin/Developer)

**Admins can:**
- Configure repositories  
- Create desktops  
- Assign permissions  
- Create search templates  

**Developers can:**
- Build plugins  
- Add custom actions  
- Enhance metadata forms  
- Add custom features via JavaScript  

---

## 🔍 Simple Example

### Scenario: Uploading a Salary Slip to HR

**Steps:**
1. Login to ICN  
2. Select **HR Desktop**  
3. Navigate to **Employee Documents**  
4. Click **Add Document**  
5. Upload PDF  
6. Fill metadata (Employee ID, Month, Year)  
7. Submit → Stored in FileNet CE  

If workflow exists:
- Work item goes to HR Queue  
- HR opens in ICN  
- Reviews → Dispatch  

---

## 📌 Summary Table

| Feature | Description |
|--------|-------------|
| UI | Web interface for FileNet |
| Document Management | Upload, versioning, metadata editing |
| Workflow | Complete steps, handle inbox tasks |
| Search | Metadata-based search templates |
| Integration | CE + PE + Case Manager + Datacap |
| Extensibility | Plugins, custom actions, widgets |
