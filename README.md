
## Prerequisites
Tested on the following

| Dependencies | Versions |
| ------------ | -------- |
| Python       | 3.6.2    |
| Virtualenv   | 15.1.0   |

## Getting started
1. Create Python virtualenv
    ```bash
    cd producer
    virtualenv --python=<$PATH_TO_PYTHON3.6> flask-restapi/
    ```

1. Activate virtualenv
    ```bash
    source rabbitmq-env/bin/activate
    ```

1. Install python dependenices 
    ```bash
    pip install flask-restful
    ```

## Run the app 
1. Deploy the server 
    ```bash
    cd flask_api_server
    python -m __main_.py
    ```

## Install the setup 
1. Package 
    ```bash
    cd flask-restful
    python setup.py instal 
    ```

## Deployment

## Built With
* [Flask-Rest](https://flask-restful.readthedocs.io)

## Contributing
## Versioning 
## Authors
* **Philip Sales** - *adopted work*
## License
This project is licensed under the Creative Commons- see the Types of [Licenses](https://opensource.org/licenses/alphabetical) 
## Acknowledgments
* [Flask-Rest](https://flask-restful.readthedocs.io)

