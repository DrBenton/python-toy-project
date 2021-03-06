# Python toy project: a weather API

[![Build Status](https://travis-ci.org/DrBenton/python-toy-project.svg?branch=master)](https://travis-ci.org/DrBenton/python-toy-project)


![Python logo](https://i2.wp.com/www.genohm.com/wp-content/uploads/2017/03/logo_python.png?resize=201%2C200)
![Django logo](http://www.tivix.com/uploads/images/django.width-200.png)
![Flask logo](https://iotbytes.files.wordpress.com/2016/08/flask.png?w=150&h=150)
![aiohttp logo](http://aiohttp.readthedocs.io/en/stable/_static/aiohttp-icon-128x128.png)


Not that I'm especially interested in weather :-), but the goal was to play with the following concepts in Python:
 * Dependencies management via [Pipenv](https://docs.pipenv.org/)
 * Unit tests with [pytest](https://docs.pytest.org/en/latest/)
 * Parallel operations via [asyncio](https://docs.python.org/3/library/asyncio.html) and [aiohttp](http://aiohttp.readthedocs.io/en/stable/index.html)
 * "Domain" and "Web API" logic handled separately, in a _[DDD](https://en.wikipedia.org/wiki/Domain-driven_design) way_
 * Dependency injection, via [scute](https://github.com/DrBenton/scute), a Python clone of PHP's [Pimple](https://pimple.symfony.com/)
 * Minimalist JSON API with [Flask](http://flask.pocoo.org/)  
   _(could be interesting to start with something even more minimalistic like [Roll](http://roll.readthedocs.io/en/latest/), as I don't need Jinja for a JSON API)_
 * "Closer to real world" JSON API with [Django](https://docs.djangoproject.com)  
   The more I work with Django, the more I realise that Symfony basically copied lots of Django features: templating system, Forms, etc :-)

Even if it's a dummy and very small project I have been able to apply most of the best practices I use for my usual domain of expertise ([Symfony](http://symfony.com/what-is-symfony)): DDD-like development, dependency injection, Makefile, Docker Compose...

I really enjoy Python! Clear syntax, rich stdlib, functions named arguments, type hinting, coroutines... Great stuff! :-)
