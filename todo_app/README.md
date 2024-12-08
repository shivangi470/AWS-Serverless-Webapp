
---

# 🌟 **AWS-Powered To-Do List App**  

A **serverless full-stack To-Do List application** that allows users to seamlessly manage their tasks. Built with React, AWS services, and Express.js for a scalable and robust user experience.  

---

## ✨ **Features**  
- 📝 Add new tasks.  
- ✅ Mark tasks as completed.  
- 🛠 Edit or delete existing tasks.  
- 🌐 Serverless backend powered by AWS Lambda and DynamoDB for scalability.  

---

## 🛠 **Technologies Used**  

| Technology | Description |
|------------|-------------|
| 🌐 **Frontend**  | React, Material UI |
| ⚙️ **Backend**   | Express.js, Node.js |
| 🗄 **Database**  | DynamoDB |
| ☁️ **Cloud**     | AWS Lambda, API Gateway, AWS Amplify |

---

## 🚀 **Project Setup Instructions**

### 🖥 **Frontend (React):**
1. Open your terminal and navigate to the `ui` directory:  
   ```bash
   cd ui
   ```  
2. Install dependencies:  
   ```bash
   npm install
   ```  
3. Start the React app:  
   ```bash
   npm start
   ```  
4. Your app will be running at [http://localhost:3000](http://localhost:3000).  

---

### 🛠 **Backend (Express API):**
1. Open a new terminal and navigate to the `api` directory:  
   ```bash
   cd api
   ```  
2. Install dependencies:  
   ```bash
   npm install
   ```  
3. Start the API server:  
   ```bash
   npm run dev
   ```  
4. The API will run at [http://localhost:3001](http://localhost:3001).  

---

### ☁️ **AWS Setup**  

#### 🗄 **1. DynamoDB**  
- Create a DynamoDB table with:  
  - **Table Name**: `TodoList`  
  - **Primary Key**: `id` (string)  
  - **Attributes**: `task` (string), `completed` (boolean)  

#### ⚙️ **2. Lambda Functions**  
- Implement Lambda functions for:  
  - ➕ Adding tasks  
  - 📋 Retrieving tasks  
  - 🛠 Updating tasks  
  - 🗑 Deleting tasks  

#### 🌐 **3. API Gateway**  
- Create endpoints for:  
  - `POST /tasks` - Add a task  
  - `GET /tasks` - Retrieve tasks  
  - `PUT /tasks/{id}` - Update a task  
  - `DELETE /tasks/{id}` - Delete a task  

#### 🌎 **4. Amplify**  
- Deploy your React app using AWS Amplify:  
  ```bash
  amplify init
  amplify publish
  ```  

---

## 📚 **Helpful AWS Documentation**  

- 🔧 **DynamoDB CRUD Operations**:  
  - [Create](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/example_dynamodb_PutItem_section.html)  
  - [Read](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/example_dynamodb_Scan_section.html)  
  - [Update](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/example_dynamodb_UpdateItem_section.html)  
  - [Delete](https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/example_dynamodb_DeleteItem_section.html)  

- ⚙️ **Lambda**:  
  [Getting Started](https://docs.aws.amazon.com/lambda/latest/dg/getting-started.html)  

- 🌐 **API Gateway**:  
  [Create REST API](https://docs.aws.amazon.com/apigateway/latest/developerguide/apigateway-rest-api.html)  

- 🌎 **Amplify**:  
  [Getting Started](https://docs.amplify.aws/start/)  

---

## 🧩 **Pushing Code to GitHub**

1. Initialize Git in the root directory:  
   ```bash
   git init
   ```  
2. Add files to Git:  
   ```bash
   git add .
   ```  
3. Commit changes:  
   ```bash
   git commit -m "feat: initial AWS To-Do List setup"
   ```  
4. Add the GitHub repository:  
   ```bash
   git remote add origin <your-github-repo-url>
   ```  
5. Push the code:  
   ```bash
   git push -u origin main
   ```  

---

## 🎉 **Enjoy your AWS-Powered To-Do List App!**  

---
