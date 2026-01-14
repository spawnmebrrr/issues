sudo python3 get-pip.py 
Error processing line 1 of /usr/local/lib/python3.5/site-packages/distutils-precedence.pth:

  Traceback (most recent call last):
    File "/usr/local/lib/python3.5/site.py", line 167, in addpackage
      exec(line)
    File "<string>", line 1, in <module>
  ImportError: No module named '_distutils_hack'

Remainder of file ignored
Traceback (most recent call last):
  File "get-pip.py", line 23974, in <module>
    main()
  File "get-pip.py", line 199, in main
    bootstrap(tmpdir=tmpdir)
  File "get-pip.py", line 121, in bootstrap
    import setuptools  # noqa
  File "/usr/local/lib/python3.5/site-packages/setuptools/__init__.py", line 17
    sys.path.extend(((vendor_path := os.path.join(os.path.dirname(os.path.dirname(__file__)), 'setuptools', '_vendor')) not in sys.path) * [vendor_path])  # fmt: skip
                                  ^
SyntaxError: invalid syntax


