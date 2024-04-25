# Amenitiz Front-end Technical Challange 🚀
Chess Wikipedia is wiki of Chess Grandmasters as defined by Chess.com.

## Pre Requisite
- Node Version 20.11.1

## Installations

To install and set node version using nvm if not installed already
```bash
nvm install 20.11.1
nvm use 20.11.1
```

To install all packages and their dependencies
```bash
npm install
```

To start the server please run
```bash
npm run dev
```

The server will be running at
```bash
http://localhost:5173/
```

## Shortcomings
**Limited Pagination**: Presently, the API returns all data at once, which may lead to performance issues when dealing with a large dataset. Pagination is not implemented, resulting in the retrieval of all data in bulk. To enhance performance and optimize response time, it is recommended to implement pagination. This would involve fetching only the necessary data in smaller, manageable portions as needed.
