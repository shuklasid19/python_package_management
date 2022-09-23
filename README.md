 pip install virtualenv /* Install virtual environment */
 virtualenv venv /* Create a virtual environment */
 venv/Scripts/activate /* Activate the virtual environment */


# python packaging 
  building a wheelfile commands required are
  pip install setuptools 
  pip install wheel

# for creating a wheel 
  python setup.py bdist_wheel --universal

# for installing the wheel
  pip install wheel_name
 