# Deep-Learning-With-Pytorch

### Code and material for the Deep Learning with Pytorch Course

## Exercises' Topics

## Online Environments And Compute Resources

1. [Colab](https://colab.research.google.com/)
4 hour GPU sessions for free limited based on overall demand.

2. [Kaggle](https://www.kaggle.com/)
30 gpu hours a week and 20 TPU hours a week. More than enough to do you course projects.

3. [Lightning AI](https://lightning.ai/)
22 gpu hours a month.

## Environment

The course python version is 12. You can use the online Environments mentioned above but you can also setup a local environment if you want to run models locally.
In the requirements.txt file you will find all the necessary libraries to run the notebooks.
You can install them with pip.

      pip install requirements.txt

[Conda](https://docs.conda.io/projects/conda/en/latest/index.html#) is recommended for managing you environment.

1. To create an environment:

    ```
      conda create --name <my-env> python=3.12
    ```

   Replace ``<my-env>`` with the name of your environment.

2. When conda asks you to proceed, type ``y``:

      ``proceed ([y]/n)?``

   This creates the myenv environment in ``/envs/``. No
   packages will be installed in this environment.

3. Then you need to activate your environment :

    ```
      conda activate <my-env>
    ```

4. Then you can install the necessary libraries :

    ```
      pip install -r requirements.txt
    ```
