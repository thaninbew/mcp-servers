FROM node:18
WORKDIR /app
RUN npm install -g @modelcontextprotocol/server-supabase
ENV SUPABASE_URL=your-supabase-url
ENV SUPABASE_KEY=your-supabase-key
EXPOSE 8002
CMD ["npx", "@modelcontextprotocol/server-supabase"]
