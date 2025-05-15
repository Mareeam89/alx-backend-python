## Project Description
Learn the difference between unit and integration tests.
Common testing patterns such as mocking, parametrizations and fixtures.

* **0. Parameterize a unit test** - Implement the `TestAccessNestedMap.test_access_nested_map` method to test that the method returns what it is supposed to. - `test_utils.py`.
* **1. Parameterize a unit test** - Implement `TestAccessNestedMap.test_access_nested_map_exception`. Use the `assertRaises` context manager to test that a `KeyError` is raised for the given inputs (use `@parameterized.expand`). - `test_utils.py`.
* **2. Mock HTTP calls** - Define the `TestGetJson(unittest.TestCase)` class and implement the `TestGetJson.test_get_json` method to test that `utils.get_json` returns the expected result. - `test_utils.py`.
* **3. Parameterize and patch** - Implement the `TestMemoize(unittest.TestCase)` class with a `test_memoize method`. - `test_utils.py`.
* **4. Parameterize and patch as decorators** - Declare the `TestGithubOrgClient(unittest.TestCase)` class and implement the `test_org` method. - `test_client.py`.
* **5. Mocking a property** - Implement the `test_public_repos_url` method to unit-test `GithubOrgClient._public_repos_url`. - `test_client.py`.
* **6. More patching** - Implement `TestGithubOrgClient.test_public_repos` to unit-test `GithubOrgClient.public_repos`. - `test_client.py`.
* **7. Parameterize** - Implement `TestGithubOrgClient.test_has_license` to unit-test `GithubOrgClient.has_license`. - `test_client.py`.
* **8. Integration test: fixtures** - Create the `TestIntegrationGithubOrgClient(unittest.TestCase)` class and implement the `setUpClass` and `tearDownClass` which are part of the `unittest.TestCase` API. - `test_client.py`.
* **9. Integration tests** - Implement `test_public_repos` to  test `GithubOrgClient.public_repos`. - `test_client.py`.

