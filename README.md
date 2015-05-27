# stardict-tools-ancient-greek
Stardict tools for Ancient Greek

===============================

First decompile the dictionary to a tab file.
Run `remove-diacritics.sh` to remove the diacritics from the keywords.
Run `transliterate.sh` to transliterate the keywords. The keywords MUST be diacritics-less.
To compile dictionary with duplicate keywords you need to have `stardict-tools (<< 3.0.2) | stardict-tools (>= 3.0.5)`

===============================

Thanks to the folks from Stackoverflow

[1] http://stackoverflow.com/questions/30393681/removing-diacritical-marks-from-a-greek-text-in-an-automatic-way/
[2] http://stackoverflow.com/questions/30461142/using-cut-on-stdout-with-tabs/
