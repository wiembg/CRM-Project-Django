# CRM-Django_project
Customer relationship management (CRM) app built with Django framework 

- configuring :static_files /media_files
- -creating adminpanel and custimize it :
- databaseModel relationships (SQL) :relationnel 
- Database Model Queries #order = Order.objects.get(id=pk)/all()/exlude()/get(name=")
- rendering data to templates :(crsf token pass data securely(every action related to form)  and won’t submit the data without it  ){{context}}
- dynamics urls #  passing pk+request {% url ="namepage"%}
- CRUD:
- Auth:from django.contrib.auth/
- userRolePermissions#decorator.py
- user profile settings account   
- reset password views #uth_views 
- db: psycopg2 configre settings
- signals: senders and receivers,extended User-> profile,signals allow certain senders to notify a set of receivers that some action has taken place so allow, when user is created , profile is created attached to username,so signals are pieces of code which contain information about what is happening. A dispatcher is used to sending the signals and listen for those signals.
