## Prerequisites 

1) Install the necessary dependencies (Both in the fronend & backend):

```bash
npm install
```
2) Create a new PostgreSQL database. Then add an environment file in the root of the backend project:

```dotenv
/* Insert your credentials */

POSTGRES_HOST=
POSTGRES_PORT=
POSTGRES_USER=
POSTGRES_PASSWORD=
POSTGRES_DATABASE=
```

## Usage

Run development server

Frontend:

```bash
npm run dev
```

Backend:

```bash
npm run start:dev
```
