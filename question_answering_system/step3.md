### 3. Start front-end

Click `+` to the right of the `Terminal`, then Select port to view on Host 1 with port 8000, then copy the link for API_URL parameter, for example: https://2886795285-8000-ollie09.environments.katacoda.com.

`docker run -d -p 80:80 -e API_URL=your_url milvusbootcamp/qa-chatbot-client:v1`

For example, my url is https://2886795285-8000-ollie09.environments.katacoda.com:

`docker run -d -p 80:80 -e API_URL=https://2886795285-8000-ollie09.environments.katacoda.com milvusbootcamp/qa-chatbot-client:v1`{{execute}}
