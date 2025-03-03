FROM node:18
WORKDIR /app
RUN npm install -g @modelcontextprotocol/server-brave-search
EXPOSE 8000
CMD ["sh", "-c", "npx @modelcontextprotocol/server-brave-search || tail -f /dev/null"]

