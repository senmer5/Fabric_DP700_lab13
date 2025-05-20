# Creating a Real-Time Dashboard with Microsoft Fabric 📊✨

## Lab Objective 🎯

The goal of this lab is to learn how to create a dynamic and interactive real-time dashboard using Microsoft Fabric platform. By the end of this lab, you will understand how to ingest data from Eventhouse, visualize it on a real-time dashboard, add parameters for user interaction, and manage the dashboard effectively.

---

### 1. Create a Workspace 🏢

- Go to the Microsoft Fabric homepage and sign in.
- Click on **Workspaces** from the left menu.
- Create a new workspace. Make sure your license supports Fabric capacity (Trial, Premium, or Fabric).
- Open the newly created workspace; it will be empty.

---

### 2. Create an Eventhouse 🏠📥

- Click **Create** from the left menu.
- In the **Real-Time Intelligence** section, select **Eventhouse**.
- Provide a unique name for your Eventhouse and create it.
- Once opened, you will see a Kusto Query Language (KQL) database with the same name.

---

### 3. Create an Eventstream (Event Flow) 🔄📡

- In your KQL database homepage, select **Get data**.
- Choose **Eventstream > New eventstream** as the data source and give it a meaningful name (e.g., Bicycle-data).
- Start the stream using sample data (e.g., bike data).
- Configure the data source and target table (e.g., bikes-table).
- Select JSON as the data format.
- Publish the stream and verify that data is arriving into the table.

---

### 4. Build the Real-Time Dashboard 📈🖥️

- Go to the **Home** hub from the left menu.
- Create a new **Real-Time Dashboard** (e.g., bikes-dashboard).
- Add a new data source to the dashboard by selecting the Eventhouse database.
- Add a new **tile** (section) to the dashboard.
- For the first tile, add a table showing the number of bikes and empty parking spots in the last 30 minutes.
- Convert this table into a **bar chart** and customize its appearance.
- Add another tile.
- This time, add a **map** visualization to show bike locations.

---

### 5. Create a Base Query 📋🔍

- If multiple visuals use the same dataset, managing them with a single base query is efficient.
- Create a base query that fetches common data and configure charts to use this query.
- This centralizes data management and improves dashboard performance.

---

### 6. Add Parameters 🎛️🔧

- Add a **parameter** to allow users to select specific neighborhoods.
- Filter bike and parking spot data based on the selected parameter.
- Update the base query to apply this filter.
- Users can filter data by selecting neighborhoods in the dashboard.

---

### 7. Add New Pages ➕

- Add additional pages to your dashboard to present different data or views.
- Create new pages and add charts or tables as needed.

---

### 8. Configure Auto-Refresh ⏰🔄

- Set the dashboard to refresh automatically at regular intervals.
- This keeps data up-to-date without manual refresh.
- For example, set auto-refresh every 30 minutes.

---

### 9. Save and Share the Dashboard 💾📤

- Save your completed dashboard.
- Generate shareable links to provide access to others.
- Shared links allow others to view the dashboard.

---

### 10. Clean Up Resources 🧹❌

- When finished, delete the workspace to clean up resources.
- This prevents unnecessary charges.

---

## What I Learned 📚

- How to set up real-time data ingestion using Eventhouse in Microsoft Fabric.
- Visualizing streaming data in real-time dashboards.
- Creating different visual components like charts, maps, and tables.
- Using base queries for efficient and performant data management.
- Adding parameters for user-driven data filtering.
- Managing dashboard pages and layouts.


---

## Screenshots

<img width="854" alt="1" src="https://github.com/user-attachments/assets/7e695e3b-d755-4989-aed0-12749e1ceabf" />

<img width="1363" alt="2" src="https://github.com/user-attachments/assets/e7015645-9b39-44f9-8cb6-6c5309fd00d6" />

<img width="1402" alt="3" src="https://github.com/user-attachments/assets/a28410a0-4e70-4ad4-a363-4f31078aafcd" />

<img width="1433" alt="4" src="https://github.com/user-attachments/assets/009a7442-4783-4d74-ae94-aecc997c88a7" />

<img width="1419" alt="5" src="https://github.com/user-attachments/assets/8ec388f1-dd0e-4dfb-9f19-f1085c10275a" />

<img width="1183" alt="6" src="https://github.com/user-attachments/assets/3d4dbc7f-3ba0-48f7-bb0f-e1a8ec1e45a7" />

<img width="1495" alt="7" src="https://github.com/user-attachments/assets/0217ff23-258e-4558-84a5-c63d2454b389" />

<img width="1479" alt="8" src="https://github.com/user-attachments/assets/07cbe03d-8926-4800-bed6-16cbd21698fb" />

<img width="1438" alt="9" src="https://github.com/user-attachments/assets/84f0251e-1f10-4198-948a-f371de968382" />

<img width="1437" alt="10" src="https://github.com/user-attachments/assets/a12cee2b-7963-4a53-b38d-8e64788381d7" />

<img width="1444" alt="11" src="https://github.com/user-attachments/assets/d097d6f1-9cf5-46db-97c3-f0d11f742408" />

<img width="1442" alt="12" src="https://github.com/user-attachments/assets/5242c662-5f1e-4b08-a374-0578dd4ccbbd" />

<img width="1418" alt="13" src="https://github.com/user-attachments/assets/d2bbb95f-0116-4e22-860b-f734e46e6be7" />

<img width="968" alt="14" src="https://github.com/user-attachments/assets/5f0d076c-8dbd-4c3a-b2f4-599473a5c368" />

<img width="1299" alt="15" src="https://github.com/user-attachments/assets/3aba26fc-e636-4948-8ca5-c7e7fb33caf1" />

<img width="1459" alt="16" src="https://github.com/user-attachments/assets/04b4b294-2a29-4576-b30b-6e8dfac10e78" />
