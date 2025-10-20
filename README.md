================================================= test session starts =================================================
platform win32 -- Python 3.13.9, pytest-8.4.1, pluggy-1.6.0 -- C:\Users\Admin\AppData\Local\Microsoft\WindowsApps\PythonSoftwareFoundation.Python.3.13_qbz5n2kfra8p0\python.exe
cachedir: .pytest_cache
rootdir: C:\Users\Admin\Desktop\LLM-evaluation
plugins: anyio-4.11.0, deepeval-3.3.2, langsmith-0.3.45, asyncio-1.2.0, repeat-0.9.4, rerunfailures-12.0, xdist-3.8.0
asyncio: mode=Mode.STRICT, debug=False, asyncio_default_fixture_loop_scope=None, asyncio_default_test_loop_scope=function
collected 4 items

test_evaluation.py::test_case[sample_case0] PASSED                                                               [ 25%]
test_evaluation.py::test_case[sample_case1] PASSED                                                               [ 50%]
test_evaluation.py::test_case[sample_case2] PASSED                                                               [ 75%]
test_evaluation.py::test_case[sample_case3] PASSED                                                               [100%]Running teardown with pytest sessionfinish...


================================================== warnings summary ===================================================
test_evaluation.py::test_case[sample_case0]
  C:\Users\Admin\AppData\Local\Packages\PythonSoftwareFoundation.Python.3.13_qbz5n2kfra8p0\LocalCache\local-packages\Python313\site-packages\deepeval\utils.py:129: DeprecationWarning: There is no current event loop
    loop = asyncio.get_event_loop()

-- Docs: https://docs.pytest.org/en/stable/how-to/capture-warnings.html
====================================== 4 passed, 1 warning in 102.54s (0:01:42) =======================================
