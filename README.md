**[Installation](#installation)** |
**[Documentation](https://jupyterlab.readthedocs.io)** |
**[Contributing](#contributing)** |
**[License](#license)** |
**[Team](#team)** |
**[Getting help](#getting-help)** |

# [JupyterLab](https://jupyterlab.readthedocs.io)

## Getting started

### Installation

If you use [conda](https://docs.conda.io/en/latest/), [mamba](https://mamba.readthedocs.io/en/latest/), or [pip](https://docs.python.org/3/installing/index.html), you can install JupyterLab with one of the following commands.

- If you use conda:
  ```shell
  conda install -c conda-forge jupyterlab
  ```
- If you use mamba:
  ```shell
  mamba install -c conda-forge jupyterlab
  ```
- If you use pip:
  ```shell
  pip install jupyterlab
  ```
  If installing using `pip install --user`, you must add the user-level `bin` directory to your `PATH` environment variable in order to launch `jupyter lab`. If you are using a Unix derivative (e.g., FreeBSD, GNU/Linux, macOS), you can do this by running `export PATH="$HOME/.local/bin:$PATH"`. If you are using a macOS version that comes with Python 2, run `pip3` instead of `pip`.

For more detailed instructions, consult the [installation guide](http://jupyterlab.readthedocs.io/en/latest/getting_started/installation.html). Project installation instructions from the git sources are available in the [contributor documentation](CONTRIBUTING.md).

#### Installing with Previous Versions of Jupyter Notebook

When using a version of Jupyter Notebook earlier than 5.3, the following command must be run after installing JupyterLab to enable the JupyterLab server extension:

```bash
jupyter serverextension enable --py jupyterlab --sys-prefix
```

### Running

Start up JupyterLab using:

```bash
jupyter lab
```

JupyterLab will open automatically in the browser. See the [documentation](http://jupyterlab.readthedocs.io/en/latest/getting_started/starting.html) for additional details.

If you encounter an error like "Command 'jupyter' not found", please make sure `PATH` environment variable is set correctly. Alternatively, you can start up JupyterLab using `~/.local/bin/jupyter lab` without changing the `PATH` environment variable.

### Prerequisites and Supported Browsers

The latest versions of the following browsers are currently _known to work_:

- Firefox
- Chrome
- Safari

See our [documentation](http://jupyterlab.readthedocs.io/en/latest/getting_started/installation.html) for additional details.

---

## Getting help

We encourage you to ask questions on the [Discourse forum](https://discourse.jupyter.org/c/jupyterlab). A question answered there can become a useful resource for others.

### Bug report

To report a bug please read the [guidelines](https://jupyterlab.readthedocs.io/en/latest/getting_started/issue.html) and then open a [Github issue](https://github.com/jupyterlab/jupyterlab/issues/new?labels=bug%2C+status%3ANeeds+Triage&template=bug_report.md). To keep resolved issues self-contained, the [lock bot](https://github.com/apps/lock) will lock closed issues as resolved after a period of inactivity. If a related discussion is still needed after an issue is locked, please open a new issue and reference the old issue.

### Feature request

We also welcome suggestions for new features as they help make the project more useful for everyone. To request a feature please use the [feature request template](https://github.com/jupyterlab/jupyterlab/issues/new?labels=enhancement%2C+status%3ANeeds+Triage&template=feature_request.md).

---

## Development

### Extending JupyterLab

To start developing an extension for JupyterLab, see the [developer documentation](https://jupyterlab.readthedocs.io/en/latest/extension/extension_dev.html) and the [API docs](https://jupyterlab.readthedocs.io/en/latest/api/).

### Contributing

To contribute code or documentation to JupyterLab itself, please read the [contributor documentation](https://jupyterlab.readthedocs.io/en/latest/developer/contributing.html).

JupyterLab follows the Jupyter [Community Guides](https://jupyter.readthedocs.io/en/latest/community/content-community.html).

### License

JupyterLab uses a shared copyright model that enables all contributors to maintain the
copyright on their contributions. All code is licensed under the terms of the revised [BSD license](https://github.com/jupyterlab/jupyterlab/blob/main/LICENSE).
