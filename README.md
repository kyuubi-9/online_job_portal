# online_job_portal

git clone https://github.com/kyuubi-9/online_job_portal.git

python3 -m venv env

source env/bin/activate

pip install django

pip install -r requirements.txt

python manage.py makemigrations

python manage.py migrate

python manage.py createsuperuser

python manage.py runserver

--after making changes in models.py---

python manage.py makemigrations

python manage.py migrate


--after making any changes---

git checkout -b <branch_name>

git add .

git commit -m "vchdch"

git push -u origin [branchname]


extraa references:

https://github.com/git-guides/git-push

https://www.youtube.com/watch?v=rYwwz1b2Nss
