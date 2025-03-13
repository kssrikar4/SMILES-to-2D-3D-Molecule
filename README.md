# SMILES to 2D/3D Molecule Converter

This Jupyter Notebook provides a way to convert SMILES (Simplified Molecular Input Line Entry System) representations into 2D and 3D molecular structures using RDKit. The generated molecular structures can be visualized and saved in MOL and SDF file formats.

## Features
- Convert SMILES strings into RDKit molecular objects: Enables users to easily transform chemical structures into computationally accessible formats.
- Generate 2D depictions of molecules: Provides a visual representation for easy interpretation and documentation.
- Generate 3D molecular structures using distance geometry: Allows users to analyze spatial conformations and molecular interactions.
- Export molecules in MOL and SDF formats: Facilitates compatibility with various cheminformatics tools and software for further analysis.

## Requirements
Ensure you have the following dependencies installed before running the notebook:

```bash
pip install notebook rdkit
```

## Usage
1. Open the Jupyter Notebook.
2. Replace `'Your_Smiles'` with the desired SMILES string, add the compound name, and specify the filepath to save the compounds.
3. Run the notebook cells to:
   - Convert the SMILES string into a molecular object.
   - Generate, display and save a 2D depiction.
   - Optimize, generate, visualize and save a 3D molecular structure.
   - Save the generated molecules into MOL or SDF files.


## Output
- `mol_2d.mol`, `mol_2d.sdf`: 2D structures of the molecule.
- `mol_3d.mol`, `mol_3d.sdf`: 3D molecular structure file.
To specify filenames, modify the relevant code sections to set your desired output paths, ensuring that they reflect the correct format and naming convention.

## Contributing
Contributions are welcome! If you have suggestions for improvement or encounter issues, please open an issue or submit a pull request.
