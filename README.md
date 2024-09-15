Fruit.ai

# Fruit.ai Frontend

## Description

This is the frontend application for Fruit.ai, a health management product designed to help users learn about fruits, manage their health, and access translation and FAQ services.

## Setup

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/fruit-ai-frontend.git
   cd fruit-ai-frontend

Or run the following command:
npx-create-react-app Fruit.ai
npm install react react-dom react-router-dom




# Fruit.ai Backend

## Setup

1. Create a virtual environment and activate it:

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows: venv\Scripts\activate
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Run the Flask app:

    ```bash
    python app.py
    ```

## API Endpoints

- `GET /faqs` - Fetch all FAQs
- `GET /faqs/<id>` - Fetch an FAQ by ID
- `POST /faqs` - Create a new FAQ
- `PUT /faqs/<id>` - Update an FAQ by ID
- `DELETE /faqs/<id>` - Delete an FAQ by ID
