Axelor Open Suite
================================

Axelor Open Suite reduces the complexity and improve responsiveness of business processes. Thanks to its modularity, you can start with few features and  then activate other modules when needed.

Axelor Open Suite includes the following modules :

* Customer Relationship Management
* Sales management
* Financial and cost management
* Human Resource Management
* Project Management
* Inventory and Supply Chain Management
* Production Management
* Multi-company, multi-currency and multi-lingual

Axelor Open Suite is built on top of [Axelor Open Platform](https://github.com/axelor/axelor-open-platform)


Installation
================================

To compile and run from source, you will need to clone Axelor Open Suite modules, which is a
[git submodule](https://git-scm.com/book/en/v2/Git-Tools-Submodules) repository, using following commands:

```bash
$ git clone git@github.com:axelor/open-suite-webapp.git
$ cd open-suite-webapp
$ git checkout master
$ git submodule init
$ git submodule update
$ git submodule foreach git checkout master
$ git submodule foreach git pull origin master
```

You can find more detailed [installation instructions](https://docs.axelor.com/abs/5.0/install/index.html) on our documentation.


docker run --name aos -d --volume /srv/aos/postgresql:/var/lib/postgresql \ aos-preview-app

```bash
docker run --name aos -d --publish 10080:8080 --env 'APP_LANGUAGE=en' --env 'APP_DEMO_DATA=true' --env 'APP_LOAD_APPS=true' --volume /srv/aos/data:/app/data --volume /srv/aos/postgresql:/var/lib/postgresql aos-preview-app
```















Импорт
Импорт
Импорт
Импорт



