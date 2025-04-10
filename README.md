# 🧪 API Testing with Postman Project

Welcome to my Postman API Testing project! This repository showcases my hands-on experience with API testing using Postman. It includes a well-organized collection of REST API requests, environment variables, test scripts, and documentation — all designed to demonstrate robust API testing workflows.


## 📌 Project Overview

This project contains a sample Postman collection designed to test common CRUD operations on a RESTful API. It demonstrates:

- ✅ GET, POST, PUT, DELETE methods
- 🌍 Use of environments for flexible testing
- 🧠 Test scripts and pre-request scripting (JavaScript)
- 📄 Documentation using Postman's built-in features
- 🚀 Collection runner & automation compatibility (Newman-ready)


## 📁 Folder Structure


📦 api-testing-postman/
 ┣ 📄 MyAPI.postman_collection.json
 ┣ 📄 MyEnvironment.postman_environment.json
 ┗ 📄 README.md


## ⚙️ How to Use

1. **Clone this repository:**
   ```bash
   git clone https://github.com/your-username/api-testing-postman.git](https://github.com/ParameeDilanka/Postman-API-Testing-Project
   ```

2. **Open Postman:**
   - Import the collection: `MyAPI.postman_collection.json`
   - Import the environment: `MyEnvironment.postman_environment.json`

3. **Run Tests:**
   - Use the **Collection Runner** to execute all requests.
   - Or use **Newman** for CLI-based test runs:
     ```bash
     newman run MyAPI.postman_collection.json -e MyEnvironment.postman_environment.json
     ```


## 🛠 Features Demonstrated

| Feature                  | Description                                                                 |
|--------------------------|-----------------------------------------------------------------------------|
| Request Methods          | GET, POST, PUT, DELETE                                                      |
| Auth Handling            | Header injection for bearer tokens                                          |
| Pre-request Scripts      | Automated token generation (if needed)                                      |
| Test Scripts             | JavaScript assertions using `pm` API                                        |
| Environment Variables    | Reusability across different test setups                                    |
| Response Validations     | Status code, response time, JSON schema validation                          |



## 📃 License

This project is open-source and available under the [MIT License](LICENSE).
