FROM denoland/deno:latest

WORKDIR /app

COPY . .

RUN deno cache main.ts

CMD ["run", "--allow-all", "main.ts"]