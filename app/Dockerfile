FROM node:20.17-bullseye-slim

RUN CI=true npx create-next-app@14.2.6 example

WORKDIR  /example

RUN npm run build

CMD ["npm" "run" "start"]
