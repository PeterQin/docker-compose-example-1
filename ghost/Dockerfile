FROM ghost
ENV NODE_ENV=development
COPY config.development.json /var/lib/ghost/config.development.json
EXPOSE 2368
CMD ["node", "current/index.js"]
