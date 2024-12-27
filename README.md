## Installation

### Clone this Project

Run the following commands to clone the repository and navigate into the project directory:

```bash
  git clone https://github.com/HGiang15/api_be_job.git
  cd api_be_job
```

### Install Dependencies

Install the required Node.js modules:

```bash
  npm install
```

Install requirements.txt:

```bash
  pip install -r requirements.txt
```

## Run the Project

Start the server with the following command:

```bash
  node --watch server.js
```

## Testing the API

Use the following endpoint to test the API:

### Endpoint:

```
  http://localhost:3000/api/jobs/search
```

### Body Request Example:

```json
{
    "keyword": "java backend"
}
```

Replace the value of `"keyword"` with your desired search term to customize the job search.
