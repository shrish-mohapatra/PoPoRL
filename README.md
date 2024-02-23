# COMP 4900G Project
> Multi agent reinforcement learning project

## Setup
```shell
# Create venv
python -m venv venv

# Activate venv
venv/Scripts/activate  # for windows

# Install requirements
pip install -r requirements.txt

# Create experiment folder
mkdir sandbox/experiments

# Run the notebook
test-benchmarl.ipynb

# If using csv logger use pt_file_experiment.py to create gif
```

## Resources
- [VMAS github](https://github.com/proroklab/VectorizedMultiAgentSimulator)
- [BenchMARL github](https://github.com/facebookresearch/BenchMARL)
- [BenchMARL + VMAS colab example](https://colab.research.google.com/github/facebookresearch/BenchMARL/blob/main/notebooks/run.ipynb#scrollTo=4f32b88e)