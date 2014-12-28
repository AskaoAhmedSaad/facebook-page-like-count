facebook-page-like-count-using-django-template-tag
==================================================

Welcome to the facebook-page-like-count-using-django-template-tag wiki!

## template-tag path:-
`your_app/`

    `templatetags/`

       `__init__.py`

       `fb_like_count.py`

## in your template you will load fb_like_count templete tag:-
`{% load fb_like_count %}`

## and use it as the following:-
`{% like_count page_name not_formatted|formatted %}`

it takes 2 parameters:

1- pages_name as 'GitHub'

2- type of like count:

       not_formatted as '47600'

       formatted as '47.6K'


## example:-
`{% load fb_like_count %}`

`{% like_count GitHub not_formatted %}`
