# Notebooks

> **Note**: Parts of this README was generated with GitHub Copilot, like the overall outline and common commands, best practices

Using this repo as a learning tool for dense topics like math and data science, while also learning how to work with Jupyter Notebooks. 

## Overview
This is serving as a sort of "cheat sheet" for me when I'm working in this repo. Notebooks will largely be oriented around topics that interest me like math and ml engineering.

## Notebook Philosophy tips

Each notebook follows these principles:
1. **Theory First**: Explain the concept with mathematical foundations where applicable
2. **Visual Learning**: Include plots, diagrams, and visualizations
3. **Hands-on Practice**: Implement concepts from scratch to build intuition
4. **Real Examples**: Use practical examples and datasets
5. **Progressive Complexity**: Start simple, build to advanced topics

## Getting Started

### Prerequisites
```bash
# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install Jupyter and common dependencies
pip install jupyter numpy pandas matplotlib seaborn scikit-learn
```

### Running Notebooks
```bash
# Start Jupyter Notebook
jupyter notebook

# Or use JupyterLab for a more modern interface
jupyter lab
```

## Best Practices cheat sheet

### Notebook Structure
- Start with a title and overview
- Import all required libraries in the first cell
- Use markdown cells for explanations and LaTeX for equations
- Keep code cells focused and well-commented
- End with conclusions and key takeaways

### Code Quality
- Write clean, readable code
- Add docstrings to custom functions
- Include inline comments for complex logic
- Use descriptive variable names

### Documentation
- Explain the "why" not just the "what"
- Include mathematical notation using LaTeX: `$f(x) = ax^2 + bx + c$`
- Reference sources and further reading materials
- Document assumptions and limitations
