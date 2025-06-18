# Jacob Dugan – Technical Portfolio for SpaceX

This portfolio showcases selected original work in GPU optimization, geospatial routing, and reinforcement learning. All code is authored by me and demonstrates technical depth relevant to a Software Engineering role at SpaceX.

---

## Projects

### 1. 3D-VAE for Medical Imaging
- **Folder**: `3d_vae_medical_imaging/`
- Designed a custom 3D variational autoencoder (VAE) in TensorFlow to expand a dataset of 50 angiograms into over 1,000 synthetic volumes.
- Achieved a 35% training speedup via CUDA-accelerated mixed-precision optimization.
- Includes custom architecture and training experiments that informed methodology for the paper below.
- [ISVC 2023 Paper](3d_vae_medical_imaging/3D_Reconstruction_from_2D_Cerebral_Angiograms_as_a_Volumetric_Denoising_Problem.pdf)
- [Experiment Notebook (PyTorch)](3d_vae_medical_imaging/3D-VAE_PyTorch.ipynb)

---

### 2. Stroke-Care Access Visualization (Mapbox)
- **Folder**: `geospatial_routing/`
- Built a choropleth map visualizing disparities in stroke-care access across U.S. census tracts.
- Frontend powered by Mapbox, backend integrated OpenStreetMap-based routing (Dijkstra) with OpenRouteService.
- [Interactive Demo](geospatial_routing/US_Stroke_Centers.html) — *Open in browser or drag & drop file.*
- [GitHub Repo (Visualization)](https://github.com/jakedugi/census_tract_visualizer)
- Routing pipeline code available upon request (excluded due to local deployment constraints).
- Presented at AHA International Stroke Conference 2024 — [Abstract TMP41](https://www.ahajournals.org/doi/10.1161/str.55.suppl_1.TMP41)

---

### 3. Reinforcement Learning Agents: CartPole & Minitaur
- **Folder**: `rl_agents/`
- Developed and trained RL agents using DQN (CartPole) and SAC (Minitaur) in PyTorch.
- Solved:
  - **CartPole (1 DOF)** in under 3 episodes
  - **Minitaur (28 DOF)** in 80 episodes
- Focused on reproducibility and sample efficiency for robotic control environments.
- [Code on GitHub](https://github.com/jakedugi/simulation_enviroments_guest_lecture)
- Demo videos and logs included in `dugan_portfolio/rl_agents/`

---

## Contact

- Email: [jake@jakedugan.com](mailto:jake@jakedugan.com)  
- [LinkedIn](https://linkedin.com/in/jakedugan)  
- [GitHub](https://github.com/jakedugi)  

