# Priti Backend Exam

This repository contains the assignment for the Priti Backend Internship Exam. The exam is designed to assess your skills in Python backend development, data analysis, and basic machine learning, strictly following the provided roadmap.

## Assignment Structure

### Part 1: Django REST API (1.5 hours)
- Build a Library Management System API using Django REST Framework.
- Implement models: Book, Author, Borrower.
- CRUD endpoints for all models.
- Filtering (by author, availability) and pagination for books.
- Custom permission: Borrowers can update only their own borrowed books.
- Efficient use of Django ORM (avoid N+1 queries).

### Part 2: FastAPI Microservice (45 minutes)
- Create a `/recommend` endpoint that accepts genres and returns recommended books (mocked data allowed).
- Use Pydantic for request/response validation.
- Async SQLite database integration.
- API documentation via Swagger/OpenAPI (default in FastAPI).

### Part 3: Data Analysis & ML (45 minutes)
- Use Pandas to analyze API logs (CSV).
- Clean and aggregate data to compute average request latency per endpoint.
- Visualize results with Matplotlib (bar chart).
- Build a basic Linear Regression model (scikit-learn) to predict request latency.

## How to Submit
- Push your code to this repository.
- Include clear setup instructions and explanations for each part in this README.
- Ensure code is well-documented and follows best practices.

## Evaluation Criteria
- Feature completeness and correctness
- Code quality and organization
- Use of Python best practices (OOP, async, data validation)
- Proper use of DRF, FastAPI, Pandas, Matplotlib, and scikit-learn
- Clarity of documentation

## Estimated Time
**3 hours**

---

Good luck!