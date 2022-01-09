# ubc_course

Helps you to register you into your desired course(s). Intended for personal use only and use at your own risk.

Note that you need to change course_url at two place, one at where the variable is defined and the other in the function register_course() at browser.execute(). Course url should be the url of the page that has the register section button.

You also need to run login_cwl() before running the infinite loop if you have two factor auth.

In addition, you need to register a new gmail (I don't recommend using your own) and allow less secure apps to access it at https://myaccount.google.com/lesssecureapps?pli=1&rapt=AEjHL4Pqj6ZQ5PQjkl9DqyOMNYsfYQK713pccwhSCvI-FwY1kNLY-MA_gI18Sb21ziMgHYDwpszf2nBnqMtnmvHz31fkjSXH-w for the script to send a email to yourself.
You can also skip this step and comment out all the notify_me()'s.
