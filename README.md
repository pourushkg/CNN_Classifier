# CNN classifier project 

## To initialized empty git repository 
git init

## workflow

1. Update config.yaml
2. Update secrets.yaml [Optional]
3. Update params.yaml
4. Update the entity
5. Update the configuration manager in src config.
6. Update the components
7. Update the pipeline
8. Test run pipeline stage
9. run tox for testing your package
10. Update the dvc.yaml
11. run "dvc repro" for running all the stages in pipeline
12. conda activate ./env

## To visualize tensorboard 
tensorboard --logdir=artifacts/prepare_callbacks/tensorboard_log_dir/

## dvc operations 
pip install dvc 
### first we have to initialize dvc 
dvc init 
### to start running the stages 
dvc repro
### how the stages are connected 
dvc dag 



