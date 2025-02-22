# SPECSOLVER: Requirements Specification to Design Translator

SpecSculpt is an application designed to translate user requirements for monitoring systems into specific technical parameters, technical sketches, and basic software architecture. This project aims to streamline the design process by automating the extraction of technical specifications and generating design artifacts.

## Features

- **Requirements Collection**: Interactive UI for collecting user requirements.
- **Parameter Extraction**: Automated extraction of technical parameters from requirements.
- **Design Generation**: Generation of technical sketches based on extracted parameters.
- **Architecture Design**: Suggestion of basic software architecture based on requirements.
- **User Feedback**: Mechanism for users to review and provide feedback on generated designs.

## Tech Stack

- **Frontend**:
  - React.js: For building interactive user interfaces.
  - HTML/CSS: For structuring and styling the UI.

- **Backend**:
  - Django: For building the server-side logic.
  - Django REST Framework: For creating APIs.

- **NLP and Machine Learning**:
  - spaCy: For natural language processing.
  - TensorFlow: For building machine learning models.

- **CAD Integration**:
  - OpenSCAD: For programmatic 3D modeling.

- **Database**:
  - PostgreSQL: For relational data storage.

- **Deployment**:
  - Docker: For containerizing the application.
  - Kubernetes: For orchestrating containers.
  - AWS: For cloud deployment.

## Architecture

1. **Presentation Layer**:
   - Web-based UI for user interaction.

2. **Application Layer**:
   - Business logic for processing requirements.
   - NLP module for understanding user inputs.
   - Design generation module for creating sketches.

3. **Data Layer**:
   - Database for storing user requirements and generated designs.
   - File storage for storing sketches and architecture diagrams.

4. **Integration Layer**:
   - APIs for integrating with CAD software.
   - Microservices for modular functionality.

5. **Infrastructure Layer**:
   - Cloud infrastructure for scalability.
   - CI/CD pipelines for automated deployment.

## Getting Started

### Prerequisites

- Python 3.8+
- Node.js and npm
- Docker (optional, for containerization)

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/specsculpt.git
   ````
2. Set up the backend:
  ```bash
  python -m venv venv
  source venv/bin/activate  # On Windows use `venv\Scripts\activate`
  pip install -r requirements.txt
  ```
3. Set up the frontend:

```bash
cd frontend
npm install
```

4. Run the application:

```bash
# Start the backend server
python manage.py runserver

# Start the frontend development server
cd frontend
npm start
cd specsolver
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.
Contact

For any questions or feedback, please contact anmarchio.

This README provides an overview of the project, its features, tech stack, architecture, and instructions for getting started. You can customize it further based on your specific needs and preferences.
