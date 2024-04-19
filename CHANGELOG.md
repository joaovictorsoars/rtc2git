# Change Log

## [Unreleased](https://github.com/rtcTo/rtc2git/tree/HEAD)

[Full Changelog](https://github.com/rtcTo/rtc2git/compare/v1.1...HEAD)

**Implemented enhancements:**

- Check ignored files which still are present [\#72](https://github.com/rtcTo/rtc2git/issues/72)
- Specify user/password on the command line [\#69](https://github.com/rtcTo/rtc2git/issues/69)
- .jazzignore -\> .gitignore [\#66](https://github.com/rtcTo/rtc2git/issues/66)
- Configuration of conflict resolver [\#55](https://github.com/rtcTo/rtc2git/issues/55)
- Ability to use -i when loading a workspace [\#50](https://github.com/rtcTo/rtc2git/issues/50)
- Link commits with Issue-System \(Jira/Github/BitBucket\) [\#48](https://github.com/rtcTo/rtc2git/issues/48)
- Provide configuration with fallback-values [\#47](https://github.com/rtcTo/rtc2git/issues/47)
- Decide if migration should be resumed or is started [\#42](https://github.com/rtcTo/rtc2git/issues/42)
- Make migrated branch to master [\#41](https://github.com/rtcTo/rtc2git/issues/41)
- Ignore binary files [\#33](https://github.com/rtcTo/rtc2git/issues/33)
- Make encoding configurable [\#30](https://github.com/rtcTo/rtc2git/issues/30)
- Add configuration to choose between lscm and scm [\#28](https://github.com/rtcTo/rtc2git/issues/28)
- Ability to accept multiple \(more than two\) change sets together to avoid conflicts [\#27](https://github.com/rtcTo/rtc2git/issues/27)
- Check Replacing of InitialBaseLines/OldestStream [\#23](https://github.com/rtcTo/rtc2git/issues/23)
- One-way Bridge [\#11](https://github.com/rtcTo/rtc2git/issues/11)
- CLI Support [\#10](https://github.com/rtcTo/rtc2git/issues/10)
- Start migration from an existing prepared workspace vs newly created workspace [\#8](https://github.com/rtcTo/rtc2git/issues/8)
- Start migration from a specific baseline [\#6](https://github.com/rtcTo/rtc2git/issues/6)
- Accept changesby date instead of component [\#5](https://github.com/rtcTo/rtc2git/issues/5)
- Loop through migrated branches and compare with stream [\#4](https://github.com/rtcTo/rtc2git/issues/4)

**Fixed bugs:**

- .gitignore files get lost [\#85](https://github.com/rtcTo/rtc2git/issues/85)
- added files in .gitignore should be non-recursive [\#81](https://github.com/rtcTo/rtc2git/issues/81)
- Travis build sometimes failing [\#77](https://github.com/rtcTo/rtc2git/issues/77)
- output of git status -z should not be stripped [\#75](https://github.com/rtcTo/rtc2git/issues/75)
- "\<No comment\>" comment is translated to "\<No comment to" [\#65](https://github.com/rtcTo/rtc2git/issues/65)
- Migration fails on Windows when using long paths [\#61](https://github.com/rtcTo/rtc2git/issues/61)
- Streams with spaces in their name lead to all sorts of problems [\#51](https://github.com/rtcTo/rtc2git/issues/51)
- Running migration a 2nd time on an already migrated repository starts from scratch [\#44](https://github.com/rtcTo/rtc2git/issues/44)
- Handling of capitalization breaks if a file in a directory beginning with 'A' is renamed  [\#39](https://github.com/rtcTo/rtc2git/issues/39)
- Fails to handle Workspace with spaces in name [\#36](https://github.com/rtcTo/rtc2git/issues/36)
- Make encoding configurable [\#30](https://github.com/rtcTo/rtc2git/issues/30)
- retryacceptincludingnextchangeset broken [\#29](https://github.com/rtcTo/rtc2git/issues/29)
- Handling of changeset-comments with linebreaks [\#21](https://github.com/rtcTo/rtc2git/issues/21)
- "Press any other key to skip this changeset and continue" does not continue [\#18](https://github.com/rtcTo/rtc2git/issues/18)
- Switch branch aborted [\#17](https://github.com/rtcTo/rtc2git/issues/17)
- Conflicts and outgoing changes [\#7](https://github.com/rtcTo/rtc2git/issues/7)
- Commit comments fail when comment contains "" [\#1](https://github.com/rtcTo/rtc2git/issues/1)

**Closed issues:**

- Error: "destination path 'XXX' already exists and is not an empty directory [\#103](https://github.com/rtcTo/rtc2git/issues/103)
- Error with lcm show [\#101](https://github.com/rtcTo/rtc2git/issues/101)
- Getting Component History Programmatically [\#84](https://github.com/rtcTo/rtc2git/issues/84)
- Exclude directories from migration [\#74](https://github.com/rtcTo/rtc2git/issues/74)
- Enable line ending normalization for text files [\#73](https://github.com/rtcTo/rtc2git/issues/73)
- Core dumps are committed to Git [\#67](https://github.com/rtcTo/rtc2git/issues/67)
- Collecting change sets to accept together should be from the same component [\#52](https://github.com/rtcTo/rtc2git/issues/52)
- describe way how to configure scm [\#43](https://github.com/rtcTo/rtc2git/issues/43)
- initialCommit should only take place when something has been changed [\#38](https://github.com/rtcTo/rtc2git/issues/38)
- test\_getSampleConfig\_ExpectInitializedConfigWithDefaultValues fails on linux [\#35](https://github.com/rtcTo/rtc2git/issues/35)
- When Git commits are missed, the files are not included with the next commit [\#32](https://github.com/rtcTo/rtc2git/issues/32)
- Delete Folder Logs when migration is started [\#24](https://github.com/rtcTo/rtc2git/issues/24)
- No repositories found based on path [\#14](https://github.com/rtcTo/rtc2git/issues/14)

**Merged pull requests:**

- Replace custom quote function with shlex.quote [\#107](https://github.com/rtcTo/rtc2git/pull/107) ([pbhandari](https://github.com/pbhandari))
- Fix typo in license shield [\#98](https://github.com/rtcTo/rtc2git/pull/98) ([ohumbel](https://github.com/ohumbel))
- \[fix\] Add quotes for Password string since it may contain special chars. [\#96](https://github.com/rtcTo/rtc2git/pull/96) ([cwill747](https://github.com/cwill747))
- Minor cleanups [\#94](https://github.com/rtcTo/rtc2git/pull/94) ([docwhat](https://github.com/docwhat))
- Acceptwithoutmerge [\#91](https://github.com/rtcTo/rtc2git/pull/91) ([WtfJoke](https://github.com/WtfJoke))
- Enhance gitignore [\#89](https://github.com/rtcTo/rtc2git/pull/89) ([reinhapa](https://github.com/reinhapa))
- Fixes no longer working link [\#88](https://github.com/rtcTo/rtc2git/pull/88) ([reinhapa](https://github.com/reinhapa))
- Enable migration.py to be executed on its own [\#87](https://github.com/rtcTo/rtc2git/pull/87) ([ohumbel](https://github.com/ohumbel))
- Fixes \#85: prevent reload from moving .gitignore away [\#86](https://github.com/rtcTo/rtc2git/pull/86) ([ohumbel](https://github.com/ohumbel))
- Make sure ignored file names are not recursive [\#83](https://github.com/rtcTo/rtc2git/pull/83) ([ohumbel](https://github.com/ohumbel))
- Enable to configure exclusion of directories [\#82](https://github.com/rtcTo/rtc2git/pull/82) ([ohumbel](https://github.com/ohumbel))
- enable line ending normalization for text files [\#79](https://github.com/rtcTo/rtc2git/pull/79) ([ohumbel](https://github.com/ohumbel))
- Summary of ignored but still present files [\#78](https://github.com/rtcTo/rtc2git/pull/78) ([ohumbel](https://github.com/ohumbel))
- Correctly parse output of git status -z [\#76](https://github.com/rtcTo/rtc2git/pull/76) ([ohumbel](https://github.com/ohumbel))
- .jazzignore \<-\> .gitignore [\#71](https://github.com/rtcTo/rtc2git/pull/71) ([ohumbel](https://github.com/ohumbel))
- enable RTC credentials on the command line [\#70](https://github.com/rtcTo/rtc2git/pull/70) ([ohumbel](https://github.com/ohumbel))
- Conflictresolution within the same component [\#64](https://github.com/rtcTo/rtc2git/pull/64) ([ohumbel](https://github.com/ohumbel))
- Fixed comparison [\#60](https://github.com/rtcTo/rtc2git/pull/60) ([jacobilsoe](https://github.com/jacobilsoe))
- List files with specific extensions in your workspace [\#59](https://github.com/rtcTo/rtc2git/pull/59) ([ohumbel](https://github.com/ohumbel))
- handle relative file names in tests [\#58](https://github.com/rtcTo/rtc2git/pull/58) ([ohumbel](https://github.com/ohumbel))
- Added configuration of change set accept max count [\#57](https://github.com/rtcTo/rtc2git/pull/57) ([jacobilsoe](https://github.com/jacobilsoe))
- Link commits by adding a prefix on comments [\#56](https://github.com/rtcTo/rtc2git/pull/56) ([WtfJoke](https://github.com/WtfJoke))
- Make inclusion of component roots configurable [\#54](https://github.com/rtcTo/rtc2git/pull/54) ([ohumbel](https://github.com/ohumbel))
- block invalid branch names [\#53](https://github.com/rtcTo/rtc2git/pull/53) ([ohumbel](https://github.com/ohumbel))
- the config file can be specified on the command line [\#46](https://github.com/rtcTo/rtc2git/pull/46) ([ohumbel](https://github.com/ohumbel))
- Allow ignoring big files \(by extension\) [\#45](https://github.com/rtcTo/rtc2git/pull/45) ([ohumbel](https://github.com/ohumbel))
- Quick fix for issue \#39 [\#40](https://github.com/rtcTo/rtc2git/pull/40) ([ohumbel](https://github.com/ohumbel))
- \[fix\] Add quotes around the workspace name [\#37](https://github.com/rtcTo/rtc2git/pull/37) ([cwill747](https://github.com/cwill747))
- Fix for issue 31 [\#34](https://github.com/rtcTo/rtc2git/pull/34) ([ljhaywar](https://github.com/ljhaywar))
- UTF-8 support, configuration of conflict resolution and configuration of scm command [\#26](https://github.com/rtcTo/rtc2git/pull/26) ([jacobilsoe](https://github.com/jacobilsoe))
- Fix Issue 14 [\#15](https://github.com/rtcTo/rtc2git/pull/15) ([WtfJoke](https://github.com/WtfJoke))
- Some suggestions [\#9](https://github.com/rtcTo/rtc2git/pull/9) ([ebullient](https://github.com/ebullient))



\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*