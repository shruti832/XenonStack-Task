# XenonStack Task

#This site consists of login/signup and contact us page which is hosted using flask and the steps to run this is described below :

Steps to Clone:-
1. In your cmd type- **git clone https://github.com/shruti832/XenonStack-Task**
2. In same folder use create a database named **flask_blog** and use the cmd **mysql -u [user] -p [database_name] < flask_blog.sql**
3. Install some python libraries with below commands:
   - pip install Flask
   - pip install smtplib
   - pip install Werkzeug
4.  After these create file in same folder names **vars.json** and copy the below code and update accordingly,
 ```
 {
    "variables":
    {
        "fb_url": "<your_facebook_url>",
        "gh_url": "<your_github_url>",
        "tw_urk": "<your_twiiter_url>",
        "blog_name": "Sharing Point",
        "num_posts": 3,
        "upload_location" : "flask-blog\\static\\assets\\img"
    },
    "sql_conf":
    {
        "mysql_host": "<db_host(for locallly ,localhost)>",
        "mysql_user": "<db_user(usually, root)>",
        "mysql_password": "<db_password>",
        "mysql_db": "flask_blog",
        "mysql_port": db_port(usually 3306/3307/3308)
    },
    "smtp":
    {
        "smtp_server": "smtp.gmail.com",
        "smtp_port": "25",
        "smtp_user": "<your_email>",
        "smtp_pass": "your_password"
    },
    "login":
    {
        "user": "admin",
        "passwd": "<admin_password>"
    }
    
 }
 ```
 5. Run the app using cmd **flask run**
 
 
 
 #This site consists of login/signup and contact us page which is running on flask and the steps to run this is described below :
