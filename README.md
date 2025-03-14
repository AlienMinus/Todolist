Minus -TodoList


<h3>
To create site.db
</h3>
<h6>
Run the following Command in Your Terminal
</h6>
<p>
from app import db, create_app  # Import `create_app()` if your app uses a factory function

app = create_app()  # Initialize the Flask app
with app.app_context():  # Activate app context
    db.create_all()
</p>