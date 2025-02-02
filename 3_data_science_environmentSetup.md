### Cond start link : https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html
### Cond Latest link: https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html
### Get Ready computer for ML link : https://www.mrdbourke.com/get-your-computer-ready-for-machine-learning-using-anaconda-miniconda-and-conda/
### Mini Conda doc link : https://docs.anaconda.com/miniconda/
# Conda Cheat Seet : 
[3.4 conda-cheatsheet.pdf](https://github.com/user-attachments/files/18631227/3.4.conda-cheatsheet.pdf)

![image](https://github.com/user-attachments/assets/4e63ed27-dc50-461e-96f1-cbd3cdb19ee0)
![image](https://github.com/user-attachments/assets/1e326045-34cf-47bc-a2ad-0c07ecdfe80a)
![image](https://github.com/user-attachments/assets/8f265e70-c793-431d-9a2d-153ebf25a851)
#### MiniConda Download link : https://docs.anaconda.com/miniconda/install/
### Create the work environment : 
#### Open the anaconda Prompt : 
```
mkdir sample_project
conda create --prefix ./env pandas numpy matplotlib scikit-learn

```

#### Activate or Deactivate : 
![image](https://github.com/user-attachments/assets/f17f4e0c-4386-4d5e-8f40-d521d98d4ac4)

#### Install Jupyter NoteBook :
```
conda install jupyter
```
## Linux Environment setup : 
[Uploading 9. Linux Environment Setup.html…]()<p>If you're using Linux, not to worry, you can get started with Miniconda too!</p><p>The following articles will guide you through downloading Miniconda and creating an environment.</p><p>Once you've got Miniconda and created an environment with Conda, you'll be able to follow the same steps as in the macOS&nbsp;videos and the rest of the course.</p><p>Step 1: Follow the Miniconda download steps in this article: <a href="https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html" rel="noopener noreferrer" target="_blank">https://docs.conda.io/projects/conda/en/latest/user-guide/install/linux.html</a></p><p>Step 2: Follow the getting started with Conda steps in this article: <a href="https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html" rel="noopener noreferrer" target="_blank">https://docs.conda.io/projects/conda/en/latest/user-guide/getting-started.html</a></p><p>Step 3: Watch and follow the Mac Environment Setup and Mac Environment Setup 2 videos</p><p>Step 4:&nbsp;Continue with the course</p>

## Sharing conda Environment : 
[Uploading 10. Sharing your Conda Environment.htm<p>There may come a time where you want to share the contents of your Conda environment.</p><p>This could be to share a project workflow with a colleague or with someone else who's trying to set up their system to have access to the same tools as yours.</p><p>There a couple of ways to do this:</p><p>1. Share your entire project folder (including the environment folder containing all of your Conda packages).</p><p>2. Share a <code>.yml</code> (pronounced YAM-L) file of your Conda environment.</p><p>The benefit of 1 is it's a very simple setup, share the folder, activate the environment, run the code. However, an environment folder can be quite a large file to share.</p><p>That's where 2 comes in. A <code>.yml</code> is basically a text file with instructions to tell Conda how to set up an environment.</p><p>For example, to export the environment we created earlier at <code>/Users/daniel/Desktop/project_1/env</code> as a YAML file called <code>environment.yml</code> we can use the command:</p><p><code>conda env export --prefix /Users/daniel/Desktop/project_1/env &gt; environment.yml</code> </p><p>After running the export command, we can see our new <code>.yml</code> file stored as <code>environment.yml</code>.</p><p>A sample <code>.yml</code> file might look like the following:</p><pre class="prettyprint linenums">name: my_ml_env
dependencies:
  - numpy
  - pandas
  - scikit-learn
  - jupyter
  - matplotlib</pre><p>Of course, your actual file will depend on the packages you've installed in your environment.</p><p>For more on sharing an environment, check out the <a href="https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#sharing-an-environment" rel="noopener noreferrer" target="_blank">Conda documentation on sharing environments</a>.</p><p>Finally, to create an environment called <code>env_from_file</code> from a <code>.yml</code> file called <code>environment.yml</code>, you can run the command:</p><p><code>conda env create --file environment.yml --name env_from_file</code></p><p>For more on creating an environment from a <code>.yml</code> file, check out the <a href="https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file" rel="noopener noreferrer" target="_blank">Conda documentation on creating an environment from a .yml file</a>.</p><p><br></p><p>PS Thank you to Konstantin for pointing this out.</p>l…]()

## Conda doc on share : 
[Uploading 10.1 Conda documentation on sharing an environment.html…]()<script type="text/javascript">window.location = "https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#sharing-an-environment";</script>
