# data_science_from_scratch

### Getting started

1. Clone the repo

2. Add data_science_from_scratch (or whatever folder you intend to keep 'lib' directory inside) to sys.path:

   Inside .bashrc or .bash_profile:

   ```shell
   export PYTHONPATH="${PYTHONPATH}:/Users/.../data_science_from_scratch/"
   ```

3. `source .bash_profile` or Restart the terminal.

4. ```PY
   $ python
   >>> from statistics.stats_intro import variance as vrc
   >>> x = [1,2,3,4,5]
   >>> vrc(x)
   2.5
   ```

   