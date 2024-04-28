# Blogs-FastAPI-
Note *** Switch to master branch for code <br><br>
The FastAPI Blog API is a RESTful web service built using FastAPI, allowing CRUD (Create, Read, Update, Delete) operations on blog posts. It provides endpoints for managing blog posts with authentication using JWT tokens and OAuth2. The API also integrates Swagger UI and ReDoc for interactive API documentation.

![FastAPI - Swagger UI](https://github.com/shanu-shahbin/Blogs-FastAPI-/assets/107126924/7c4c47d3-3b0d-4566-a6ae-0d331bc50fc1)

## Features

- **CRUD Operations:** Perform Create, Read, Update, and Delete operations on blog posts.
- **Interactive API Documentation:** Integrated Swagger UI and ReDoc for easy exploration of API endpoints.
- **Authentication:** Secure endpoints using JWT tokens and OAuth2 for user authentication.
- **Validation:** Input data validation ensures data integrity and security.
- **Pagination:** Paginate through large collections of blog posts to improve performance.
- **Search:** Search functionality to find specific blog posts based on keywords.
- **User Management:** Manage users with roles and permissions for accessing resources.
- **Testing:** Thoroughly tested using Postman API for reliability and stability.
- **Logging:** Comprehensive logging to track API requests, errors, and system behavior.
- **Deployment:** Easily deploy the API to various platforms such as AWS, Azure, or Google Cloud.


![FastAPI - auth](https://github.com/shanu-shahbin/Blogs-FastAPI-/assets/107126924/547ebad1-3e69-4de4-8b70-051ee09a81cc)

## Prerequisites


Before running the project, make sure you have the following installed:

- Python 3.7+
- [FastAPI](https://fastapi.tiangolo.com/)
- [uvicorn](https://www.uvicorn.org/)
- [PyJWT](https://pyjwt.readthedocs.io/en/stable/)
- [OAuthlib](https://oauthlib.readthedocs.io/en/latest/)
- [Postman](https://www.postman.com/) (for testing)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/your_username/fastapi-blog-api.git
   ```

2. Navigate to the project directory:

   ```bash
   cd fastapi-blog-api
   ```

3. Install the dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the FastAPI server using uvicorn:

   ```bash
   uvicorn main:app --reload
   ```

2. Open your web browser and navigate to [http://localhost:8000/docs](http://localhost:8000/docs) for the Swagger UI or [http://localhost:8000/redoc](http://localhost:8000/redoc) for the ReDoc documentation.

3. Authenticate using JWT tokens or OAuth2 to access protected routes.

## Testing

You can test the API using Postman:

1. Import the provided Postman collection (`fastapi-blog-api.postman_collection.json`) into Postman.
2. Use the collection to send requests to the API endpoints and verify the responses.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---


