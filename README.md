# MISTRA Coalitions Barometer: public data

This repository holds the published data files of the MISTRA Coalitions
Barometer dataset. The dataset describes every coalition and minority
administration in South Africa's hung municipal councils since the
local government election of 1 November 2021, together with the
national and provincial administrations formed without a single-party
majority after the general election of 29 May 2024. It is maintained by
the Mapungubwe Institute for Strategic Reflection (MISTRA).

## Status: version 1.0

These files are version 1.0 of the dataset, released on 7 October 2026.
The data runs to 28 February 2026. Known issues in this version are
listed in the release notes:
https://coalitions.mistra.org.za/release-notes.html. Corrections will
appear in later versions and be listed in their release notes.

## Files

All six files are in the `data` folder.

| File | Contents |
| --- | --- |
| `municipal_administrations.csv` | One row per municipal administration |
| `municipal_indicators.csv` | One row per municipality per financial year |
| `provincial_administrations.csv` | One row per provincial administration |
| `provincial_indicators.csv` | One row per province per financial year |
| `national_administrations.csv` | One row per national administration |
| `national_indicators.csv` | One row per financial year for the country |

The codebook, available at https://coalitions.mistra.org.za/downloads.html,
defines every column, the values it may take and how it was coded. Every
file carries a `Geo_Code` column, which holds the official geographic
code of the area the row describes and can be used to join the data to
other sources. Every file also carries a `Notes` column; an empty
`Notes` cell means that no additional context is needed to read the row.

## Versions

Each new version of the dataset replaces these files. Earlier versions
remain available in the history of this repository.

## Citation and licence

The recommended citation is given in section 2 of the codebook.

The data is published under a [Creative Commons Attribution 4.0
International Licence (CC BY 4.0)][cc-by], with the exception of
Total_Seats, the seat columns, Population, the three expenditure
amounts and Geo_Code. These columns were first published by other
bodies and remain subject to their terms; section 2 of the codebook
lists them and their publishers. The full legal text of the licence is
in [`LICENSE`](LICENSE).

[cc-by]: https://creativecommons.org/licenses/by/4.0/

## Contact

Please send corrections and questions to coalitions@mistra.org.za. For
a correction, give the cell or row concerned and a source that supports
it.
