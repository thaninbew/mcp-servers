FROM node:18
WORKDIR /app
RUN npm install -g @modelcontextprotocol/server-brave-search
ENV BRAVE_API_KEY=your-brave-api-key
EXPOSE 8000
CMD ["npx", "@modelcontextprotocol/server-brave-search"]
