# LittleLemon
### Django Routes
The Django framework adopts an MVT approach. The model is the data layer of the application. 
The view layer is responsible for processing the request and returning the response. The template is the presentation layer. 
# URL dispatcher 
When the server receives a request in the form of a client URL, the dispatcher matches its pattern with the patterns available 
in the urls.py and routes the flow of the application toward its associated view. 
example: 
The path() function matches a URL endpoint string with the function you want to be called:
from django.contrib import admin
from django.urls import path
 
urlpatterns = [
    path('admin/', admin.site.urls),
]

