# Oxford calendar terms for Emacs

**UPDATE 2026-02-11 22:54 +0200:** This project is discontinued and
superseded by my `institution-calendar`: <https://github.com/protesilaos/institution-calendar>.

* * *

SCREENSHOT here: <https://protesilaos.com/codelog/2026-01-09-emacs-oxford-calendar-package/>.

* * *

The `oxford-calendar` package augments the `M-x calendar` buffer to
include the week number of the current University of Oxford academic
calendar term. Weeks are numbered 1 through 8 for each of the
Michaelmas, Hilary, and Trinity terms.

To show the indicators, enable the `oxford-calendar-mode`. By default,
it includes the extra weeks 0 and 9 at the boundaries of each term.
The idea is to make things easier for planning purposes. Remove those
extra weeks by setting `oxford-calendar-include-extra-week-numbers` to
`nil`.

To include a heading above the term indicators, set the user option
`oxford-calendar-include-intermonth-header` to a non-`nil` value.

+ Package name (GNU ELPA): `oxford-calendar` (!!! COMING SOON)
+ Git repository: <https://github.com/protesilaos/oxford-calendar>
+ Backronym: Overtly Xenial Feature Orders Relevant Dates ... Calendar.
