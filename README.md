### TOKEN FLOW

A web application that visualizes GPT model token generation and probabilities in real-time. Built with React frontend and Python backend.

## Features

- Interactive text generation from prompts
- Visual token nodes graph with interaction 
- Token probability analysis
- Real-time decoding visualization
- Customizable generation parameters

## Project Structure

```
Gpt2-token-prob/
├──gpt_visualizer/
                  ├──frontend/           # React application
                  └── backend/           # Python Flask API

```

## Getting Started

### Prerequisites

- Node.js and npm
- Python 3.x
- Virtual environment (venv)

### Installation

1. **Backend Setup**
```sh
cd backend
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
pip install -r requirements.txt
```

2. **Frontend Setup**
```sh
cd frontend
npm install
```

### Running the Application

1. Start the backend server:
```sh
cd backend
source venv/bin/activate  # On Windows: venv\Scripts\activate
./run.sh  # On Windows: run.bat
```

2. Start the frontend development server:
```sh
cd frontend
npm start
```

The application will be available at [http://localhost:3000](http://localhost:3000)

## Development

- Frontend is built with React and uses [Material-UI](https://mui.com/) for components
- Backend uses Flask for API endpoints
- Token visualization implemented using React-based graph visualization

## License

This project is licensed under the MIT License.
