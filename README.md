# MISTRA Coalitions Barometer: public data

This repository holds the published data files of the MISTRA Coalitions
Barometer, a structured dataset tracking coalition governance in South
Africa since the 2021 local government elections. It is maintained by the
Mapungubwe Institute for Strategic Reflection.

## Status: pre-release

These files are a working copy, published ahead of the launch on
7 October 2026. The structure is settled. Repairs_Maintenance_Ratio has
been removed from `municipal_indicators.csv`; column names and column
order will not change again before launch. The values are the real current data, but
they are not final. Rows may be added, and individual values may change,
as coding is completed.

Do not cite this pre-release copy. A citable, versioned release will be
published at launch.

## Files

All six files are in the `data` folder.

| File | Contents |
| --- | --- |
| `municipal_administrations.csv` | One row per municipal administration |
| `municipal_indicators.csv` | Municipal indicators by financial year |
| `provincial_administrations.csv` | One row per provincial administration |
| `provincial_indicators.csv` | Provincial indicators by financial year |
| `national_administrations.csv` | One row per national administration |
| `national_indicators.csv` | National indicators by financial year |

Every file carries a `Geo_Code` column holding the official Municipal
Demarcation Board code for the municipality, province or country the row
describes.

## The Notes column

Every file carries a `Notes` column. An empty `Notes` value
is not missing data.

## How this repository is updated

These files are produced from MISTRA's private research repository by an
export script. The export is run deliberately, when the data is refreshed
or released. It does not track every change to the working data.

## Licence

The data in this repository is licensed under a [Creative Commons
Attribution 4.0 International Licence (CC BY 4.0)][cc-by]. The full legal
text is in [`LICENSE`](LICENSE).

You are free to share and adapt the data, including for commercial purposes,
provided you give appropriate credit, link to the licence, and indicate
whether you made changes.

The pre-release status above is unaffected by this. The licence governs how
you may use these files; it does not make this working copy the citable
version.

[cc-by]: https://creativecommons.org/licenses/by/4.0/

## Contact

Laurence Caromba, Mapungubwe Institute for Strategic Reflection.
