
## Questions

<details>
<summary>Can you please briefly explain Django's system architecture | <i>✎ Full text answer</i></summary>

</details>

<details>
<summary>Which ones of the following commands will create files in your filesystem? | <i>Multi choice answer</i></summary>

- [x] ./manage.py makemigrations
- [ ] ./manage.py migrate
- [ ] ./manage.py sqlmigrate</details>

<details>
<summary>Can you please describe the pros & cons of Django's ORM? | <i>✎ Full text answer</i></summary>

</details>

<details>
<summary>Does Django support NoSQL? If so, how? | <i>✎ Full text answer</i></summary>

</details>

<details>
<summary>What is CRSF protection and how it's implemented in Django? | <i>✎ Full text answer</i></summary>

</details>

<details>
<summary>Which one of the following code snipets will trigger a post_save signal? | <i>Multi choice answer</i></summary>

- [ ] Code snippet no. 1
- [ ] Code snippet no. 2
- [ ] Both
- [ ] None- Code snippet no. 1
~~~python
User.objects.filter(pk=10).update(name="John")
~~~
- Code snippet no. 2
~~~python
User.objects.get(pk=10).save(name="John")
~~~
</details>

<details>
<summary>What is the typical usage of Django's middleware? | <i>Multi choice answer</i></summary>

- [x] Cross-Site request forgery protection
- [ ] Rendering a template
- [x] Session management
- [x] Authentication handling
- [ ] Querying database</details>

<details>
<summary>What is the typical structure of Django's application? | <i>✎ Full text answer</i></summary>

</details>

<details>
<summary>Where does Django store information about SQL migrations? | <i>Multi choice answer</i></summary>

- [x] Filesystem
- [x] Database
- [ ] Cache</details>

<details>
<summary>Why is it recommended to start a project with a custom user model? | <i>✎ Full text answer</i></summary>

</details>

<details>
<summary>What does the following code do? | <i>Single choice answer</i></summary>

- [ ] Loads all buildings including offices to all_buildings variable
- [x] Throws `AttributeError` exception
~~~python3
from django.db import models

class OfficeBuildingsManager(models.Manager):
    def get_queryset(self):
        return super().get_queryset().filter(building_type='office')

class Building(models.Model):
    offices = OfficeBuildingsManager()

all_buildings = Building.objects.all()
~~~
</details>

<details>
<summary>How to structure your Django app so that it is re-usable in other Django projects? | <i>✎ Full text answer</i></summary>

</details>

<details>
<summary>What is the possible exception that can be thrown by this code? | <i>Multi choice answer</i></summary>

- [x] Company.DoesNotExist
- [ ] IndexError
- [ ] both of these exceptions
- [ ] none of these exceptions~~~python
Company.objects.order_by('created_at')[0:1].get()
~~~
</details>

<details>
<summary>How is Django's admin interface customizable? | <i>✎ Full text answer</i></summary>

</details>

<details>
<summary>What is a Meta class on Django's models and what do we use it for? | <i>✎ Full text answer</i></summary>

</details>

<details>
<summary>What is Django REST framework and how does it work? | <i>✎ Full text answer</i></summary>

</details>
