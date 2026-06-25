## Logging Middleware


## Installation

Clone the repository:

```bash
git clone <repository-url>
cd <project-folder>
```

Install dependencies:

```bash
npm install
```

## Configuration

Create a `.env` file in the project root:

```env
VITE_CLIENT_ID=your_client_id
VITE_CLIENT_SECRET=your_client_secret
```

## Running the Project

Start the development server:

```bash
npm run dev
```

For production build:

```bash
npm run build
```

## Logging Middleware Usage

Example:

```javascript
import logger from "./middleware/logger";

logger.info("Application started");

logger.error("Something went wrong");
```

