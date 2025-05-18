# Assignment_12_RestApi
# @ model.py:
	* In this class we have created title, content, publishby, created on , update on and created by fields
	* and it return title to register in the admin post
	
	
# @admin.py:
	* Here we registe the models to the admin 
	

# @permission.py	
	* It contain the basic permission which all user to give read function only

 
# @filter.py:
	* It contain post filter class which is used to filter the post in date range
	
# @Serializers.py:
	* It contain the PostSerializer class which is used to display the user name who is created the post

# @view.py:
	* It Contain the PostView class which provide the permission such as IsAuthenticted and IsPostProcessor
	* It also used for filtering
	* Here get_queryset() method is used to view the post of individual user created by them
	
# @setting.py	
	* Here we have to provide the rest_framework,django_filters and blog_app inside the INSTALLED_APP
	* By using REST_FRAMEWORK we can do pagination
	
# @urls.py:
	* we have to provide the router register and provide the api-auth in the urlpatterns
