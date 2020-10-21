# frocli
Tiny but useful CLI snippets for everyday use.

`diffx` = `diff` but run some commands (up to three currently) beforehand
Quite powerful tool. My favourite. Examples:
`diffx a b head` to get preliminary diff of two large files quickly
`diffx a b "sed s/://g"` to process `json` and diff
`diffx a b nonum` throw out numbers and diff
`diffx a b nonum sort` throw out numbers and sort and diff

`diffxvi` = `diffx` + `vim`
`tkdiffx` = `tkdiff` + `diffx`

`diffvi` = `diff` + `vim` to be able to look at the result more thoroughly
`diffrvi` = `diff -r` + `vim`

`cols` = select columns form `tsv` file (by `cut`)
`sstat` = create frequency list / histogram
Maybe the one I have used several thousand times.
`wcless` = `wc` + `less` as it is useful to know the lenght of the output

`nonum` = replace numbers with `#` -- useful when `diff`-ing e.g. logs

`summa` = sum up numbers, one number per line
`summahash` = ...
`hashsumma` = ...

`charperline` = ...
`wordperline` = ...

`merge_two_lines` = merge line#1 and line#2 then line#3 and line#4 then ...

