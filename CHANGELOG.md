# Change Log
This project adheres to [Semantic Versioning](http://semver.org/).

## 0.8.3
* Improve error messages style.

## 0.8.2
* Better output for projects with multiple limits.
* Fix multiple limits support in `--why`.

## 0.8.1
* Improve CLI help (by Peter deHaan).

## 0.8
* Add `size-limit` configuration section support.

## 0.7.1
* Fix multiline error messages in CLI.
* Do not load `node-zopfli` as loose dependency.

## 0.7
* Add glob pattern support to `sizeLimit` section.

## 0.6.2
* Better project name in Webpack Bundle Analyzer.

## 0.6.1
* Load images by `file-loader`.

## 0.6
* Add `sizeLimit` configuration section support.

## 0.5.1
* Use gzip sizes in Webpack Bundle Analyzer.

## 0.5
* Add Semaphore support.

## 0.4
* Add CircleCI support.

## 0.3.2
* Fix bundle name in `--why` mode.
* Move gzip calculation inside webpack.

## 0.3.1
* Use `read-pkg-up` to find `package.json`.
* Use `ci-job-number` to detect CI job number.

## 0.3
* Run only on first CI job to save CI resources.

## 0.2
* Add `--babili` argument.
* Use Chalk 2.

## 0.1.3
* Fix CLI text (by Yaroslav Markin).

## 0.1.2
* Fix CLI text (by Marais Rossouw).

## 0.1.1
* Fix parsing `B` unit without kilo/mega prefix.

## 0.1
* Initial release.
