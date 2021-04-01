# {{cookiecutter.project_name}}

{{cookiecutter.description}}
{% if cookiecutter.default_ci_badges == "Y" %}

## Build Status

### GitHub Actions

![Python Test](https://github.com/{{cookiecutter.github_username}}/{{cookiecutter.project_name}}/workflows/Python%20Test/badge.svg)

{% endif %}

## Requirements

- [requirements.txt](requirements.txt)
- [requirements-dev.txt](requirements-dev.txt)

## Dependencies

## Documentation

## License

{{cookiecutter.license}}

## Author Information

{{cookiecutter.author}}

- [@{{cookiecutter.twitter}}](https://twitter.com/{{cookiecutter.twitter}})
- [{{cookiecutter.email}}](mailto:{{cookiecutter.email}})
- [{{cookiecutter.website}}]({{cookiecutter.website}})

> NOTE: Repo has been created/updated using [https://github.com/mrlesmithjr/cookiecutter-ansible-project](https://github.com/mrlesmithjr/cookiecutter-ansible-project) as a template.
