FROM node:18
WORKDIR /app
RUN npm install -g @modelcontextprotocol/server-memory
EXPOSE 8004
CMD ["sh", "-c", "npx @modelcontextprotocol/server-memory || tail -f /dev/null"]
