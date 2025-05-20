# How to Run API Tests in Postman via Browser (Step by Step)

## Requirements

- A web browser (Chrome, Firefox, Edge – any)
- An account on [postman.com](https://www.postman.com) (free)

---

## Usage

### 1. Download the Collections

Download the Postman collection files to your local machine. You can either:

- Clone the entire repository  
or  
- Download each file manually

It's up to you.

---

### 2. Sign Up or Log In to Postman Web

1. Go to: [https://www.postman.com](https://www.postman.com)  
2. Click **Sign In** or **Sign Up** if you don’t have an account yet

---

### 3. Open or Create a Workspace

- Click **Workspace** from the left menu
- Choose **My Workspace** (default) or create a new one

---

### 4. Go to the Collections Tab

- Click on **Collections** from the left sidebar

---

### 5. Import Your Collection File

1. Click the **Import** button (top right corner)  
2. Select **Upload Files**  
3. Choose your `*.postman_collection.json` file from the repository  
4. Click **Import**

*If you also have an environment file (`*.postman_environment.json`), import it the same way.*

---

### 6. Run the Collection

1. Go to the **Collections** tab again  
2. Click on the imported collection  
3. Click **Run** (top right corner of the collection – opens Collection Runner)  
4. Select the environment (if imported)  
5. Click **Run Collection**

---

### 7. View Test Results

After a few seconds you’ll see:

- Status of each request (e.g., 200 OK, 401 Unauthorized)
- Test results (green/orange/red indicators)
- Full API response details

---

## Done!

You're all set.  
No need to install anything – everything works directly in your browser.
