# Galacticus-Emulator
Normalizing Flow Emulator of Galacticus Subhalo Populations

This is a proof-of-concept for emulation of Galacticus subhalo populations using a machine learning approach (specifically, normalizing flows). The Jupyter notebook runs a small Galacticus model, extracts the relevant parameters for all subhalos, normalizes them, and builds a normalizing flow emulator of the joint PDF. It also provides a function which then samples a subhalo realization from this PDF.
