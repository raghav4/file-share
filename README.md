# Fileshare 📁
### A file Sharing Application built with Nodejs
---
## Quick Start
```bash
# Install dependencies
npm install
# Serve on localhost
npm start
```

### Disclaimer
- Make Sure Node is installed on your machine.
- In order to use the application you will need to create account on [cloudinary](http://cloudinary.com) for uploading the files and [sendgrid](https://sendgrid.com) for sending emails. (**API KEYS**)
- You can share the maximum file of size 100 MB, in order to share files greater than 100 MB change the `upload` to `upload_large` in cloudinary. However, the response time increases if any larger file is uploaded and thus the application may give `502` error. This application supports file smaller in size and does not support some of the extensions. You can refer cloudinary api for more. 

### License

This project is licensed under the MIT License
