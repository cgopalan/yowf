# yowf
Your Own Web Framework

This is a minimal python framework, which enables you to understand the guts behind Python web frameworks like Django and Flask.

To see it work, run the `example_app.py` file using a web server. I used twisted (`pip install twisted`):

`PYTHONPATH=. YOWF_APP=example_app twist web --wsgi yowf.application`

From the [fantastic tutorial](https://github.com/jacobian/pycon2017) by Jacob Kaplan-Moss
