Generating the docs
----------

Install requirements:

    pip install mkdocs mkdocs-cinder

Change directories into the docs folder:

    cd docs

Use [mkdocs](http://www.mkdocs.org/) structure to update the documentation. Test locally with:

    mkdocs serve

If you just have some changes that look good, submit a pull request. If you are an admin for the repo, you can deploy the updated site by publishing to the `gh-pages` branch:

    mkdocs gh-deploy --clean

** Note **: Never edit the generated site by hand because using `gh-deploy` blows away the `gh-pages` branch and you'll lose your edits.
