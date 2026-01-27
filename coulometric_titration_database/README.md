# Coulometric Titration Reference Database (in Liquid Electrolyte)
The purpose of this database is to provide reference measurements to be reused,
e.g. by Coulometric titration comparison (CTC). Contributions to the database are
very welcome. (Check below to contribute)

## Folder structure
Each active material has its own folder:
Material_Name/
  titration_curve.txt
  metadata.txt

## Data format
- `titration_curve.txt` must contain at least:
  - capacity/charge starting from q0 (mAh/g)
  - potential (V vs. Li+/Li)
Column headers should be clearly labeled. 

## How to contribute
1. Fork this repository
2. Create a new folder named after your active material
3. Add:
   - `titration_curve.txt`
   - `metadata.txt`
4. Open a pull request

## Optimal metadata
Each dataset should include:
- Active material description (incl. mass of active material)
- Electrolyte details
- Measurement temperature
- coulometric titration parameters (current, polarization time, relaxation time)
- Contributor name and affiliation
- Source (publication, thesis, or "unpublished")

