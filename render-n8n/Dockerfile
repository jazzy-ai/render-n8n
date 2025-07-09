From n8nio/n8n:latest

#Set basic authentication (change these securely in Render ENV instead)
ENV N8N_BASIC_AUTH_ACTIVE-true
ENV N8N_BASIC_AUTH_USER=admin
ENV N8N_BASIC_AUTH_PASSWORD=securepassword

#optional timezone setting (adjust as needed)
ENV TZ=Euope/Berlin

#Default port
EXPOSE5678

#Use /home/node as working directiory
WORKDIR /home/node

#Run n8n
CMD ["n8n"]




