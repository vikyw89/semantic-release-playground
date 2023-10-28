# CHANGELOG



## v0.1.0 (2023-10-28)

### Chore

* chore(main.py): remove unnecessary main.py file

The main.py file was deleted as it contained unnecessary code that was not being used in the project. Removing this file helps to keep the codebase clean and reduces clutter. ([`7586b82`](https://github.com/vikyw89/semantic-release-playground/commit/7586b824d35a78e6a4d78a997a7fc4bf840775df))

* chore(pyproject.toml): switch commit_parser from &#34;emoji&#34; to &#34;angular&#34; for more conventional commit messages
feat(pyproject.toml): update allowed_tags in commit_parser_options to include a comprehensive list of conventional commit types ([`0d55d7b`](https://github.com/vikyw89/semantic-release-playground/commit/0d55d7bed6793899caaf122fc7cb34da6dc6b001))

### Feature

* feat(main.py): add basic FastAPI routes for root and item endpoints

The main.py file was added with basic routes for the root (&#34;/&#34;) and item (&#34;/items/{item_id}&#34;) endpoints using the FastAPI framework. The root endpoint returns a simple JSON response with the message &#34;Hello World&#34;, while the item endpoint returns a JSON response with the provided item_id and an optional query parameter &#34;q&#34;. ([`c98e4b4`](https://github.com/vikyw89/semantic-release-playground/commit/c98e4b434021bc73a4191e8a5f04b1e44b5f57c3))

### Unknown

* Merge branch &#39;alpha&#39; of https://github.com/vikyw89/semantic-release-playground into alpha ([`4d72fb2`](https://github.com/vikyw89/semantic-release-playground/commit/4d72fb2a1b0da85b1f561d8fae4cdabb76bd96d1))

* ✨ feat(main.py): add FastAPI endpoints for root and item with optional query parameter
📦 chore(pyproject.toml): add fastapi as a dependency to enable FastAPI usage in the project ([`e1dbfb8`](https://github.com/vikyw89/semantic-release-playground/commit/e1dbfb8a2b2a5e8a58ceff352656b8da40763a8a))

* 📦 chore(main.py): add new file main.py to the project ([`e51d624`](https://github.com/vikyw89/semantic-release-playground/commit/e51d624c9fd0f904004600735361cb50e6ec6552))


## v0.0.1 (2023-10-28)

### Unknown

* :bug: Bug

bug ([`8ac0e8f`](https://github.com/vikyw89/semantic-release-playground/commit/8ac0e8f1e9d96f724533fefd84b38a9c374de50d))


## v0.0.0 (2023-10-28)

### Unknown

* 📦 chore(semver): add semver package and tests package ([`41b656f`](https://github.com/vikyw89/semantic-release-playground/commit/41b656f0dffa4895ce1a867686e16e8e226e52b5))

* 🔥 chore(README.md, pyproject.toml): remove semver directory and its files

The semver directory and its files, README.md and pyproject.toml, were deleted as they are no longer needed in the project. ([`f328708`](https://github.com/vikyw89/semantic-release-playground/commit/f328708716359cce788398ca0e5216590298204d))

* 🔧 chore(pyproject.toml): remove extra blank line to improve readability ([`de45c3b`](https://github.com/vikyw89/semantic-release-playground/commit/de45c3bee439a2c52d408c12ebd9ebfc0638a9c6))

* 📦 chore(README.md): add README.md file to the semver directory
📦 chore(pyproject.toml): add pyproject.toml file to the semver directory with project metadata and dependencies
📦 chore(__init__.py): add __init__.py file to the semver directory
📦 chore(tests/__init__.py): add __init__.py file to the semver/tests directory ([`3c09b10`](https://github.com/vikyw89/semantic-release-playground/commit/3c09b1053a90f8f9b99645fda05e59d274485224))

* Initial commit ([`3a8158e`](https://github.com/vikyw89/semantic-release-playground/commit/3a8158e42f5b81dee989512909ba73b3318a3aa3))
