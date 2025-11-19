# 🛰️ WICO Twitter Subgraph Analysis — All-In-One README  
### **5G Misinformation vs Non-Conspiracy — Full Technical, Analytical & Security Report**  


---

# 📌 1. Overview  
This repository contains **everything** related to the analysis of two Twitter subgraphs from the **WICO Dataset**, including:

- Full Gephi analysis  
- Comparative study  
- Security & Threat Intelligence findings  
- Written question answers  
- Final unified report contents  
- Repository structure  
- Student information  

This README is **all-in-one** — no need to open any other file.

---

# 👨‍🎓 2. Student Information  
- **Name:** Ahmed Mohammed Ashri Mourad  
- **ID:** 2205229  
- **Course:** Social Network Computing  

---

# 🛰️ 3. Dataset Description  
Two subgraphs from WICO were analyzed:

1. **5G Conspiracy / Misinformation Graph**  
2. **Non-Conspiracy Graph**

Graphs were processed using **Gephi** with layouts + statistics + community detection.

---

# 📊 4. 5G Conspiracy Graph — Full Results

| Metric | Value |
|--------|-------|
| Nodes  | 42    |
| Edges  | 45    |
| Avg Degree | 1.071 |
| Density | 0.026 |
| Clustering Coefficient | 0.040 |
| Modularity | 0.267 |
| Communities | 13 |
| Diameter | 3 |
| Radius | 0 |
| Avg Path Length | 1.847826 |
| Weak Components | 8 |
| Strong Components | 34 |

### Required Screenshots
- Graph visualization  
- Degree distribution  
- Clustering panel  
- Modularity panel  
- Path length plot  
- Components plot  

---

# 📊 5. Non-Conspiracy Graph — Full Results

| Metric | Value |
|--------|-------|
| Nodes | 61 |
| Edges | 62 |
| Avg Degree | 1.016 |
| Density | 0.017 |
| Clustering Coefficient | 0.049 |
| Modularity | 0.267 |
| Communities | 13 |
| Diameter | 3 |
| Radius | 0 |
| Avg Path Length | 1.847 |
| Weak Components | 5 |
| Strong Components | 59 |

---

# ⚖️ 6. Comparative Analysis Summary  

### ⭐ Structural  
- 5G graph is **denser** → more coordinated behavior  
- Non-Conspiracy has **higher clustering** → natural conversations  
- 5G has **fewer SCCs** → low reciprocity  
- Non-Conspiracy has **more SCCs** → real interactions  

### ⭐ Diffusion  
- 5G spreads faster → very short path length + radius=0  
- Non-Conspiracy spreads normally  

### ⭐ Communities  
- 5G: 13 tightly coordinated communities  
- Non-Conspiracy: organic, diverse clusters  

---

# 🔐 7. Security Analysis & Threat Intelligence Findings  

### 🧩 Fake Followers  
- Low clustering + high density  
- Weak components → fake follower clusters  

### 🤖 Bot Indicators  
- Radius = **0** → central controller  
- Diameter = **3** → fast automated spread  
- Low SCC  

### 🕸️ Coordinated Inauthentic Behavior (CIB)  
- Central hubs controlling message flow  
- Echo chambers  
- ~2-hop diffusion → synchronized amplification  

### 📢 Influence Operations  
- Modularity = **0.267** → structured coordination  
- Artificial boosting via highly connected subclusters  

### 🔒 Summary  
- **5G Network = high-risk misinformation structure**  
- **Non-Conspiracy = natural human activity**  

---

# 📝 8. Written Questions — Short Answers  

### 1) Clustering & degree for bots  
Bots → low clustering, unbalanced degree.

### 2) Echo chamber  
Dense inward links → appears clearly in 5G graph.

### 3) How visualizations detect misinformation  
Star patterns, bot cliques, radius=0, hubs.

### 4) Role of community detection  
Reveals botnets, coordinated groups, echo chambers.

### 5) Radius meaning  
Radius=0 → one dominant node controls spread.

### 6) Why 5G vs Non-Conspiracy easier  
Structural difference is huge.

### 7) Disconnected components  
Isolated pockets of spread → misinformation fragments.

### 8) High betweenness  
Bridge influencer → controls flow.

### 9) WICO takeaway  
Network structure is best indicator of misinformation.

### 10) GNN + Graph features  
Graph = behavior, Text = content → strongest detection.

---

# 📁 9. Recommended Repository Structure

```
📁 /5G_Graph/
📁 /Non_Conspiracy_Graph/
📁 /Screenshots/
📁 /Reports/
📁 /Data Samples/

📄 README.md  ← (this file)
```

---

# 🧾 10. Final Notes  
This README is designed to replace:  
- Unified Report  
- Security Report  
- Summary document  
- Explanation for TA  
- Project description  

Everything is consolidated here.

---

# ✅ End of README  
