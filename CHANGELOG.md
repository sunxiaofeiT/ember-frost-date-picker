# 6.0.0

* The `frost-date-picker` component now defaults to empty instead of the current date.


# 5.2.1

* **Fixed** blueprint to not crash.


# 5.2.0

* **Added** additional builds to CI to make sure addon works with latest versions of Ember.
* **Repalced** `moment` and `pikaday` bower deps with Ember shims/npm deps.
* **Removed** files from npm package that aren't necessary (all of the various config files).
* **Updated** dependencies to latest versions.


# 5.1.2
- Remove font-size: 40px

# 5.1.1
- Added default separator
- Cleaner validation for date-picker
- Fix date-picker test

# 5.1.0
Please add a description of your change here, it will be automatically prepended to the `CHANGELOG.md` file.


# 5.0.1
- [x] Accessibility
    - [x] bump and pin pikaday to ~1.5.1 (newly added kb features)
    - [x] https://github.com/srowhani/clockpicker-seconds/issues/1
- [x] Styling fixes to account for accessibility
- [x] Fix calendar icon positioning
- [x] Improve validation to account for kb inputs

Closes #19 #20 

# 5.0.0
- `frost-date-time-picker`
- `frost-range-picker`
- `frost-time-picker`
-  validation (wip)
- scss changes

# TODO
- [x] testing
- [ ] coverage
- [x] lint fix
- [x] validation
- [x] datetime
- [x] rangepicker
- [x] timepicker
- [x] update demo

# 4.0.0
upgrade to frost-core 1.0.0



# 3.0.1
- Fix the demo


# 3.0.0
**updated** supported node version to 6



# 2.0.0
Upgraded ember to 2.8
Added linting and badges
Added integration tests
Updated README

# 1.0.2
No CHANGELOG section found in Pull Request description.
Use a `# CHANGELOG` section in your Pull Request description to auto-populate the `CHANGELOG.md`

# 1.0.1
- let to var

# 1.0.0
- Included Pikaday
- Events binded to ember run loop
- Ember CLI Deploy for ez gh-page pushes
- Styling similar to proposed UX spec
    - https://confluence.ciena.com/pages/viewpage.action?pageId=171217370
