# My stack / my tools

<!-- vscode-markdown-toc -->
* [Backend](#Backend)
	* [Django](#Django)
	* [FastAPI](#FastAPI)
	* [Flask](#Flask)
	* [Misc](#Misc)
	* [Testing](#Testing)
	* [Tools](#Tools)
* [Devops](#Devops)
	* [Cloud](#Cloud)
	* [CI/CD](#CICD)
	* [Middlewares](#Middlewares)
* [Frontend](#Frontend)
	* [Vue.js](#Vue.js)
	* [TailwindCSS](#TailwindCSS)
	* [AlpineJS](#AlpineJS)

<!-- vscode-markdown-toc-config
	numbering=false
	autoSave=true
	/vscode-markdown-toc-config -->
<!-- /vscode-markdown-toc -->


## <a name='Backend'></a>Backend

### <a name='Django'></a>Django

- [django-airports](https://github.com/bashu/django-airports) - like django-cities, but django-airports
- [django-allauth](https://django-allauth.readthedocs.io/en/latest/installation.html) - social auth
- [django-anymail](https://github.com/anymail/django-anymail) - ESPs integration
- [django-axes](https://github.com/jazzband/django-axes) - keep track of login attempts and block brute-force attacks
- [django-celery-results](https://github.com/celery/django-celery-results) - celery results using django ORM backend
- [django-cities-light](https://github.com/yourlabs/django-cities-light) - fetch data from [Geonames](http://www.geonames.org/) and prepare database
- [django-constance](https://github.com/jazzband/django-constance) - store dynamic settings in pluggable backends
- [django-constance](https://github.com/jazzband/django-constance) - store settings in django backend
- [django-cors-headers](https://github.com/adamchainz/django-cors-headers) - adding CORS headers to response
- [django-countries](https://github.com/SmileyChris/django-countries) - country choices for forms, flag static icons, country model field
- [django-debug-toolbar](https://github.com/jazzband/django-debug-toolbar)
- [django-elasticsearch-dsl](https://github.com/django-es/django-elasticsearch-dsl) - indexing of django models in [Elasticsearch](https://www.elastic.co/)
- [django-environ](https://django-environ.readthedocs.io/en/latest/) - configure your django with ease
- [django-extensions](https://github.com/django-extensions/django-extensions) - collection of custom extensions
- [django-flags](https://cfpb.github.io/django-flags/) - feature flags
- [django-fsm-admin-lite](https://github.com/etchegom/django-fsm-admin-lite) - my "lite" implementation of django-fsm-admin
- [django-fsm-admin](https://github.com/gadventures/django-fsm-admin) - integrate django-fsm into django admin
- [django-fsm-log](https://github.com/jazzband/django-fsm-log) - log django-fsm ops
- [django-fsm](https://github.com/viewflow/django-fsm) - friendly finite state machine
- [django-hijack](https://github.com/django-hijack/django-hijack) - admins can log in and work on behalf of other users without having to know their credentials
- [django-lifecyle](https://github.com/rsinger86/django-lifecycle/) - lifecycle hooks to your Django models
- [django-linear-migrations](https://github.com/adamchainz/django-linear-migrations) - Ensure your migration history is linear
- [django-manifest-loader](https://github.com/rykener/django-manifest-loader) - read manifest created by [webpack](https://www.npmjs.com/package/webpack-manifest-plugin)
- [django-money](https://github.com/django-money/django-money) - money fields in models and forms
- [django-mptt](https://django-mptt.readthedocs.io/en/latest/) - tree structure models
- [django-multisite](https://github.com/ecometrica/django-multisite)
- [django-ninja-extra](https://github.com/eadwinCode/django-ninja-extra)
- [django-ninja-jwt](https://github.com/eadwinCode/django-ninja-jwt)
- [django-ninja](https://django-ninja.rest-framework.com/) - REST API based on pydantic like FastAPI, an alternative to DRF
- [django-phonenumber-field](https://github.com/stefanfoulis/django-phonenumber-field) - phone number field validation
- [django-redis](https://github.com/jazzband/django-redis) - redis cache backend
- [django-service-objects](https://django-service-objects.readthedocs.io/en/latest/) - service base class based on forms
- [django-storages](https://django-storages.readthedocs.io/en/latest/) - collection of custom storage backends, including S3
- [django-tailwind](https://github.com/timonweb/django-tailwind) - Django + TailwindCSS
- [django-templated-email](https://github.com/vintasoftware/django-templated-email) - templated email
- [django-typed-models](https://github.com/craigds/django-typed-models) - extra type of model inheritance
- [django-user-agents](https://github.com/selwin/django-user_agents) - identification of visitor's browser
- [djantic](https://github.com/jordaneremieff/djantic) - Pydantic model support for django
- [djoser](https://github.com/sunscrapers/djoser) - set of auth related views for DRF
- [drf-camelcase](https://github.com/vbabiy/djangorestframework-camel-case) - camelcase JSON support for DRF
- [drf-friendly-errors](https://github.com/FutureMind/drf-friendly-errors) - improve DRF error display
- [drf-simplejwt](https://github.com/jazzband/djangorestframework-simplejwt) - JWT authentication plugin for DRF
- [drf-spectacular](https://github.com/tfranzel/drf-spectacular) - an OpenAPI 3.0 schema generation for DRF
- [drf-yasg](https://github.com/axnsan12/drf-yasg) - swagger generator
- [drf](https://www.django-rest-framework.org/) - django rest framework
- [pytest-django](https://pytest-django.readthedocs.io/en/latest/) - tools for testing django with pytest

[2021-top-100-django-packages](https://blog.devgenius.io/2021-top-100-django-packages-list-during-the-year-92fef0ba79c9?gi=f683fb71ca8e)


### <a name='FastAPI'></a>FastAPI

- [fastapi-admin](https://github.com/fastapi-admin/fastapi-admin) - admin dashboard
- [fastapi-cache](https://github.com/long2ice/fastapi-cache) - cache fastapi response against multiple backends
- [fastapi-camelcase](https://nf1s.github.io/fastapi-camelcase) - camelizing request and response bodies
- [fastapi-mail](https://github.com/sabuhish/fastapi-mail) - simple lightweight mail system
- [sqlmodel](https://sqlmodel.tiangolo.com/) - interacting with SQL databases with python objects

### <a name='Flask'></a>Flask

- [Flask-Admin](https://github.com/flask-admin/flask-admin) - admin interface
- [Flask-Assets](https://github.com/miracle2k/webassets) - integrate webassets into your Flask application
- [Flask-Bcrypt](https://github.com/maxcountryman/flask-bcrypt) - password hashing
- [Flask-Caching](https://github.com/pallets-eco/flask-caching) - cache support
- [Flask-DebugToolbar](https://flask-debugtoolbar.readthedocs.io/en/latest/) - debug toolbar
- [Flask-Login](https://flask-login.readthedocs.io/en/latest/) - user session management
- [Flask-Marshmallow](https://flask-marshmallow.readthedocs.io/en/latest/) - serialization library
- [Flask-Migrate](https://github.com/miguelgrinberg/Flask-Migrate) - db migration (sqlalchemy + alembic)
- [Flask-nplusone](https://github.com/jmcarp/nplusone#flask-sqlalchemy) - detecting the n+1 queries problems
- [Flask-Principal](https://github.com/mattupstate/flask-principal) - identity management for Flask applications
- [Flask-Shell-IPython](https://github.com/ei-grad/flask-shell-ipython) - flask shell with ipython
- [Flask-SQLAlchemy](https://flask-sqlalchemy.palletsprojects.com/en/3.0.x/) - SQLAlchemy support
- [Flask-WTF](https://github.com/wtforms/flask-wtf/) - WTForms integration

### <a name='Misc'></a>Misc

- [Celery](https://github.com/celery/celery) - task queue
- [Google Tink](https://github.com/tink-crypto/tink-py) - crypto library
- [Gunicorn](https://gunicorn.org/) - WSGI web server
- [psycopg2](https://github.com/psycopg/psycopg2) - PostgreSQL database adapter python
- [SQLAlchemy-utils](https://github.com/kvesteri/sqlalchemy-utils) - various utils for sqlalchemy
- [SQLAlchemy](https://www.sqlalchemy.org/) - python sql toolkit & ORM
- [Uvicorn](https://www.uvicorn.org/) - ASGI web server 


### <a name='Testing'></a>Testing

- [factory_boy](https://factoryboy.readthedocs.io/en/stable/) - test fixtures
- [freezegun](https://github.com/spulec/freezegun) - mocking the datetime module in tests
- [pytest](https://docs.pytest.org/en/6.2.x/) - test framework
- [pytest-cov](https://github.com/pytest-dev/pytest-cov) - produce coverage reports during tests
- [pytest-factoryboy](https://pytest-factoryboy.readthedocs.io/) - combine factory approach to the test setup with the dependency injection, heart of the pytest fixtures
- [pytest-instafail](https://github.com/pytest-dev/pytest-instafail) - show failures and errors instantly instead of waiting until the end of test session
- [pytest-xdist](https://github.com/pytest-dev/pytest-xdist) - speed up test execution with parallel processing

### <a name='Tools'></a>Tools

- [black](https://github.com/psf/black)
- [coverage](https://coverage.readthedocs.io/en/7.3.1/)
- [isort](https://github.com/PyCQA/isort)
- [poetry](https://python-poetry.org/)
- [precommit hooks](https://pre-commit.com/hooks.html)
- [ruff](https://github.com/astral-sh/ruff)

---

## <a name='Devops'></a>Devops

### <a name='Cloud'></a>Cloud

- [Terraform](https://www.terraform.io/) - automate infra on any cloud
- [Consul](https://www.consul.io/) - service mesh manager
- [GCP python](https://github.com/googleapis/google-cloud-python) - python client for GCP

### <a name='CICD'></a>CI/CD

- [Install poetry](https://github.com/snok/install-poetry) - Github action to install poetry
- [Create Github release](https://github.com/ncipollo/release-action) - Github action create a GitHub release


### <a name='Middlewares'></a>Middlewares

- [PGSync](https://pgsync.com/) - syncing data from Postgres to Elasticsearch
- [Dapr](https://dapr.io/) - abstraction layer for connecting micro-services

---

## <a name='Frontend'></a>Frontend

- [HTMX](https://htmx.org/) - modern browser features directly from HTML

### <a name='Vue.js'></a>Vue.js

- [pinia](https://pinia.vuejs.org/) - new vue store
- [vue-axios](https://www.npmjs.com/package/vue-axios) - axios integration
- [vue-dropzone](https://www.npmjs.com/package/vue2-dropzone) - file upload
- [vue-google-maps](https://www.npmjs.com/package/vue2-google-maps) - google maps integration
- [vue-gtm](https://www.npmjs.com/package/@gtm-support/vue2-gtm) - google tag manager integration
- [vuex](https://github.com/vuejs/vuex) - centralized state management
- [vue-i18n](https://www.npmjs.com/package/vue-i18n)
- vue-slider-component
- vue-tel-input
- [quasar framework](https://quasar.dev/)

### <a name='TailwindCSS'></a>TailwindCSS

- [daisyui](https://github.com/saadeghi/daisyui) - open-source components library
- [hyperui](https://github.com/markmead/hyperui) - a large collection of free components for marketing, ecommerce and application UI
- [merakiui](https://github.com/merakiui/merakiui) - components that support RTL languages & fully responsive based on Flexbox & CSS Grid
- [tailblocks](https://github.com/mertJF/tailblocks) - ready to use blocks

### <a name='AlpineJS'></a>AlpineJS

- [hyperjs](https://js.hyperui.dev/) - a collection of Alpine JS snippets

