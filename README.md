# maps-leafletjs-django
Building Interactive Maps using Leafletjs and Django


<h2>Install python3 and the following packages in ubuntu:</h2>
<ul>
<li>sudo apt-get install build-essential </li>
<li>sudo apt-get install libssl-dev  </li>
<li>sudo apt-get install libffi-dev </li>
<li>sudo apt-get install libpq-dev</li>
<li>sudo apt-get install gdal-bin</li>
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


<h2>Installing postgres in Ubuntu</h2>
<ul>
<li>sudo sh -c 'echo "deb http://apt.postgresql.org/pub/repos/apt/ bionic-pgdg main" >> /etc/apt/sources.list.d/pgdg.list'</li>
<li>wget --quiet -O - https://www.postgresql.org/media/keys/ACCC4CF8.asc | sudo apt-key add - </li>
<li>sudo apt-get update</li>
<li>sudo apt-get install postgresql-11</li>
</ul>

<p>
    Success. You can now start the database server using:  <br>
<br>
    pg_ctlcluster 11 main start <br>

Ver Cluster Port Status Owner    Data directory              Log file <br>
11  main    5432 down   postgres /var/lib/postgresql/11/main /var/log/postgresql/postgresql-11-main.log <br>
update-alternatives: using /usr/share/postgresql/11/man/man1/postmaster.1.gz to provide /usr/share/man/man1/postmaster.1.gz (postmaster.1.gz) in auto mode <br>

</p>

<h2>Install Ubuntu GIS</h2>
<ul>
    <li>sudo add-apt-repository ppa:ubuntugis/ppa</li>
    <li>sudo apt-get update</li>
</ul>

<h2>Install postgis</h2>
<ul>
    <li>sudo apt install postgis postgresql-11-postgis-3</li>
    <li>sudo apt-get update</li>
</ul>


<h3>postgis log notes</h3>
Success. You can now start the database server using: <br>
<br>
    pg_ctlcluster 12 main start <br>
<br>
Ver Cluster Port Status Owner    Data directory              Log file <br>
12  main    5433 down   postgres /var/lib/postgresql/12/main /var/log/postgresql/postgresql-12-main.log <br>
update-alternatives: using /usr/share/postgresql/12/man/man1/postmaster.1.gz to provide /usr/share/man/man1/postmaster.1.gz (postmaster.1.gz) in auto mode <br>
<br>

<h2>Installing Django Leaflet</h2>
<ul>
<li>source WaterWatch/venv/bin/activate</li>
<li>cd WaterWatch/</li>
<li>pip install django-leaflet</li>
<li>pip install geojson</li>
</ul>

