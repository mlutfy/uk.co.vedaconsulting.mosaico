**DO NOT DOWNLOAD DIRECTLY FROM GITHUB**
Download via [the extensions directory](https://civicrm.org/extensions/email-template-builder) as there are additional packaging requirements not handled by github.

## Release 2.10

* Fix [#539](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/539) Fix issue with urls that are double url encoded.
* Fix issue where by some large placeholders aren't rendering behind application load balancers.
* Fix broken images when not logged in - accidently changed with multisite patches.
* [#489](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/489) Add validation rule to Mosaico uploader.
* [#536](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/536) Pass in String null so that db field is set to NULL.
* [#533](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/533) Add type hint to return value.
* [#530](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/530) Multisite support for search kit templates display.
* [#532](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/532) Fix tests following #529.
* [#410](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/410) Multisite support for mosaico.
* [#528](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/528) Various updates for `develop.md`.
* [#525](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/525) Download Mosaico JS files via composer-downloads-plugin.
* [#512](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/512) Define customTemplatesUrl absolute as templatesUrl.
* [#523](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/523) Fix crash when installing via CLI.
* [#520](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/520) Update civix templates.
* [#508](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/508) Bump postcss from 5.2.18 to 7.0.36.
* [#501](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/501) Switch newsletter category to one-time insert instead of managed.
* [#507](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/507) Use CiviCRM core Guzzle dependencies.
* [#500](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/500) Default orderBy Title on template listing search display.
* [#502](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/502) Add APIv4 permissions for MosaicoTemplate.
* Switch newsletter category to one-time insert instead of a managed entity.
* Default orderBy Title on template listing search display.
* [#496](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/496) Don't add the "schedule/send via CiviMail" search task, if the user has insufficient permissions.
* [#488](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/488) Validate multiple email when testing.
* [#490](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/490) Loosen restrictions on required fields.
* [#493](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/493) Ensure that when tests are run search kit is installed.
* [#485](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/485) Remove crmStar styling, require Bootstrap3.

## Release 2.9

* [#478](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/478) Add Mosaico Template Listing page based on Searchkit.
* Add template "Categories" and allow them to be filtered in the UI.
* [#470](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/470) Add hooks to alter Mosaico plugins

## Release 2.8

* [#456](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/456) Add hooks to alter relevant assets in the Mosaico interface.
* [#462](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/462) PHP7.4 compatibility - Fix usage of Curly brackets to do array access.
* [#463](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/463) Improve error handling on image params.
* [#468](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/468) Allow users to choose hotlist tokens.
* [#472](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/472) / [#444](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/444) Auto-save after idle-timeout (~4s) and/or active-timeout (~90s)

## Release 2.7

* [#440](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/440) Add support for personalized tokens for "View in your browser" mode.
* [#451](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/451) Update unit tests to work with phpunit8.
* [#452](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/452) Use Generic Settings Form rather than our custom form.    Fix for issue #427
* [#427](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/427) Update AutoGenerated DAO, Civix, auto_install files to be latest versions from civix commands.
* [#437](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/437) phpunit8 testing compatibility.
* [#433](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/433) Throw error message on resizing image and prevent hard fail.
* [#414](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/414) Add setting to hide base templates.

## Release 2.6

* [#321](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/321) Introduce A/B testing for subject lines.
* [#406](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/406) Fix for mosaico placeholder images not accessible in joomla.
* [#409](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/409) Fix Leave site? warning when not required.
* [#412](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/412) Use standard methods and add validation to URL params for placeholder image endpoint.

## Release 2.5

* Fix [#319](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/319) Warn user before clicking away from mosaico editor.
* [#388](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/388) Adds bullets (unorderd list) to editor
* [#389](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/389)
[#390](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/issues/390)
Fix placeholder images showing on Drupal8, Wordpress.

## Release 2.4

#### Features
* [#345](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/345) Use mosaico graphics service to resize thumbnail.
* [#352](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/352) Make spell check available directly in mosaico.
* [#374](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/374) Add API method to update template URLs.
* [#371](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/371) Provide better support for high resolution images in mosaico.
* Improvements to documentation.

#### Fixes
* Fix path to translation files.
* [#376](https://github.com/veda-consulting-company/uk.co.vedaconsulting.mosaico/pull/376) Fix issue with image rendering (sometimes output buffer started by another module or plugin causes problem with image rendering).
* Update composer libraries for PHP7.3 support.
* Update Mosaico Services to be compatible with Symfony 4.
* Update npm dependencies.
* PHPUnit configuration compatible with PHPUnit6 and PHPUnit7.
* Various tweaks for compatibility if using Shoreditch theme.

## Release 2.3

* Change image placeholder permissions (*Fixes issue with image placeholders for some sites*).

## Release 2.2

* Allow sending traditional emails as a search task.
* Improve validation in image processing.
* Move maximum image size into a setting.
* Drop system check for shoreditch theme as it is not required for Mosaico to function.
* Improve browser incompatibility message.
* Sort templates alphabetically when displaying 'New Mailing'.
* Add translation support - the Mosaico editor will now appear in the same language as CiviCRM if language files are available.

## Release 2.1

* Always place iframe below KAM menu instead of behind.
* Replace '<title>TITLE<title>' with subject (render-time).
* Document hook_civicrm_mosaicoConfig.

## Release 2.0

All users of Mosaico should evaluate and upgrade to this release.

* Simplify requirements:
  * The shoreditch theme is not required - the extension will work with the current CiviCRM theme.
  * ImageMagick is not required - the extension will auto-detect between imagemagick and gd depending on what the server supports.
* Reduce memory usage which previously caused issues sending mail on some servers.
* Add a hook for mosaico editor configuration.

**Download link: https://civicrm.org/extensions/mosaico-civicrm-integration/version-20**
