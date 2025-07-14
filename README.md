# 🌌 Spatio-Temporal Galaxy Interaction Prediction with Graph Neural Networks (GNNs)

This project applies **spatio-temporal Graph Neural Networks** to model and predict interactions between galaxies based on synthetic astrophysical data. Using **Graph Attention Networks (GAT)** combined with **Time2Vec**-based temporal encoding, we simulate and forecast galaxy dynamics in a spatially-connected graph over time.

## 🚀 Project Highlights

- 📈 **Objective**: Predict future galaxy interactions by learning from synthetic spatio-temporal galaxy data.
- 🔍 **Approach**:
  - Graphs represent galaxies as nodes and spatial proximity as edges.
  - Time-based interactions are modeled with temporal features using Time2Vec.
  - A GAT-based architecture handles attention across time and space.
- 🧪 **Data**: Fully synthetic data simulating 3D galaxy distributions across timesteps.
- 📊 **Task**: Temporal edge prediction — identifying which galaxies are likely to interact in future timesteps.

## 🛠️ Technologies Used

- **PyTorch Geometric**: GNN framework for spatial-temporal modeling.
- **NetworkX**: Graph generation and visualization.
- **Matplotlib**: Plotting and visual feedback.
- **Numpy / Pandas**: Data handling and simulation.

## 🧠 GNN Architecture

- **Encoder**: GAT-based with Time2Vec temporal encodings.
- **Message Passing**: Attention mechanism over spatial and temporal neighbors.
- **Prediction Layer**: Binary classifier to detect interaction edges over time.

## 📁 Folder Structure (in notebook)

Since the project is contained within a Jupyter Notebook, the code includes:
- Data simulation
- Graph construction
- Temporal encoding
- Model definition and training
- Final evaluation

## 👨‍💻 Author

Farid Nowruzi  
Bachelor Student – Data Analysis  
Long-term goal: Astronaut in space technology & AI  

## 📄 License

This project is open for academic and educational use. Feel free to fork or adapt for research or learning.
