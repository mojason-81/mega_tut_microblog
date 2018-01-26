# mega_tut_microblog

Working through the Flask Mega-Tutorial.  This is the product
of that endeavor.

Find the tutorial / eBook here:
  - https://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world

## Notes

  - Written and tested with Python3
  - May need to install python3-venv package
  - Generate venv in root directory and install packages via pip
  - Don't forget to `source venv/bin/activate` to activate the virtual env
  - When running `flask run` make sure to...
    - `export FLASK_APP=microblog.py` before you try.
  - To get a Python interpreter in scope of the app...
    - `flask shell`
  - When you're all done fiddling around, don't forget to `deactivate` the virtual env
  - If you get some weird error when updating tranlations such as:
    - `pkg_resources.extern.packaging.markers.UndefinedEnvironmentName: 'extra' does not exist in evaluation environment.`
    - Try updating setuptools pkg via `pip install --upgrade setuptools`
