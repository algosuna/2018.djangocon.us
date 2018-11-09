---
abstract: Creating well-behaved Python classes shouldn't require boilerplate. In this
  talk we'll see how to easily make classes with proper string representations, comparability,
  iterability, and immutability.
accepted: true
category: talk
date: 2018-10-17 12:20:00 -0500
difficulty: All
layout: session-details
permalink: /talk/easier-classes-python-classes-without/
presenters:
- bio: 'Trey Hunner helps Python and Django teams on-board new developers through
    on-site team training and sends Python exercises to learners every week through
    Python Morsels.

    Trey is a director at the Python Software Foundation, a member of the Django Software
    Foundation, and is heavily involved with his local Python meetup group in San
    Diego.'
  company: Truthful Technology, LLC
  github: ''
  name: Trey Hunner
  photo_url: '/static/img/speakers/trey-hunner.jpg'
  twitter: treyhunner
  website: http://treyhunner.com
published: true
room: 'Salon A-E'
sitemap: true
slides_url: ''
summary: ''
title: 'Easier Classes: Python Classes Without All The Cruft'
track: t0
video_url: 'https://youtu.be/epKegvx_Jws'
---

When bundling up data, sometimes tuples and dictionaries don't quite cut it. Python's classes are powerful tools for data storage and manipulation, but it can take quite a bit of boilerplate code to make a well-behaved Python class. In this talk we're going to discuss how a well-behaved class should work and take a look at a number of helper libraries for creating well-behaved classes.

We'll first see how to make classes with proper string representations, comparability, iterability, and immutability. Then we'll dive into helper tools built-in to the standard library and available in third-party libraries and briefly discuss which of these tools makes sense to use with Django's classes.

We'll look at namedtuple, NamedTuple (not a typo), attrs, and the new Python 3.7 dataclasses.

Most of the libraries discussed in this talk are only available in Python 3, so if you're not using Python 3, hopefully this talk will encourage you to upgrade.
