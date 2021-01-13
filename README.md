# Support Vector Machine from scratch
Build SVM from scratch using only Python and some helper libraries: pandas, numpy,..

There are 5 tasks in total:
- **Task 1**: Inference ([progress](docs/task1.md)).
- **Task 2**: Kernelize SVM ([progress](docs/task2.md)).
- **Task 3**: Training using convex optimization library ([progress](docs/task3.md)).
- **Task 4**: Training using self-implementeed library ([progress](docs/task4.md)).
- **Task 5**: Visualization + Comparison with sklearn ([progress](docs/task5.md)).

# Installation guide 🔥
```
$ git clone https://github.com/trungdt21/svm-from-scratch
$ cd svm-from-scratch
$ pip install -r requirements.txt
$ pre-commit install
```

# Work Convention ✨
- Code convention: Follow PEP8 convention (include docstrings for functions).
- Update `__init__.py` when you add new modules.
- Use pre-commit so that the code would not be messy when merge between commits:
  - Usually, you can just `git commit` and `pre-commit` will run itself.
  - If you want to run it manually, use `pre-commit run --all-files` to run all files, `pre-commit run <hook_id>` to run a specific hook.
- Remember to put understandable commit descriptions.
- Update `taskX.md` of your task (documentation, progress, API documentation) usually so that other can follow it.
- Write tests if you can.

# Contributors 🥺
- Phan Hoang Viet
- Tran Duc Nam
- Nguyen Hoang Tuan Duy
- Dao Tuan Trung
- Mentor: Dzung Nguyen
