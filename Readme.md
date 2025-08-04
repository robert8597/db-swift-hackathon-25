# Swift Digital FX Service

*Version 0.0.1*

## Developer Requirements:

- Compliant OpenJDK 17
- Maven 3.9.9
- Node.js

This is the repository for all SWIFT Hackathon 2025 related items:

1. Orchestration Microservice (all further connections are mocked)
2. UI
3. Documentation




## How to run UI
1. Navigate to the `react-ui` directory.
2. Run the following command to start the UI:
   ```bash
   npm install
   npm install react-syntax-highlighter
   npm run dev
   ```

## How to run backend
1. mvn clean install
2. Adjust applicaion-local.yaml file:
   dfx.storage.path: ".../dfx-messages/"
3. Start DfxServiceApplication with local profile setting
   VM options: -Dspring.profiles.active=local
