# Topological-Photonics-GDS-design

> **2025 version.** Forked from Supra. Requires **Python 3.12** and **gdsfactory `~=9.14.0`** (tested with 9.14.2). The **Ligentec AN800 PDK** (`an800-gdsfactory`) is required separately for the edge-coupler design and is **not included in this repository** — obtain it from the foundry.

The repository contains Python codes that use GDSfactory to generate GDS chip design files for topological photonics lattices (both integer and anomalous quantum Hall) found in the following literature:

1. Sunil Mittal _et al_. A topological source of quantum light. Nature **561**, 502–506 (2018). DOI:[10.1038/s41586-018-0478-3](https://www.nature.com/articles/s41586-018-0478-3)
2. Christopher J. Flower _et al_., Observation of topological frequency combs. Science **384**, 1356-1361 (2024). DOI:[10.1126/science.ado0053](https://www.science.org/doi/full/10.1126/science.ado0053)
3. Lida Xu _et al_., On-chip multi-timescale spatiotemporal optical synchronization. Science Advances **11**, eadw7696 (2025). DOI:[10.1126/sciadv.adw7696](https://www.science.org/doi/full/10.1126/sciadv.adw7696)
4. Mahmoud Jalali Mehrabad _et al_., Multi-timescale frequency-phase matching for high-yield nonlinear photonics. Science **390**, 612-616 (2025). DOI:[10.1126/science.adu6368](https://www.science.org/doi/full/10.1126/science.adu6368)

The file _QHE lattice - grating couplers.ipynb_ goes through the following steps for chip design:

1. Design resonator with Euler bends:

![image](https://github.com/user-attachments/assets/b0abc980-f6e7-4836-9c79-846706faf9bf)

2. Design two types of grating couplers:

![image](https://github.com/user-attachments/assets/6d8e19f1-8968-4c07-b145-927b4a03fd5c)

![image](https://github.com/user-attachments/assets/79cc575f-dfd3-4318-992a-3a822322c8a3)

3. Design a 1D chain of coupled resonators with grating couplers:

![image](https://github.com/user-attachments/assets/a70557ca-2e89-431d-a023-694bbcf300d6)

4. Design N x N integer or anomalous topological photonic lattices:

![image](https://github.com/user-attachments/assets/cbb889f4-5bc9-42b8-a31a-742b1a9d3589)

5. Design rings of integer or anomalous topological lattice plaquettes:

![image](https://github.com/user-attachments/assets/09f13f7d-b8c4-4ac3-9424-46564085252e)

![image](https://github.com/user-attachments/assets/2d6403e5-7379-4cd0-b506-fec19f2e5846)

The file _QHE lattice - edge couplers.ipynb_ uses a PDK to generate the following chip design:

<img width="1354" height="633" alt="image" src="https://github.com/user-attachments/assets/39cfe376-3823-4883-92e8-dfc4861c0518" />
