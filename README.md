# Coding Blog
<b>About</b>
<p>I have created Coding blog website using flask framework. In this website one can add,delete or change the blog post. I have used flask,python,bootstrap,jinja,SQLAlchemy to complete this website. If you want to use this code simply follow this steps.</p>
<b>You have to know before you start</b><br><br>
  <b>1. SQLAlchemy</b>
    <p>This part of the project is very simple.The login routes reference this table. Only very basic pieces of SQLAlchemy are used, so it should all be pretty easy to find and edit for your project.</p><br>

  <b>2.Flask-Login</b>
  <p>Flask login can be done from dashboard.After login you can add new post or you can delete and edit in existing post.</p><br>
  
  <b>3.Contact</b>
  <p>In this site if anyone try to contact you then that message will save in database as well as come in my email. If you want to add this feature then you have to enable "allow less secure apps" in email settings.</p><br>
  
<b>Steps to run</b>
<ol>
  <li>Clone the repository on your device.</li>
  <li>pip install flask</li>
  <li>pip install SQLAlchemy</li>
  <li>You have to add your email address in config.json file in gmail-user parameter.</li>
  <li>You have to add your email password in config.json file in gmail-password parameter.</li>
  <li>You have to add username that you want to set for your website login in config.json file in admin_user parameter.</li>
  <li>You have to add password that you want to set for your website login in config.json file in admin_password parameter.</li>
  <li>Open Xampp on your device.</li>
  <li>Make new database in phpmyadmin.</li>
  <li>Create two new tables Posts and Contact.</li>
  <li>You have to add sno,name,email,phone_num,mes,date in Contact table.</li>
  <li>You have to add sno,title,slug,content,tagline,date,img_file in Posts table.</li>
  <li>Run the Main.py file.</li>
  <li>Open your website from link that you got after running main.py file.</li>
</ol>


