FROM node:18
WORKDIR /app
RUN npm install -g @modelcontextprotocol/server-github
EXPOSE 8002
CMD ["sh", "-c", "npx @modelcontextprotocol/server-github || tail -f /dev/null"]
