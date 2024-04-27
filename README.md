## Ultimate PDF Toolkit 

* Experience the power of collaborative PDF editing and real-time discussions with the Ultimate PDF Toolkit.

1. **Clone the Repository:**

   ```
   git clone https://github.com/your-repo/your-project.git
   ```

2. **Navigate to the Project Directory:**

   ```
   cd your-project
   ```

3. **Create Required Directories:**

   Create the following directories in the project root:

   - `cache`


4. **Create a `.env` File:**

   Create a `.env` file in the `cache` directory.

5. **Run Docker Compose:**

   ```
   docker-compose up -d
   ```

   This command will build and start the services defined in the `docker-compose.yml` file in detached mode.

6. **Accessing the Services:**

   - **`anythingllm` Service:** Accessible at `http://localhost:3001`
   - **`vectordb` Service:** No direct access needed.
   - **`ollama` Service:** No direct access needed.
   - **`stirling` Service:** Accessible at `http://localhost:8081`

7. **Stopping the Services:**

   ```
   docker-compose down
   ```

   This command will stop and remove the containers created by Docker Compose.

---

To provide access to these services you can use the  `index.html` file in your project's root directory with links to the services' endpoints.

