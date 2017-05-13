# tensorflow-jupyter
installation tensorflow and jupyter on vagrant (with python3)

# Requirement
- [vagrant](https://www.vagrantup.com/)

# Usage
__step 1: create vagrant guest machine__

    git clone https://github.com/vazrupe/tensorflow-jupyter.git
    cd tensorflow-jupyter
    vagrant up

__step 2: enter jupyter page__

enter [localhost:9191](http://localhost:9191/) with your web browser

__step 3: 토큰 알아내기__

cat /var/log/notebook/nbserver_stderr.log

url의 맨끝에 토큰이 있습니다.

# Installed on guest machine

- python3(and pip)
- supervisor
- [tensorflow](https://www.tensorflow.org/) 0.11

# License
MIT
