# maps-leafletjs-django
Building Interactive Maps using Leafletjs and Django


<h2>Install python3 and the following packages in ubuntu:</h2>
<ul>
<li>sudo apt-get install build-essential </li>
<li>sudo apt-get install libssl-dev  </li>
<li>sudo apt-get install libffi-dev </li>
<li>sudo apt-get install libpq-dev</li>
</ul>


<h2>Setup virtualenv and needed dependencies</h2>
<ul>
<li>virtualenv venv --python=python3.6</li>
<li>source WaterWatch/venv/bin/activate</li>
<li>pip install django-toolbelt</li>
</ul>

<h2>Create GeoDjango Application Skeleton</h2>
<ul>
<li>cd WaterWatch/</li>
<li>django-admin.py startproject waterwatch <b>.</b></li>
<li>python manage.py startapp waterwatchapp</li>
<li>python manage.py runserver</li>
</ul>

<h3>Open URL: <a href="http://localhost:8000/">http://localhost:8000/ </a> </h3>


