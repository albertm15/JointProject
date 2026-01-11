# Joint project - Hotel las palmeras:
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![Closed Issues][closedIssues-shield]][closedIssues-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Comando per Git
* Create a branch (manualment desde GitHub)
* git pull (actualitzar tot el repositori)
* git checkout name_of_branch (canviar de rama)
* git checkout (comprobar en quina rama estem treballant)
* exemple: git checkout develop-branch
* treballar en els arxius
* git add -A
* git commit -m "Missatge Commit"
* git push

### Built With
* Python
* FrameWork - Django

<p align="right">(<a href="#readme-top">back to top</a>)</p>

...
### Built With
* Python
* FrameWork - Django

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Security Configuration Note
> **⚠️ Important:** The `SECRET_KEY` in `djangoProject/settings.py` is intentionally exposed in this repository to facilitate the setup and evaluation of the project in a development environment.
>
> **For Production:** If deploying this application to a production environment, you must:
> 1.  Hide the `SECRET_KEY` using environment variables.
> 2.  Set `DEBUG = False`.
> 3.  Ensure `ALLOWED_HOSTS` is properly configured.

### For use our application

1. Clone the repo
...

### To use our application

1. Clone the repo
   ```sh
   git clone https://github.com/arnaums02/Joint-Project---Grup-B.git
   ```

2. Be sure the migrations are generated correctly
   ```python
   python manage.py makemigrations
   ```

3. Apply the migrations
   ```python
   python manage.py migrate
   ```
4. Run the application
   ```python
   python manage.py runserver
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<p align="right">(<a href="#readme-top">back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/arnaums02/Joint-Project---Grup-B.svg?style=for-the-badge
[contributors-url]: https://github.com/arnaums02/Joint-Project---Grup-B/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/arnaums02/Joint-Project---Grup-B.svg?style=for-the-badge
[forks-url]: https://github.com/arnaums02/Joint-Project---Grup-B/network/members
[stars-shield]: https://img.shields.io/github/stars/arnaums02/Joint-Project---Grup-B.svg?style=for-the-badge
[stars-url]: https://github.com/arnaums02/Joint-Project---Grup-B/stargazers
[issues-shield]: https://img.shields.io/github/issues/arnaums02/Joint-Project---Grup-B.svg?style=for-the-badge
[issues-url]: https://github.com/arnaums02/Joint-Project---Grup-B/issues
[closedIssues-shield]: https://img.shields.io/badge/Closed%20Issues-85-green?style=for-the-badge
[closedIssues-url]: https://github.com/arnaums02/Joint-Project---Grup-B/issues?q=is%3Aissue+is%3Aclosed

