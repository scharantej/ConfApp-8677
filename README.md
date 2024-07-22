### Flask Application Design

#### HTML Files
- **index.html**: The landing page that showcases the speaker's expertise and persuades conference organizers to book them.
- **contact.html**: A separate page for conference organizers to easily get in touch with the speaker.

#### Routes

- **@app.route('/')**: Main route that renders the **index.html** page.
- **@app.route('/contact')**: Route for the **contact.html** page, where conference organizers can find contact information and a contact form.
- **@app.route('/book')**: Route that handles the booking request from conference organizers. This can be a separate page or a form submission that triggers an email or message to the speaker.