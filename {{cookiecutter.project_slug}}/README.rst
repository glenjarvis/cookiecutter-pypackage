{% for _ in cookiecutter.project_name %}={% endfor %}
{{ cookiecutter.project_name }}
{% for _ in cookiecutter.project_name %}={% endfor %}

{{ cookiecutter.project_short_description }}

Project and Build Status
------------------------

.. image:: https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}.svg?branch=master
     :target: https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}
     :alt: Travis tests

.. image:: https://pyup.io/repos/github/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/shield.svg
     :target: https://pyup.io/repos/github/{{ cookiecutter.github_username }}/{{
     cookiecutter.project_slug }}/
     :alt: Updates

.. image:: https://pyup.io/repos/github/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/python-3-shield.svg
     :target: https://pyup.io/repos/github/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/
     :alt: Python 3

.. image:: https://readthedocs.org/projects/test-20180517-03/badge/?version=latest
     :target: http://test-20180517-03.readthedocs.io/en/latest/?badge=latest
     :alt: Documentation Status

.. There is currently a problem at Appveyor
.. .. image:: https://ci.appveyor.com/api/projects/status/github/{{ cookiecutter.github_username }} /{{ cookiecutter.project_slug }}?branch=master&svg=true
      :target: https://ci.appveyor.com/project/{{ cookiecutter.github_username }}/{{ cookiecutter.project_slug }}/branch/master
      :alt: Windows build status on Appveyor

* GitHub repo: {{ cookiecutter.github_project_uri }}/
* Documentation: `Read The Docs <https://{{ cookiecutter.project_slug }}.readthedocs.io/>`_
* Free software: `LICENSE <{{ cookiecutter.github_project_uri }}/blob/master/LICENSE>`_


Welcome
-------

{{ cookiecutter.project_short_description }}

Make this better by Contributing
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

This is an Open Source project and contributions are always welcome, and they
are greatly appreciated! Every little bit helps, and credit will always be
given.

You can contribute in many ways:

* `Report bugs <{{ cookiecutter.issue_tracker_uri }}>`__
* `Write Documentation <https://{{ cookiecutter.project_slug }}.readthedocs.io/>`__
* `Fix bugs <{{ cookiecutter.issue_tracker_uri }}>`__

To maximize the chance that your hard work gets merged, we have these guidelines
to guide you along the way to a successfully merged Pull Request:

* :ref:`contribution_link`
* {{ cookiecutter.github_project_uri }}/blob/master/CONTRIBUTING.rst
