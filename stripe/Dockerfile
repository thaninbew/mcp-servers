FROM node:18
WORKDIR /app
RUN npm install -g @modelcontextprotocol/server-stripe
ENV STRIPE_API_KEY=your-stripe-api-key
EXPOSE 8001
CMD ["npx", "@modelcontextprotocol/server-stripe"]
