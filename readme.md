## First run
The recommended way of installing is by using a virtual environment. The easiest way of doing this is by using [virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/install.html#quick-start).

1. When virtualenvwrapper is installed run the command `mkvirtualenv --python=python3 burry`.
    * In the future you can use `workon burry` to work on the project.
    * If you are using Intellij or PyCharm you can set `Project interpreter`, then click the cog, add local and then point to your `[HOME_FOLDER]/.virtualenvs/burry/bin/python`.
1. Install the dependencies using `pip install -r requirements.txt`. This will install everything you need to use Burry.
1. Acquire a dataset for use with Burry.
    * A sample dataset is available if you have been provided with a `.env` file.
1. Run `jupyter notebook` to start using Burry.
