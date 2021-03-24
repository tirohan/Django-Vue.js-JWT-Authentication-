# Django-Vue.js-JWT-Authentication-

Workflow
###################
Django
###################
Setup
#####
    1. Install venv Django
    2. Create APP & Register in settings.py
    3. pip Install djangorestframework
    4. Make model
    5. createsuperadmin
    6. admin.py
    7. Add data
    8. Create serializers.py
    9. Create view
    10. Config urls with /post
    11. Test in postman
#####
Cross-Origin Resource Sharing (CORS) 
#####
    13. pip install django-cors-headers (https://pypi.org/project/django-cors-...​)
    14. Add cors to settings apps installed and middleware then whitelist


###################
Vue JS
###################
Create new project (CLI)
=======
    1. First we remove the the helloworld components
=======
Configure routes
=======
    2. Configure the App.vue file
    3. Add a routes.js file
    4. Configure/Connect in main.js
    5. Add new file routes and configure
    6. Configure main.js with router
    7. Add views folder and add Posts.vue
    8. Import vue router npm install --save vue-router
    9. Page should be working now - lets test it
=====
Build Navbar & Bootstrap
=====
    10. Build Navbar file
    11. Add Navbar to Posts.vue
    12. Install Bootstrap npm install bootstrap
    13. Add Bootstrap to main.js
======
Axios
======
    14. Install axios npm install --save axios
    15. Create axios instance axios-api.js
    16. Configure Posts.vue - output data (remember to turn of authentication in Django view)
    17. Test new configuration
    
    
    
    
In the second part........................

Django
=======
 Configure JWT
 Create new Token with postman
 Test authentication with postman
 
 Vue js
=======
1.Create new files Logout.vue Login.vue Store.vue
2.Configure router
3.Build login page
4.Create store using Vuex //npm install vuex
5.Build Post page access data from API
6.Add authorisation to pages with redirect
7.Build logout page
8.Example of displaying links if only logged in
9.Add Idle feature //npm install idle-vue
