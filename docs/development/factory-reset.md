* `rdctl reset --factory`
  * if you launch | UI
    * -> its stdout is written | "TMP/rdctl-stdout.txt"
      * Reason to NOT write | "logs/": 🧠`reset --factory` deletes it🧠
      * | linux,
        * `TMP` == `/tmp`
      * | macOS,
        * `TMP` == `$TMPDIR`
      * | Windows,
        * `TMP` ==
          * `%TEMP%`(command shell)
          * `$env:TEMP`(powershell)
    * / debug mode,
      * -> `rdctl reset --factory --verbose`
