# URL Shortening Service Full-Stack

## Description

<p align="justify"> This is a full-stack URL shortening service that allows users to shorten long URLs, create custom aliases, and track analytics (clicks, unique visitors, and geographic data). It’s designed for high performance with a static frontend and a scalable backend, deployed entirely on AWS. </p>

## Stack

<div align="center"> <img src="https://skillicons.dev/icons?i=react,astro,nestjs,graphql,tailwind,aws,postgres,githubactions" alt="Tech Stack" /> </div>

**Frontend:**

- Astro – Static site generator for modern web apps.
- React.js – Library for building interactive UIs.
- Tailwind CSS – Utility-first CSS framework for rapid UI development.

**Backend:**

- Node.js – Runtime environment for executing JavaScript on the server.
- Nest.js – A progressive Node.js framework for building scalable server-side applications.
- GraphQL – API query language for requesting only the data needed.

**Database:**
- PostgreSQL (AWS RDS) – Relational database for storing URLs and click data.

**Cloud Infrastructure:**
AWS (S3, CloudFront, RDS, Lambda, ECR) – Cloud services for hosting and deployment.

## Features

- 🌐 **URL Shortening** – Generate short URLs with custom aliases.
- 🚀 **Cloud Native** – Deployed entirely on AWS for high scalability.

## Getting Started

### Prerequisites

- Node Version Manager (NVM)
Install NVM from [here](https://github.com/nvm-sh/nvm?tab=readme-ov-file#installing-and-updating)

- PNPM (Node Package Manager):
Install PNPM globally using NPM:
```bash

npm install -g pnpm

```

### Setup Instructions

1. Clone the repository:

```bash

git clone <repo-url>
cd <repo-name>

```

2. Install Node.js using NVM:

```bash

nvm install
nvm use

```

3. Enable Corepack and install dependencies:

```bash

corepack enable
corepack install
pnpm install

```

4. Start the development server:

```bash

pnpm run dev

```

## Contributing

We welcome contributions! Feel free to open issues, suggest improvements, or submit pull requests.

## Stay in touch

- Author - [Novin Noori](linkedin.com/in/novin-noori)
- Website - [novinnoori.com](https://novinnoori.com)
