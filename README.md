# EquityIntel (a fork of SEC Insight) 🏦

## Intro

## Why did we make this? 🤔
As RAG applications look to move increasingly from prototype to production, we thought our developer community would find value in having a complete example of a working real-world RAG application.

SEC Insights works as well locally as it does in the cloud. It also comes with many product features that will be immediately applicable to most RAG applications.

Use this repository as a reference when building out your own RAG application or fork it entirely to start your project off with a solid foundation.

## Product Features 😎
- Chat-based Document Q&A against a pool of documents
- Citation of source data that LLM response was based on
- PDF Viewer with highlighting of citations
- Use of API-based tools ([polygon.io](https://polygon.io/)) for answering quantitative questions
- Token-level streaming of LLM responses via [Server-Sent Events](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events)
- Streaming of Reasoning Steps (Sub-Questions) within Chat

## Development Features 🤓
- Infrastructure-as-code for deploying directly to [Vercel](https://vercel.com/) & [Render](https://render.com/)
- Continuous deployments provided by Vercel & Render.com. Shipping changes is as easy as merging into your `main` branch.
- Production & Preview environments for both Frontend & Backend deployments! Easily try your changes before release.
- Robust local environment setup making use of [LocalStack](https://localstack.cloud/) & [Docker](https://www.docker.com/) compose
- Monitoring & Profiling provided by [Sentry](https://sentry.io/welcome/)
- Load Testing provided by [Loader.io](https://loader.io/)
- Variety of python scripts for REPL-based chat & data management

## Tech Stack ⚒️
- Frontend
    - [React](https://react.dev/) / [Next.js](https://nextjs.org/)
    - [Tailwind CSS](https://tailwindcss.com/)
- Backend
    - [FastAPI](https://fastapi.tiangolo.com/)
    - [Docker](https://www.docker.com/)
    - [SQLAlchemy](https://www.sqlalchemy.org/)
    - [OpenAI](https://openai.com/) (gpt-3.5-turbo + text-embedding-ada-002)
    - [PGVector](https://github.com/pgvector/pgvector)
    - [LlamaIndex 🦙](https://www.llamaindex.ai/)
    - [Opensearch](https://opensearch.org/docs/2.10/)
- Infrastructure
    - [Render.com](https://render.com/)
        - Backend hosting
        - [Postgres 15](https://www.postgresql.org/)
    - [Vercel](https://vercel.com/)
        - Frontend Hosting
    - [AWS](https://aws.amazon.com/)
        - [Cloudfront](https://aws.amazon.com/cloudfront/)
        - [S3](https://aws.amazon.com/s3/)

### System Architecture

## Usage 💻

## Caveats 🧐
- The frontend currently doesn't support Mobile
- Our main goal with this project is to provide a solid foundation for full-stack RAG apps. There is still room for improvement in terms of RAG performance!
