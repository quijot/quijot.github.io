.. title: Deploy de un proyecto Django en heroku
.. slug: django-to-heroku
.. date: 2020-06-06 16:00:00 UTC-03:00
.. tags: code, python, django, deploy, heroku
.. category: 
.. link: 
.. description: Cómo deployar un proyecto Django a heroku
.. type: text

Desde hace muchísimo tiempo vengo investigando distintos servicios donde *deployar* aplicaciones Django sencillas. Hay miles de artículos y tutoriales de cómo hacerlo en [heroku](https://www.heroku.com/), el cual creo que es el más popular. Probé además [PythonAnywhere](https://www.pythonanywhere.com/), que también es facilísimo. Pero me decidí por heroku...

Explico el proceso mínimo de cómo hacerlo en **heroku** en este [repo de github](https://github.com/quijot/django_project_heroku_template) que he ido puliendo para que quede super minimalista y básico, a partir del cual luego se puede seguir construyendo.

La idea es contar con un Django project inicial **limpio** al que deba modificar nada (o lo menos posible), **fácilmente actualizable** (a medida que salen nuevas versiones de Django), con **configuración y dependencias mínimas** indispensables para deployar a heroku y rápidamente tenerlo funcionando.

Está basado en esos varios ejemplos que hay dando vueltas pero sobre todo en el [Django Tutorial de MDN](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Deployment) que es espectacular.

Pasos
-----

Los pasos son básicamente:

- clonar el [repo](https://github.com/quijot/django_project_heroku_template) (que viene con todas las `settings` necesarias para deploy en un archivo aparte)
- deploy!

**Con esto, tenemos el Django project completamente funcional, publicado y disponible.**

Con algunos pocos agregados se puede convertirlo en un proyecto GeoDjango, es decir, con capacidades de manejo de geodata o spatial data. Y lo más importante, se pueden agregar apps ;)
