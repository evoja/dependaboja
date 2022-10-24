# Change log of Dependaboja

<!---
#### [Unreleased][unreleased]
##### Added
##### Changed
##### Deprecated
##### Removed
##### Fixed
##### Security
##### Broken
--->




## v0.0
#### [0.0.3] - [2022-10-09][c-0.0.3]
##### Added
Create deps branches if they do not exist


#### [0.0.2] - [2022-01-26][c-0.0.2]
##### Fixed
* Start supporting dependabot configs which contained several sections with the same target branch.
* Syncing a single `sync_with` branch.

#### [0.0.1] - [2022-01-23][c-0.0.1]
##### Fixed
Change order of one step that was responsible for reporting of skipping behaviour.
Invalid order caused a tiny mistake that didn't affect the main feature.
Only in case of skipping the reporting step it was not invoked.

##### Added
Some inline comments which explain structure and behaviour of the action.


#### [0.0.0] - 2022-01-22
Merge dependabot PRs to aggregated branches and sync the aggregated branches with master.




------------
Changelog file follows [this convention](https://keepachangelog.com/)

[unreleased]: https://github.com/evoja/dependaboja/compare/0.0.3...master

[c-0.0.3]: https://github.com/evoja/dependaboja/compare/0.0.2...0.0.3
[0.0.3]: https://github.com/evoja/dependaboja/tree/0.0.3

[c-0.0.2]: https://github.com/evoja/dependaboja/compare/0.0.1...0.0.2
[0.0.2]: https://github.com/evoja/dependaboja/tree/0.0.2

[c-0.0.1]: https://github.com/evoja/dependaboja/compare/0.0.0...0.0.1
[0.0.1]: https://github.com/evoja/dependaboja/tree/0.0.1

[0.0.0]: https://github.com/evoja/dependaboja/tree/0.0.0
