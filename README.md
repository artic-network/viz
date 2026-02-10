# Interactive Visualizations for Phylogenetics and Bioinformatics

This repository contains interactive HTML-based visualizations for teaching phylogenetics and bioinformatics concepts.

## Contents

### 1. Phylogenetics Practical: Whippomorpha (`phylogenetics_practical.html`)

A comprehensive graduate-level practical on molecular phylogenetics focusing on the evolutionary relationships of Whippomorpha (whales and hippos). 

**Topics covered:**
- Maximum likelihood phylogenetic inference
- Nucleotide substitution models (JC69, K80, HKY, GTR)
- Site rate heterogeneity (discrete gamma distribution, invariable sites)
- Likelihood ratio tests for model comparison
- Bootstrap support for phylogenetic hypotheses
- Monophyly concepts and testing

**Features:**
- Detailed biological background on cetaceans and hippopotamids
- Step-by-step practical exercises using MAFFT and IQ-TREE
- Interactive Chi-squared distribution plot for likelihood ratio tests
- Interactive discrete gamma distribution visualization
- Discussion questions throughout to foster critical thinking

### 2. Discrete Gamma Distribution Interactive (`gamma_distribution_interactive.html`)

A standalone interactive visualization of the discrete gamma distribution used to model rate heterogeneity in phylogenetics.

**Features:**
- Adjustable shape parameter (α) on a logarithmic scale (0.5 to 100)
- Variable number of rate categories (2-10)
- Real-time visualization showing:
  - Continuous gamma distribution (black curve)
  - Discrete rate categories as colored bars with equal areas (equal probability)
  - Mean rate line (normalized to 1.0)
  - Calculated rates for each category

**Educational value:**
- Demonstrates how continuous distributions are discretized for computational phylogenetics
- Shows the relationship between α and rate variation
- Illustrates the +G model commonly used in programs like IQ-TREE

## Usage

These are standalone HTML files that can be opened directly in any modern web browser. No server or additional dependencies required.

```bash
# Open in your default browser
open phylogenetics_practical.html
# or
open gamma_distribution_interactive.html
```

## Technologies

- Pure HTML5, CSS3, and vanilla JavaScript
- Canvas API for interactive plots
- No external dependencies

## Target Audience

- Graduate students in evolutionary biology, bioinformatics, and related fields
- Instructors teaching molecular phylogenetics
- Researchers wanting interactive demonstrations of phylogenetic concepts

## License

MIT License - feel free to use and adapt for educational purposes.

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

## Authors

Created for the ARTIC Network educational resources.
