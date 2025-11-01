# How to Set Up Jupyter AI Locally?

This guide describes the steps to set up  <a href="https://github.com/jupyterlab/jupyter-ai" target="_blank">Jupyter AI</a> locally and run the course notebooks on your machine.

## Installing Jupyter AI

This course uses the beta version of Jupyter AI v3, as Jupyter AI v3 is not yet officially released. To install the beta version, run this command in your terminal:

`pip install "jupyter-ai>=3.0.0b7,<3.1"`

Once installation is complete, navigate to your working directory and launch JupyterLab by typing `jupyter lab`. You should now see the chat bubble in the left sidebar.

## Setting Up the Model Provider in JupyterLab

Before you can start interacting with Jupyter AI, you need to configure the model provider and API key:

- Click **Settings** in the top menu bar
- Select **AI Settings** from the drop-down menu
- Under `Chat model`, select your preferred model (this course uses `openai/gpt-5-chat-latest`) and then click on the button `Update Chat Model`
- Under `Secrets and API keys`, enter your API key
  
## Accessing Course Notebooks

You can download the notebook of each exercise by clicking on **File** in the top menu bar and then select  **Download** from the drop-down menu. Or you can access them at this repo.

- You can find the dependencies in this requirements file.
- For the third notebook, you can get the Serper API key by signing up for a free account at <a href="https://serper.dev/" target="_blank">serper.dev</a>

## Jupyter AI Additional Feature - Jupyter AI Personas

In the course, you mainly interacted with Jupyternaut, this is the default AI Persona. In the current beta version, the AI persona does not come with any additional tools to read, edit or search for files. These features are currently being developed and will make the default AI persona more powerful.

If you want, you can also create your own custom AI persona and equip it with the tools you want. You can read more about AI personas <a href="https://jupyter-ai.readthedocs.io/en/v3/developers/entry_points_api/personas_group.html" target="_blank">here</a>