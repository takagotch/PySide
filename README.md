### pyside
---
https://github.com/pyside

https://wiki.qt.io/PySide

```py
//

class TestRunner(object):
  def __init__(self, log_entry, project, index):
    self.log_entry = log_entry
    built_path = log_entry.build_dir
    self.test_dir = os.path.join(built_path, project)
    log_dir = log_entry.build_dir
    if index is not None:
      self.logfile = os.path.join(log_dir, project + ".{}.log".format(index))
    else:
      self.logfile = os.path.join(log_dir, project + ".log")
    os.environ['CTEST_OUTPUT_ON_FAILURE'] = '1'
    self._setup_clang()
    self._setup
  
  def _setup_clang(self):

```

```
```

```
```


