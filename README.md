## ✅ Pre-Requisites

### 1. Install Java (JDK)

- 🔗 Download:  
  [https://www.oracle.com/nz/java/technologies/downloads/#java17-windows](https://www.oracle.com/nz/java/technologies/downloads/#java17-windows)

- ⚙️ Set `JAVA_HOME` (Environment Variable):

  #### Step 1: Set `JAVA_HOME`

  - Press `Windows + S` → Search for **"Environment Variables"**
  - Click **"Edit the system environment variables"**
  - In the **System Properties** window → Click **"Environment Variables…"**
  - Under **System Variables** → Click **New…**
    - **Variable name**: `JAVA_HOME`  
    - **Variable value**:
      ```
      C:\Program Files\Java\jdk-17
      ```

  #### Step 2: Add `JAVA_HOME\bin` to `Path`

  - Still under **System Variables**, find **Path** → Click **Edit…**
  - Click **New**, and add:
    ```
    %JAVA_HOME%\bin
    ```

---

### 2. Install Apache Spark

- 🔗 Download:  
  [https://spark.apache.org/downloads.html](https://spark.apache.org/downloads.html)

- 📦 Extract the `.tgz` file to a folder like: C:\spark

- ⚙️ Set `SPARK_HOME` (Environment Variable):

#### Repeat the steps for `SPARK_HOME`:

- **Variable name**: `SPARK_HOME`  
- **Variable value**:
  ```
  C:\spark\spark-4.0.0-bin-hadoop3
  ```

#### Add `%SPARK_HOME%\bin` to `Path`:

- Still under **System Variables**, find **Path** → Click **Edit…**
- Click **New**, and add:
  ```
  %SPARK_HOME%\bin
  ```
