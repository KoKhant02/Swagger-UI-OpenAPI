# Swagger UI OpenAPI Example

This project demonstrates how to set up Swagger UI with an OpenAPI specification. The API definition is provided in the `user-api.yaml` file, and Swagger UI is used to visualize and interact with the API documentation.

## Prerequisites

Before running this project, make sure the following installed:

- [Node.js](https://nodejs.org/) (version 16 or higher)
- [npm](https://npmjs.com/)
- [Docker](https://www.docker.com/) *(optional)*

## Setup and Run the Project

### 1. Clone the Repository

First, clone this repository to local machine:

```bash
git clone https://github.com/KoKhant02/Swagger-UI-OpenAPI.git
cd Swagger-UI-OpenAPI
```

---

### 2. Install Dependencies

```bash
npm install
```

This will install the necessary packages to run the Swagger UI with OpenAPI specification.

---

### 3. Run the Project Locally

Run this project locally using `http-server`. The `dist` folder contains the static files for Swagger UI.

#### Step-by-Step Instructions:

1. Navigate to the `dist` directory:

    ```bash
    cd dist
    ```

2. Start a local server using `http-server`:

    ```bash
    http-server -p 8080
    ```

   This will serve the Swagger UI at `http://localhost:8080`.

3. Open browser and go to `http://localhost:8080` to view the API documentation.

---

### 4. Interact with the API

Once the Swagger UI is running, developer should be able to see the API documentation loaded from `user-api.yaml`. Developer can explore the API endpoints and make sample API calls directly from the Swagger UI interface.

---
