# github-secret-scan

github-secret-scan is a Python tool to help find potentially sensitive files pushed to public or private repositories on Github. This can be used

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install requirements.txt
```

## Options
```
--orgname
    To specify the organization repository name. 
```    

## Usage

Clone this repository and run:
```bash
python gss.py --orgname [name of the organisation]

```

## Github access token
github-secret-scan will need a Github access token in order to interact with the Github API. Create a personal access token and save it in an environment variable in your .bashrc or similar shell configuration file:

```
export access_token=deadbeefdeadbeefdeadbeefdeadbeefdeadbeef
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please also consider contributing the dorks (githubtestdork.txt) that can reveal potentially sensitive information in github.
