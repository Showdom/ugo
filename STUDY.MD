#This For My Python pypi Project.
##config
1. .pypirc
repository: https://upload.pypi.org/legacy/
username:账号
password:密码
##install
1. install:python setup.py install
##package
1. for easy:python setup.py bdist_egg
1. for pypi:python setup.py sdist
##register
1. register in pypi:python setup.py register
1. register in pypi:python setup.py register -r pypi
##upload
1. upload to pypi:python setup.py sdist upload
1. upload to pypi:python setup.py sdist upload -r pypi
1. upload use twine:twine upload dist/*
##pip install
1. install by pip:pip install ugo
1. set proxy: pip --proxy=http://127.0.0.1:80 search ugo
