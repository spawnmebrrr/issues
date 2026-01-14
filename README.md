# issuessudo python3 -m pip install qtconsole pyqt5 jupyter-console g-python
Error processing line 1 of /usr/local/lib/python3.5/site-packages/distutils-precedence.pth:

  Traceback (most recent call last):
    File "/usr/local/lib/python3.5/site.py", line 167, in addpackage
      exec(line)
    File "<string>", line 1, in <module>
    File "/usr/local/lib/python3.5/site-packages/_distutils_hack/__init__.py", line 34
      f"Register concerns at {report_url}"
      ^
  SyntaxError: invalid syntax

Remainder of file ignored
Traceback (most recent call last):
  File "/usr/local/lib/python3.5/runpy.py", line 174, in _run_module_as_main
    mod_name, mod_spec, code = _get_module_details(mod_name, _Error)
  File "/usr/local/lib/python3.5/runpy.py", line 133, in _get_module_details
    return _get_module_details(pkg_main_name, error)
  File "/usr/local/lib/python3.5/runpy.py", line 109, in _get_module_details
    __import__(pkg_name)
  File "/usr/local/lib/python3.5/site-packages/pip/__init__.py", line 18, in <module>
    from pip.commands import get_summaries, get_similar_commands
  File "/usr/local/lib/python3.5/site-packages/pip/commands/__init__.py", line 14, in <module>
    from pip.commands.install import InstallCommand
  File "/usr/local/lib/python3.5/site-packages/pip/commands/install.py", line 10, in <module>
    import wheel
  File "/usr/local/lib/python3.5/site-packages/wheel/__init__.py", line 1
    from __future__ import annotations
SyntaxError: future feature annotations is not defined

