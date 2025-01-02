## 🌟 Introduction

This is the frontend repo for the phone web agent. This uses Retell AI services for the AI voice agent platform. The backend repo is [here](https://github.com/jjvillegas16/salon-backend)

## Prerequisite

Ensure you have the following in your local environment:

1. NodeJS v22.12.0

## Local dev setup

1. Clone the repo

```bash
git clone <repository-url>
cd <repository-directory>
```

2. Add .env vars. You can use .env.template as reference for the needed variables

3. Install the dependencies.

```bash
npm install
```

4. Run the project

```bash
npm run dev
```

## Limitations:

1. Please use google chrome for easier use. there's an webrtc error in firefox that needs additional config to be fixed when running locally (https://stackoverflow.com/questions/72862092/webrtc-ice-failed-in-firefox-but-working-in-ms-edge)
