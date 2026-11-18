Reproduction data and code for Certified limits on modal prediction in two-dimensional Kolmogorov flow

N. Bolivar, G. Abellan and I. Vasilev, version 1.0.0.

The deposit contains the four trajectories used in the article, the initial-field construction, a separate Fourier integrator, directed-interval verification code, and the analytical quadratic-response calculation. The manuscript PDF and LaTeX source contain the definitions and derivations.

The central result is a worst-case prediction error greater than 1e-5 at T=2000 for a modal amplitude, for each of two pairs with identical prescribed initial observations, unresolved norm and laminar spectrum. The quadratic-response bounds distinguish transverse truncation error from the correction beyond quadratic order for the same data.

Files:
manuscript.pdf: article including analytical appendices.
manuscript_sources.zip: clean LaTeX source.
reproduction_code.zip: code, requirements, reference certificates and instructions.
numerical_trajectories.zip.part1 and .part2: binary parts of the original data archive.
data_parts.json: part sizes and SHA256 checksums, and the reconstructed archive checksum.
SHA256SUMS.txt: checksums of all release assets except this checksum list.

Download both parts and data_parts.json into one directory. Extract reproduction_code.zip and run:
python assemble_data.py PATH_TO_DOWNLOADED_PARTS

The reconstructed numerical_trajectories.zip has 2196157280 bytes and SHA256 30b9841645e5330e0d6b05e1975d5dd8ffd3fbaf4d140305696b75b236d82fe1. Extract it into a separate data directory, then follow README.txt in reproduction_code.zip. The full verification takes several CPU hours; the quadratic-response calculation is separate and short. The archive contains exactly the four article trajectories, not an extended parameter survey.

The detailed reproduction commands and software requirements are in README.txt inside reproduction_code.zip.
