# SonicareGenerator
This is a web application that generates the NFC password for a Philips Sonicare toothbrush head.
This can be used to reset its wear timer and continue using the head beyond the manufacurers recommendations.

## Usage

1. Download an NFC reader/writer (e.g. to your Smartphone).
2. Scan the brush head using the NFC reader.
3. Open the generator at [https://nicjes.github.io/SonicareGenerator/](https://nicjes.github.io/SonicareGenerator/).
4. Fill in the UID field (NFC Tag Serial Number displayed in NFC reader).
5. Fill in the MFG field (Code printed underneath brush head).
6. Click the "Generate" button.
7. If the input is valid, the generated password and an advanced NFC command will be displayed.
8. Send this NFC command to your brush head using the NFC writer.

## Input Examples

- Valid UID pattern example: 04:EC:FC:A2:94:10:90
- Valid MFG pattern example: 221214 12K
- Pay attention to the space in the MFG code (regardless if it exists on the head or not)!

## Credits

[@ATC1441](https://github.com/atc1441): For providing the [password generation algorithm](https://gist.github.com/atc1441/41af75048e4c22af1f5f0d4c1d94bb56).
