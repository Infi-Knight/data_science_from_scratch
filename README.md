# data_science_from_scratch

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

### Getting started

1.  Clone the repo: `git clone https://github.com/Infi-Knight/data_science_from_scratch`

2.  Add dsfs to sys.path:

    Inside .bashrc or .bash_profile:

    ```shell
    export PYTHONPATH="${PYTHONPATH}:/Users/.../[PATH_TO_dsfs]/"
    ```

    e.g

    ```shell
    export PYTHONPATH="${PYTHONPATH}:/Users/.../data_science_from_scratch/"
    ```

3.  `source .bash_profile` or Restart the terminal.

4.  ```PY
    python
    >>> from statistics.stats_base import variance as vrc
    >>> x = [1,2,3,4,5]
    >>> vrc(x)
    2.5
    ```
