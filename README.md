# English dictionary of words

This is a clone of the Webster's New International Dictionary, 2nd Edition, accessible as an Elm list.

## Usage

`import Ni2Dictionary`

`List.filter (\x -> not (List.member x Ni2Dictionary.words)) ListofWords`

`List.length Ni2Dictionary.words`
