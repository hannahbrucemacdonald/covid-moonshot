# Docked molecules

![ensemble of docked molecules](https://github.com/foldingathome/covid-moonshot/raw/master/docking/docked-molecules.png "Ensemble of docked molecules")

## Manifest
* `covid_submissions_03_26_2020 - docked.sdf` - docked COVID Moonshot molecules as of 2:34 PST March 27, 2020
   * Each molecule was docked into every fragment structure listed as inspirati; the corresponding fragment is listed in the `<fragments>` tag;
     docked structures are found in `f'../receptors/Mpro-{fragment}-protein.pdb'`
   * Some Moonshot molecules failed to dock and were omitted
   * See `../scripts/README.md` for more information on methodology
* `mpro_fragments_03_25_2020 - docked.sdf` - docked [DiamondMX fragment hits](https://www.diamond.ac.uk/covid-19/for-scientists/Main-protease-structure-and-XChem/Downloads.html) from 2020-03-25 for score comparison
   * Each compound was redocked into its original fragment structure
