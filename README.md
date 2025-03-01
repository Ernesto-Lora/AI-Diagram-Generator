We utilize LlamaIndex's Pydantic Program mode for generating structured outputs. Additionally, we implement partial object parsing to transmit intermediate objects, which are validated against Pydantic models before being sent to the frontend.

Click the thumbnail above to watch the full video tutorial.

## Getting Started

Begin by cloning the repository:

```bash
git clone https://github.com/Ernesto-Lora/AI-Diagram-Generator.git
cd ai-diagram-generator
```

## Launching the Backend

Navigate to the `backend` directory:

```bash
cd backend
```

### Create `.env` from the example file

```bash
cp .env.example .env
```

### Configure the OpenAI API key in `.env`

```bash
OPENAI_API_KEY=****
```

### Install dependencies

```bash
poetry install
```

### Run the backend server

```bash
poetry run python main.py
```

## Launching the Frontend

Navigate to the `frontend` directory:

```bash
cd frontend
```

### Create `.env` from the example file

```bash
cp .env.example .env
```

### Install dependencies

```bash
npm i
```

### Run the frontend server

```bash
npm run dev
```
