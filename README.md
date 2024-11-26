# FreedAMA

## Student Details
- **Name**: Whendell Tan
- **Course**: Application Development
- **Student ID No**: 19002321100


## Description of the System
The **FreedAMA** is a web-based exclusive platform design to create a safe and engaging space for students to share their thoughts, opinion, and personal experiences.

Key features:
- User authentication 
- Post creation and Management
- Accessible Design
- AI Chatbot Integration

## Technologies Used
- **Backend**: Django (Python)
- **Frontend**: HTML, CSS, JavaScript, Bootstrap
- **Database**: MySQL
- **Authentication**: Django's built-in authentication system
- **AI/Chatbot**: DialogFlow

## How to Run Locally

1. **Clone the repository**

2. **Set up a virtual environment**:
    If you don’t have `virtualenv` installed, you can install it using:
    ```bash
    pip install virtualenv
    ```
    Then create a virtual environment:
    ```bash
    virtualenv venv
    ```
    Activate the virtual environment:
    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On Mac/Linux:
      ```bash
      source venv/bin/activate
      ```

3. **Install the required dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Run db.py to set up the database**:
    - Create a MySQL database for the project.
    - Update the `settings.py` file with your MySQL database credentials.

5. **Run migrations**:
    ```bash
    python manage.py migrate
    ```

6. **Create a superuser** (for admin access):
    ```bash
    python manage.py createsuperuser
    ```

7. **Run the development server**:
    ```bash
    python manage.py runserver
    ```
    Now, you can access the application by opening a web browser and going to `http://127.0.0.1:8000/`.

## Additional Information
- **Authentication**: The application uses Django's built-in authentication system, which allows users to register, log in, and manage their profiles.
- **AI Chatbot**: The AI Chatbot is integrated for assistance with frequently asked questions. It provides real-time support to users.



---

### Created by Whendell Tan
