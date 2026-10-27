# Semicrystalline-Builder
MFS-SPEED

Builds atomistic semicrystalline polyethylene: a crystal with an amorphous layer whose chains form tails, loops and bridges.

# What's in the notebook
Crystal builder: builds an orthorhombic PE crystal, optionally with a tilted (h0l) crystal/amorphous interface.

Cutting: removes CH2 sites from the amorphous layer to reach a target amorphous density, with helpers to calibrate the cut count.

Diagnostics: reports density, crystallinity, free chain ends and rings after each stage.
MDSystem: fast array-based copy of the system for bond editing; adds hydrogens and converts back to mBuild for saving.

MonteCarlo: end-bridging and tail-reconnection moves that rearrange amorphous chains, then counts tails, loops and bridges.

# Workflow
Build the crystal.
Cut the amorphous layer to the target density.
Run Monte Carlo moves to equilibrate the chain topology.
Add hydrogens and export.

# Run
Press run all on the Jupyter notebook


