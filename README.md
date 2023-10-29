[![CI](https://github.com/nogibjj/python-ruff-template/actions/workflows/cicd.yml/badge.svg)](https://github.com/nogibjj/python-ruff-template/actions/workflows/cicd.yml)

# Jiechen_Li_Mini_9_Colab

## Purpose

* Set up a cloud-hosted Jupyter Notebook (e.g., Google Colab)
* Perform data manipulation tasks on a sample dataset

## Preparation

1. Open codespaces
2. Create Google Colab Notebook
3. Wait for container to be built with requiremnts.txt installed

## CI/CD

On git push/pull request the CI/CD flow is triggered using Github Actions:

1. Install and validate Rust toolchain
2. Format and lint code
3. Run unit tests
4. Build binary release
5. Lint Dockerfile
6. Build distroless rusty-ds image
7. Push image to [Github Container Registry](https://github.com/athletedecoded?tab=packages)

## Task Preformed

1. Clone [Jiechen_Li_Mini_2_Pandas](https://github.com/nogibjj/Jiechen_Li_Mini_2_Pandas.git) as the template
2. Creat a new juptyter notebook on Google Colab
3. Perform data manipulation in the jupyter notebook
4. Link the Google Colab to Github

## Deliverables

* [Link to the cloud-hosted notebook](https://colab.research.google.com/drive/1aAoZy0GuNYF7m7dGOXIIfQOp5lXs9z5R?usp=sharing)
* [Document demonstrating the tasks performed](task_performed.md)

## Visualizations

1. **Relationship between room types and price**
<img decoding="async" src="./7.png" width="85%"><br/>  

2. **Relationship between beds and price**
<img decoding="async" src="./8.png" width="85%"><br/>

3. **Relationship between room types, beds number, and price**
<img decoding="async" src="./9.png" width="85%"><br/>
