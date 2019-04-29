# Introduction
First, create the Flask app. This is the easy part! There’s a QuickStart Guide to working with Flask (http://flask.pocoo.org/docs/quickstart/). Deploy the site remotely using a combination of Absible playbooks and Hashicorp Packer.  

# specs
```
- OS: Debian Jessie 64-bit
- App Server: Gunicorn/Nginx (Native or Docker)
- Python: 2.7
- Flask: 0.12
```

# Tasks
```
1. Launch the EC2 server (EG: using aws cli utilities)
2. Bootstrap the server
3. Run the application
```
