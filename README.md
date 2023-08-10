# contrails_model_group
Repo with code from model group of Opencampus course

group members: 
Jan Waller
Desmond Hammond
Albers Sandritter
Julian Lohmann
Fynn Junge
Wang

### Folder 1
Models working on Ash dataset and timestep 5

### Folder 2
Models working on created masks with all 8 timesteps

### Folder 3
Post-Processing Exploration

### Folder 4
Lightning workflow to run single-band (-single-timestep)  experiment. (Also extention to arbitrary band-timestep combinations included in the code.)

### Folder 5
Training a model for every timestep,and then ensembling them in a Stack. Each pretrained model gets as input the ash-colour version of the according timestep and needs to predict the mask at timestep 5.
Afterwards another model is trained on the outputs of the pretrained(frozen) models to predict the final mask.
