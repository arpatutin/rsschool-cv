# CV
#### Mini-self-description
My name is **Arseniy Patutin**, I'm *12* years old


I'm intrested in _Fullstack-development_, _Game-development_ and in _programming for Informatic olympiads_.

I would like to study this, because I want to go to ITMO University when I'll finish school.


I can work with _Python (django and Jinja)_ and with _HTML and CSS_.


#### Courses I completed


I completed **[Mail.Ru's "Web-technologies" course on Stepik](https://stepik.org/course/154)**, **[Mail.Ru's "Web-projects Safety" course](https://stepik.org/course/127)** and read some books about _HTML and CSS_.


#### Other information


I have verified **A2** English-level, but I am continuing to learn this language.


You can write me to _**Telegram** @arpatutin_, to _**Discord** arpat70#8757_ and to [_**VK**_](https://vk.com/id535585567).


#### My code examples
```python
# Some django views code that I wrote on Innopolis University's marathone
from newsapp.models import Article
from django.shortcuts import render

def index(request):
    return render(request, 'index.html')

def article_1(request):
    return render(request, 'single.html')

def home(request):
    articles = Article.objects.all()
    return render(request, 'index.html', {'all': articles})
```


```html
<!--Some HTML I wrote and integrated with django after first week-->
<!DOCTYPE html>
<html>
<head>
    <title>Test Site</title>
    <link rel='stylesheet' href={% static "bootstrap.css" %}>
    <link rel='stylesheet' href={% static "style.css" %}>
</head>
<body>
    <header>
        <a>Test Site</a>
        <il class='headers'>
            <li class='headers'><a>Contacts</a></li>
            <li class='headers'><a>About</a></li>
        </il>
    </header>
    <main>
      
    </main>
    <footer>
        
    </footer>
    
</body>
</html>
```

