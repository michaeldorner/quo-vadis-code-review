# Quo Vadis, Code Review?

Replication package for the study *Quo Vadis, Code Review? Exploring the Future of Code Review*

## Introduction

This replication package provides the raw data as well as the analysis of an online survey conducted in late 2025 and early 2026 to investigate the future of code review.

## Raw Data

The raw data can be found in the `data` folder as a file named [raw_data.csv](./data/raw_data.csv).
This file is in a CSV format where each column represents a question from the survey and each row represents a response from a participant. The columns are the six questions of the survey:

- How many hours on average do you currently review code per week?
- Do you expect to spend more, less, or same time for code review in five years (in comparison to today)?
- What software artifacts do you review today?
- What software artifacts do you anticipate to review in five years?
- What major changes do you anticipate in code review in five years?
- Based on those changes, what implications for code review do you see?

A final column contains the assigned code.

## Analysis

The analysis of the data is available in the [main.ipynb](./main.ipynb) file.

Install all dependencies using the following command:

```bash
pip install -r requirements.txt
```

### Run the analysis inside a Docker container

You can run the analysis inside a [Dev Container](https://code.visualstudio.com/docs/devcontainers/containers), that already contains all the dependencies needed to run the analysis.

For this setup, you need

1. [Docker](https://www.docker.com)
2. [Visual Studio Code](https://code.visualstudio.com)
3. [Remote Development Extension Pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)

Use then the `Remote-Containers: Open Workspace in Container...` command to open the project inside the container.

## License

This project (source code) is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
