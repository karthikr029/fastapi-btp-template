# Python Application Template

This repository provides a streamlined template for building **Python applications** tailored for SAP BTP Environment. It includes a robust project structure, configuration management, and deployment readiness for **SAP BTP (Business Technology Platform)**. With this template, you can quickly set up rest endpoints integrated with best practices for scalable and maintainable development, while ensuring seamless deployment to BTP environments.

## Pre-requisites
To effectively use this template the following tools are required to be installed

### 1. [UV](https://docs.astral.sh/uv/)
A rust based python package and project management tool

follow the [installation guide](https://docs.astral.sh/uv/getting-started/installation/) to setup uv. 

> [!TIP]
> - on macOS uv can be installed using brew.
> - uv can also be installed on BAS.

### 2. [Copier](https://copier.readthedocs.io/en/stable/)
A CLI app for rendering project templates

follow the [installation guide](https://copier.readthedocs.io/en/stable/#installation) to setup copier.

> [!TIP]
> copier can be installed as a uv tool.

## Usage

1. using uv

```
uvx copier copy https://github.com/karthikr029/fastapi-btp-template.git <Destination Path>
```
2. using copier cli
```
copier copy https://github.com/karthikr029/fastapi-btp-template.git <Destination Path>
```

## Example

1. create a directory
```
mkdir sample
```
2. open the newly created directoy
```
cd sample
```
3. generate project using the template in the current folder
```
copier copy https://github.com/karthikr029/fastapi-btp-template.git .
```
4. fill in the prompts to generate the project from the template

## Contributing

If you'd like to contribute, please create a new branch to the repository, make your changes, and submit a pull request (PR).

> [!NOTE]
> This README serves as a template for building python application. When using this as a starting point for a new project, ensure you update or delete sections as needed to reflect your specific use case.
