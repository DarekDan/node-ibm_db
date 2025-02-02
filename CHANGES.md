2019-07-19, Version 2.5.3
=========================

 * update windows binary in build.zip file (Priyanka Manoharan)

 * Fix for issue #512 (Priyanka Manoharan)

 * support for fs-extra package (#554) (PriyankaManoharan04)

 * fix security alert for lodash (Bimal Jha)

 * Fix for the issue #541 (#549) (PriyankaManoharan04)

 * support for executeFileSync Api (#547) (PriyankaManoharan04)

 * Fix undefined availablePool issue (Bimal Jha)

 * Fix error when pool is not initialized: DBC-4375 (Bimal Jha)

 * update test file (Bimal Jha)

 * Fix for issue #497, remote stale connection from pool (Bimal Jha)

 * Update fstream to 1.0.12 to fix vulnerability (#539) (Vinícius Silva)

 * Update z/OS documentation (#540) (Joran Siu)

 * Add bindings for Electron f/w (#536) (Vyshakh)

 * Add support for DBCLOB data types. Issue #431 (Priyanka Manoharan)

 * Do not delete build direcotry for z/OS. #530 (Bimal Jha)

 * fix test case issue (Bimal Jha)

 * renaming the vscode extension directory as per new extension name (#529) (Vyshakh)

 * update windows binary in build.zip file. (Priyanka Manoharan)

 * clean build directory before rebuild during installation (Bimal Jha)

 * DBC-4156:Add support for SQLRowCount() API on result object returned by stmt.execute (Bimal Jha)

 * Add support for BOOLEAN data type (Bimal Jha)

 * test case for XML datatype (Priyanka Manoharan)

 * Fix for issue #517 (Priyanka Manoharan)

 * Vscode extension detection during install (#518) (Vyshakh)

 * Enable electron build for use with VS Code (#515) (Vyshakh)


2018-12-05, Version 2.5.0
=========================

 * Update README.md (Bimal Kumar Jha)

 * Adding windows binary support for Node V9.X, V10.X, V11.X (#492) (Rohit Pandey)

 * Fix STEPLIB typos for SDSNLOD2 library (#488) (Joran Siu)

 * Revert "Fix ApiDocumentation.md to use Github Markdown anchors" (#491) (Bimal Kumar Jha)

 * Remove extraneous comma in zos test config (#479) (Joran Siu)

 * Node.js Version 9.X and 10.X support. (#398) (Rohit Pandey)

 * Change links to add user-content- prefix, trim whitespace (#477) (Michael Varrieur)

 * fix test case (Bimal Jha)


2018-09-26, Version 2.4.1
=========================

 * Update dependent package versions (Bimal Jha)

 * doc update and add test file (Bimal Jha)

 * Add API Documentation and document fetchAll #409 (Bimal Jha)

 * adding latest binaries for windows support (Rohit Pandey)

 * Fix security vulnerability of manitest files. (Bimal Jha)

 * V11.1clidriver support (#456) (Bimal Kumar Jha)

 * fix typo (Bimal Jha)

 * Add support for result.getSQLErrorSync() API (Bimal Jha)

 * Bug fixes and #440 (Bimal Jha)

 * Update basic + async call tests for z/OS compatibility (#441) (Joran Siu)

 * Update query() API to return sqlcode and state in third parameter of callback function (Bimal Jha)

 * update test file for issue #415 (Bimal Jha)

 * update unzipper version #417 (Bimal Jha)

 * fix for issue #415 (Bimal Jha)

 * DB2 z/OS installation difficulties noted (#408) (Robert Penny)

 * Fix for issue #375 (Bimal Jha)


2018-06-04, Version 2.4.0
=========================

 * adding latest binaries, support for node 9.X on windows (Rohit Pandey)

 * Fix for issue #405, #404, #389 (Rohit Pandey)

 * Document setIsolationLevel #154 (Bimal Jha)

 * Rename getColumnMetadata to getColumnMetadataSync (Bimal Jha)

 * Add queryResult APIs. #246 (Bimal Jha)

 * Doc change for issue #386 (Bimal Jha)

 * Add debug logs (Bimal Jha)

 * Fix for international characters. #388, #399, #401, #402 (Bimal Jha)

 * Restrict createDbSync/dropDbSync on z/OS (#403) (Joran Siu)

 * Update test file for issue #388 (Bimal Jha)

 * update test file with getColumnMetadata (Bimal Jha)

 * adding latest binaries for windows (Rohit Pandey)

 * Correct formatting issue (Bimal Jha)

 * Fix for issue #389 (Bimal Jha)

 * Accessor for column metadata (#391) (Michael Colavita)


2018-04-19, Version 2.3.1
=========================

 * Updated test case for issue #357 (#380) (Rohit Pandey)

 * adding latest code binaries till node 8.X (Rohit Pandey)

 * Set theme jekyll-theme-cayman (Bimal Kumar Jha)

 * Fix for issue #377 and #342 (Bimal Jha)

 * CreateDatabaseSync() and dropDatabaseSync() api support. (#341) (Rohit Pandey)

 * add logs (Bimal Jha)

 * Add GRANT EXECUTE permissions step for z/OS ODBC (#378) (Joran Siu)

 * Fix for issue #329, pull #330, #368 (Bimal Jha)

 * Update tests for z/OS compatiability (Joran Siu)

 * Add z/OS specific updates (Joran Siu)

 * Add z/OS specific configuration and installation steps (Joran Siu)

 * Update README + INSTALL with z/OS details (Joran Siu)

 * Added Fix for issue #253 #331 (rhtpandeyIN)

 * Fix for issue #324 - Calling conn.close twice causes pool.close not to complete (bimalkjha)

 * fix for issue #323 (bimalkjha)


2017-09-29, Version 2.2.1
=========================

 * enhance db2connect license info - issue #317 (bimalkjha)

 * enhance test file to test issue #318 (bimalkjha)

 * Fix for issue #313 (bimalkjha)

 * correct dependency versions in pakcage.json - fix for issue #315 (bimalkjha)

 * Fix for issue #288 - Stringify Pool Object in debug log. (bimalkjha)


2017-09-18, Version 2.2.0
=========================

 * update windows binary (bimalkjha)

 * Windows: Latest pre-compiled binary support (rhtpandeyIN)

 * Windows: Auto Installation support (Compile and build) (#310) (Rohit Pandey)

 * update readme (bimalkjha)

 * New contribution guidelines for node-ibm_db (rhtpandeyIN)

 * test case changes (bimalkjha)

 * Fix for issue #297 - After DB Connection Failure, Available and Used Pool gets blank but poolSize still has value as max pool size (bimalkjha)

 * Fix for issue #307 (bimalkjha)

 * fix for issue #305 (rhtpandeyIN)

 * Fix for issue #293 (bimalkjha)


2017-07-10, Version 2.1.0
=========================

 * fix installer bug (bimalkjha)

 * fix test case issue (bimalkjha)

 * add test script for windows (unknown)

 * error message console warning format correction (rhtpandeyIN)

 * node v8.x support for windows platform with the latest code changes (rhtpandeyIN)

 * clidriver permission issue fix. (#284) (Rohit Pandey)

 * inserted missing escape sequence. (#279) (Rohit Pandey)

 * unzipper finish console message change (Rohit Pandey)

 * issue related to clidriver permission and bindings (rhtpandeyIN)

 * README update for clidriver downloading information #255 (#266) (Rohit Pandey)

 * Fix and Test case for issue #253 (#261) (Rohit Pandey)

 * IBM_DB_INSTALLER_URL detailed information updated- issue #255 (rhtpandeyIN)

 * For issue #256 (bimalkjha)

 * Fix for issue #249 - Invalid cursor state (bimalkjha)

 * Fix for issue #238 (bimalkjha)

 * For issue #230 (bimalkjha)

 * fix test case issues and error handling (bimalkjha)

 * Fix for issue #231 (bimalkjha)

 * remove downloaded clidriver zip file on windows (bimalkjha)

 * fix for issue #229 (bimalkjha)

 * doc updated (bimalkjha)


2017-02-22, Version 2.0.0
=========================

 * fix warning and installer update (bimalkjha)

 * latest node binaries for windows and nodejs version < 0.12.x support for node-ibm-db discontinued. (#228) (Rohit Pandey)

 * For issue #227 (bimalkjha)

 * Add support for i5/OS system naming (bimalkjha)

 * For issue #205 (bimalkjha)

 * Fix for issue #222, downloading driver using "request" module, also Code refactoring in "installer.js" (#226) (Rohit Pandey)

 * Delete dead dynodbc code. (#225) (Ben Noordhuis)

 * fix for connection timeout (bimalkjha)

 * fix for issue #210 (bimalkjha)

 * log enhancement (bimalkjha)

 * update test files (bimalkjha)

 * version update (bimalkjha)

 * test file update (bimalkjha)

 * Rebase (Quentin Presley)

 * typeof NULL is object causing tests to fail (Quentin Presley)

 * udpate test files (bimalkjha)

 * update test file (bimalkjha)

 * update test file for issue #215 (bimalkjha)

 * update about node.js v0.10.x (bimalkjha)

 * adding node V7 support for windows (rhtpandeyIN)

 * Remove unnecessary locking (Quentin Presley)

 * fix for issue #211 (bimalkjha)

 * Add support for OUTPUT parameters of SP in execute() and executeSync() APIs. (bimalkjha)

 * adding unzipper support removing unzip (rhtpandeyIN)

 * add check for dynamically allocated memory (bimalkjha)

 * fix for issue #208 (bimalkjha)

 * fix for issue #207 (bimalkjha)

 * add support for multiple resultset returned by query and querySync methods. (bimalkjha)

 * fix for issue #200 (bimalkjha)

 * fix for #198 (bimalkjha)

 * doc update (bimalkjha)

 * remove stale code related to loginTimeout (bimalkjha)

 * Fix for issue #196 (bimalkjha)

 * fix for issue #192 (bimalkjha)

 * add example for single row fetch at once (bimalkjha)

 * add support for Object in query APIs (bimalkjha)

 * adding CLA contribution licence agreement. (rhtpandeyIN)

 * Add stream support and address pull request #184, #189 and #190. (bimalkjha)

 * update windows binary (bimalkjha)

 * connection pool related changes (bimalkjha)

 * doc update with new pool apis (bimalkjha)

 * Add setIsolationLevel function (Quentin Presley)

 * Code comments (Quentin Presley)

 * fix  for pull request #183 (bimalkjha)

 * Fix up no results code (Quentin Presley)

 * Connectio0n Pooling Enhancement to support MaxPoolSize (bimalkjha)

 * fix test-querySync-select-with-execption.js on windows (George Adams)

 * force test-call-stmt and test-call-async to use the default schema (George Adams)

 * Show stdout and stderr when a test fails (Gibson Fahnestock)

 * update version (bimalkjha)

 * call stmt (bimalkjha)

 * update doc (bimalkjha)

 * update doc with bind info (bimalkjha)

 * test file merge (bimalkjha)

 * Fix for issue #159 (bimalkjha)

 * added try-catch for droping table (bimalkjha)

 * merge pull request #157 (bimalkjha)

 * test files to test OUT and INOUT params in SP (bimalkjha)

 * code changes to supprort OUT param in SP (bimalkjha)

 * used targz instead of tar.gz (Jeremiah Akpotohwo)

 * installed dependencies for ibm_db tests (Jeremiah Akpotohwo)

 * Downgraded tar.gz module to 1.0.2 (Akpotohwo)

 * add support for OUT and INPUT Param in Stored Procedure (bimalkjha)

 * Update white space formatting (Quentin Presley)

 * Added 2 test cases and fixed a bug related to promises (matpasha)

 * Reverting test case (matpasha)

 * added promise support to all methods (matpasha)

 * sample web app using ibm_db (bimalkjha)

 * add logs (bimalkjha)

 * for issue #141 (bimalkjha)

 * begining to add support for promises (IBM_ADMIN)


2016-07-08, Version 1.0.0
=========================

 * Added node V6.X and BLOB/CLOB Support for Windows platform (rhtpandeyIN)

 * fix for issue #139 (bimalkjha)

 * fix for issue #120 (bimalkjha)

 * fix for issue #131 (bimalkjha)

 * query api updated to handle LOB data (bimalkjha)

 * updating README for new APIs (rhtpandeyIN)

 * updating README for API information (rhtpandeyIN)

 * Fix for issue #120 and issue #132 (bimalkjha)

 * fix for segfault (bimalkjha)

 * Added V6 Support and LOB Support (rhtpandeyIN)

 * remove node.js v0.8 support (bimalkjha)

 * update for BLOB supprot (bimalkjha)

 * fix for #119 (bimalkjha)

 * udpated test files (bimalkjha)

 * Fix issues related to v0.10.x (bimalkjha)

 * Add BLOB/CLOB Support (bimalkjha)

 * Added BLOB/CLOB Support (bimalkjha)

 * add build steps (bimalkjha)

 * correct examples (bimalkjha)

 * udpate readme file (bimalkjha)

 * add support for proxy authentication using auth (bimalkjha)

 * update test script for MacOS (bimalkjha)

 * commit (rhtpandeyIN)

 * updating link for INSTALL.md (rhtpandeyIN)

 * updating readme (rhtpandeyIN)

 * updating readme and install.md (rhtpandeyIN)

 * updating INSTALL.md (rhtpandeyIN)

 * Adding all installation steps for INSTALL.md (rhtpandeyIN)

 * added steps for Linux for Power PC (rhtpandeyIN)

 * adding space b/w headings INSTALL.md (rhtpandeyIN)

 * added steps for linux on z in INSTALL.md (rhtpandeyIN)

 * modified AIX steps in INSTALL.md (rhtpandeyIN)

 * modified INSTALL.md (rhtpandeyIN)

 * added steps for AIX in INSTALL.md (rhtpandeyIN)

 * updating INSTALL.md file text format (rhtpandeyIN)

 * updating INSTALL.md file (rhtpandeyIN)

 * test commit (rhtpandeyIN)

 * old commit push for INSTALL.md (rhtpandeyIN)

 * updated INSTALL.md file (rhtpandeyIN)

 * adding INSTALL.md for installation guide (rhtpandeyIN)

 * Fix for issue #93, included code from pull request #94 (rhtpandeyIN)

 * adding support for v5 on windows (rhtpandeyIN)

 * Fix for issue #100, included code from pull request #101 (bimalkjha)

 * fix for compile issue on node.js v0.10.x (bimalkjha)

 * update v4 related comment (bimalkjha)

 * Fix for linux compile issue (bimalkjha)

 * Code changes to support node.js v4.x (bimalkjha)

 * fix for issue #81 (bimalkjha)

 * update doc with AIX install issue (bimalkjha)

 * update about v4 support on windows (bimalkjha)

 * new version with AIX support (bimalkjha)

 * Update installer to support V4 binary on ntx64 (bimalkjha)

 * Including windows binary for v4 (rhtpandeyIN)

 * Adding AIX support for node.js v0.12.x (bimalkjha)

 * information updated (Rohit Pandey)

 * Update: node-ibm_db is now supported on Windows using NodeJS V4.x. (Rohit Pandey)

 * adding latest odbc_bindings.node file (unknown)

 * add debug method (Bimal Kumar Jha)

 * Fix for error preventing compilation without UNICODE support (Bimal Kumar Jha)

 * correct the spelling of platform in installer (Bimal Jha)

 * Replace usage of `timelocal` with `mktime` (Matt Hamann)

 * Adding support for AIX platform. (Bimal Jha)

 * removing v4.x related code form master (Bimal Jha)

 * Updating license text (Bimal Jha)

 * Updated windows limitation (Bimal Jha)

 * update nodejs v4.x info (Bimal Jha)

 * correct formatting (Bimal Jha)

 * add nodejs v4.x info (Bimal Jha)

 * fix code issue (Bimal Jha)

 * fixed code issues (Bimal Jha)

 * fixed nan releated code issue (Bimal Jha)

 * update files for nodejs-v4.1.1 support (Bimal Jha)

 * added supported platforms name (Bimal Jha)

 * Add support for LinuxPPC64LE platfrom (Bimal Jha)

 * fix a js bug, call console.log (Bimal Jha)

 * New binary to reflect cpp code changes. (unknown)

 * update test files. (Bimal Jha)

 * Fix for issue #38 (Bimal Jha)

 * update test files (Bimal Jha)

 * Regroup nodeEE test files. (Bimal Jha)

 * Added support for Linux on z Systems (Bimal Jha)

 * Fix for issue #60 (Bimal Jha)

 * code fix (elkorep)

 * Additional Test Cases (elkorep)

 * Fix for issue #55 (Bimal Jha)

 * Use the fixed versions of dependent modules (Regression Account)

 * Fixes [#50](https://github.com/ibmdb/node-ibm_db/issues/50) (Matt Pelland)

 * fix for issue #45 (Bimal Jha)

 * Revert "0.0.12 fails to install on IBM Bluemix #43" (bimalkjha)

 * 0.0.12 fails to install on IBM Bluemix #43 (Matt Pelland)

 * Fix for issue #42 (Bimal Jha)

 * fix installer issue for windows (bimaljha)

 * Update build.zip and defautl connection timeout. (Bimal Jha)

 * Exit with error code on installation errors, to allow failure detection by automated build tools (Michael Szlapa)

 * Add pool related test files. (Bimal Jha)

 * Update conn.close() for Pool to avoid reconnection before moving to available pool. Add pool related test files and update existing test files. (Bimal Jha)

 * update examples (Bimal Jha)

 * Updating the new build.zip for windows (Bimal Jha)

 * delete build.zip file on ntx64 after unzip (bimaljha)

 * add build.zip (Bimal Jha)

 * add build.zip for windows, add ibm_db.close method to remove members of Database(), update package.jso with new version for release. (Bimal Jha)

 * update package.json that node version should be less than v0.12.0 (Bimal Jha)

 * fix for issue #35 and #36 (Bimal Jha)

 * note about 0.12.x support (ibmdb)

 * Adding Mac OS, other platform support (Avinash K)

 * Fixed a few typos of 'funtion'->'function' (Christopher Bebry)

 * Removing build.zip (Avinash K)

 * formatting macos section (ibmdb)

 * macos (mariobriggs)

 * Intermediate_Fixes branch merge (Avinash K)

 * Fix for pipe stream issue while downloading DSDriver zip file (Avinash K)

 * Fixed error in lib path set in binding.gyp for DB2 installation (Avinash K)

 * Removing unnecessary print statements (Avinash K)

 * Code review changes, removed unnecessary conditionals from binding.gyp (Avinash K)

 * Code review fixes, test-case  clean up (Avinash K)

 * Documenatation changes, Changes after code review (PriyaRanjan)

 * driver install automation on linux, test cases (PriyaRanjan)

 * Automated driver installation for linux (PriyaRanjan)

 * Driver installation automated on linux (PriyaRanjan)

 * Automated linux drivier installation (PriyaRanjan)

 * Commit windows build binary (avinashk)

 * fixes for issue #4, #14, #17 (PriyaRanjan)

 * Update document to note requirements can use a DB2 Server, not just Data Server Driver. (Ian Bjorhovde)

 * Modify to add support for building on Mac OS X Add comments about possibility of using a DB2 Server (e.g., DB2 Express-C) instead of the Data Server Driver only. (Ian Bjorhovde)


2014-10-30, Version -0.0.3
==========================

 * fixes linux new line char (PriyaRanjan)


2014-10-22, Version -0.0.2
==========================

 * test-suite clean up for DB2, fixes for issue #14, bug while retrieving time data type (avinashk)


2014-01-24, Version -0.0.1
==========================

 * First release!
