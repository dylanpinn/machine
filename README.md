# Machine Ansible setup

Setup a new development machine using Ansible quickly and easily.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

To setup a new machine `ansible` is required, easiest way to install `ansible` is with `pip`, Python's built-in package manager:

```bash
./install-ansible.sh
```

### Installing

To install on MacOS

```bash
ansible-galaxy install -r requirements.yml -r requirements-darwin.yml
ansible-playbook playbook.yml -i hosts -K
```

To install on Linux

```bash
ansible-galaxy install -r requirements.yml
ansible-playbook playbook.yml -i hosts -bK
```

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Built With

* [Ansible](https://docs.ansible.com/) - Configuration management

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/dylanpinn/machine/tags).

## Authors

* **Dylan Pinn** - *Initial work* - [dylanpinn](https://github.com/dylanpinn)

See also the list of [contributors](https://github.com/dylanpinn/machine/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
