1. Eingabe der Zahl anstelle des Namens
2. bei Fehler zurück zu Wallet Management, nicht Main
3. Restart the maker service for changes to take effect.
    nur wenn neue aktive wallet als maker genutzt werden aoll





Notes on the `Send Bitcoin` command:

General)

- Order of transaction parameters
The order of the TX parameters is, of course, a matter of personal preference. Nevertheless, I suggest adopting the order already used by JoininBox:

1. `Wallet` (wallet selection not yet implemented)
2. `Source Mix Depth`
3. `Amount`
4. `Counterparties`
5. `Fee Rate`
6. `Destination Address`
7. `Change Address` (not yet implemented)


In the input fields of: `Amount`, `Source Mixdepth` and `Counterparties`

`Counterparties`:
- The default value in the `Counterparties` input field is `2`. However, an entry does not overwrite the `2` but is appended to the end. Overwriting would be more practical.
- Is it reasonable/possible to set the default value to a random number within the recommanded range i.e. 4-10?   

`Destination`:
- Rename title `Destination` to `Destination Address`

`Amount`:
- Rename title `Amount` to `Send Amount`
- The default value in the `Amount` input field is `0`, i.e. `sweep`. However, an entry does not overwrite the `0` but is appended to the end. Overwriting would be more practical.


2.) - The default value in the Source Mixdepth input field is “0”. However, an entry does not overwrite the “0” but is appended to the end.