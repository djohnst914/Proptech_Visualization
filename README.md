# Proptech Visualization - Module 6 Challenge
Proptech is the application of technology to real-estate markets, an innovative domain in the fintech industry. For the week 6 challenge, I was tasked with using newly learned data visualization skills. These skills include aggregation, interactive visualizations, and geospatial analysis, to find properties in the San Francisco real estate market that are viable investment opportunities. 

---

## *Technologies*

- **Programming Language:** Python
- **Libraries:** Pandas, hvPlot, pathlib, warnings
- **Framework:** JupyterLab, Python
- **Operating Systems:** Mac OS, Microsoft Windows

---

## *Installation Guide*

**First things first:**
If you don't have Python, Jupyter Lab, or Anaconda installed on your operating system ..

-**[Install Python](https://www.python.org/downloads/)**

-**[Install JupyterLab](https://jupyter.org/install)**

-**[Install Anaconda](https://docs.anaconda.com/free/anaconda/install/index.html)**

Do you have the PyViz ecosystem installed? If you are asking yourself what that is, the answer is most likely no and is totally okay! Proceed to follow the steps below ..

1. In your terminal, activate a default or preferred development environment before installing the PyViz ecosystem. In my case I use:
    
        conda activate dev
2. Install the PyViz packages by using the conda install command as follows:
    
        conda install -c pyviz hvplot geoviews
3. Confirm the installation of all the PyViz packages by running the following commands:

        conda list hvplot
        conda list geoviews
- You should see the following in your terminal after executing the 'conda list' commands: ![Screenshot 2023-04-24 at 2 50 43 PM](https://user-images.githubusercontent.com/123714457/234125164-7418215e-cc18-4670-95c6-d913da28800e.png)
- Note ~ Make sure to use hvPlot version 0.7.0 or later!
---

## *Usage*

- **IMPORTANT:** Before running Jupyter Lab, ensure your dev environment is activated in your terminal, otherwise the geoviews interactive plot towards the end of the app may not display. I gave an example near the top of the installation section. 
- With your mouse navigate near the top of the tab, select 'Kernel', then inside Kernel you'll select 'Restart Kernel and Run All Cells...' This will automatically run the whole program for you start to finish. FYI, it may take a few minutes for everything to load!
<img width="400" alt="Screenshot 2023-04-17 at 2 53 35 PM" src="https://user-images.githubusercontent.com/123714457/232619135-6b2f77be-d543-4a59-a4ad-6e62b2113c6c.png">
- Once the jupyter notebook has fully loaded after running all cells, there are a few interactive graphs that the user can manipulate to better understand a trend or explore a hypothesis they might have. The graphs are reltaively very user friendly, but if you find yourself having issues interacting with the them .. 

-**[Configuring hvPlot Tools](https://docs.bokeh.org/en/2.4.0/docs/user_guide/tools.html)**

---

## *Credits*
For any questions/concerns, anything at all feel free to contact below
- Dylan Johnston
- Email: dylanhjjohnston@gmail.com


---

## *License*

This software is licensed under the MIT License. See the [LICENSE](https://github.com/djohnst914/Proptech_Visualization/blob/main/LICENSE) file for details.  