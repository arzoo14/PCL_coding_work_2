# PCL Documentation

This repository demonstrates a small example of [PCL Documentation](https://pcl-documentatiom.readthedocs.io/en/latest/).

### How to add a new topic to the documentation
**Step 1:**  Add the `.rst` file in `docs/` folder. (say file name - test.rst)

**Step 2:**  Add the same `.rst` file name in `docs/index.rst` file under the `Contents:` heading. ( as test)

**Step 3:**  Add the same `.rst` file name in `docs/_build/html/_sources/index.rst.txt` file under the `Contents:` heading. (as test)

Now commit the changes to the github repository.

Open the [PCL Documentation](https://pcl-documentatiom.readthedocs.io/en/latest/) and see your file there. 

We can also edit any `.rst` file directly in the repository and after committing the changes, the same will get reflect in the website also.
