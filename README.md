# plover-dictionaries-backports

Plover dictionaries backported to [Plover](https://github.com/openstenoproject/plover/) [v2.5.8](https://github.com/openstenoproject/plover/releases/tag/v2.5.8)


# Features

* General `computer_use.json` dictionary:
  * `STPH-` and P, R, G, B cluster for arrows (where G is right)
  * `STP-` and P, R, G, B cluster for holding shift and using arrows to select text (where G is right)
  * `PW*F` => `B*S` for **B**ack**s**pace
  * `PW*R` for delete
  * `K*UT` for `⌘x` to cut
  * `KPWR*` for `⌘c` to copy
  * `P*FT` for `⌘v` to paste
  * `S*F` for `⌘s` to save
  * `TKPH` => `ND` (sort of) for `⌘z` to u**nd**o
  * `TKPH*` for `⌘⇧z` to redo
* Plover commands:
  * SUSPEND
  * TOGGLE
  * RESUME
  * ADD_TRANSLATION
* Missing punctuation:
  * >
  * <
  * #
  * ^
  * =
  * @
  * /
  * |
  * ]
  * [
  * _
  * '
  * &
  * \
  * *
  * )
  * (
  * }
  * {
* Top level domains: .com, .org, .net, .ca, .au


# Setup

1.  [Download the dictionary files included](https://github.com/dimonster/plover-dictionaries-backports/archive/master.zip).
2.  Add the newly downloaded dictionary files to your dictionaries folder.
3.  In your Plover dictionary configuration, add the new dictionaries.
