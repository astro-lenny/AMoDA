Each folder contains the exercises for this course in ipython notebook (ipynb) format. You can download these and run them using Jupyter notebook.
Within Jupyter, you can upload the notebooks downloaded from these pages. I recommend organising them into folders, as there may be several files per exercise. Then you can start working on the problems.
If you want to download the notebook, you can choose "File" > "Download as" > "Notebook (.ipynb)".

If working remotely, below is a one-liner for connecting to the PI linux cluser and running Jupyter notebook in a way that lets you connect from your own web browser.
More detailed instructions are available at the following links:
https://codimd.web.cern.ch/p/RO7yjoBex (slides from the first tutorial)
https://confluence.team.uni-bonn.de/display/PHYIT/Jupyter+Notebooks+via+SSH (if you are connected to the Uni VPN)

export JPYPORT=$(($RANDOM%61000+32768)); ssh -t -L ${JPYPORT}:localhost:${JPYPORT} <UNI-ID>@desktop.physik.uni-bonn.de "jupyter notebook --no-browser --port=${JPYPORT}"

Remember to replace <UNI-ID> with your Uni ID (i.e. your username on the cluser). 

In the terminal output, there will be a link that looks like http://localhost:<port>/?token=<token>. Follow this with your web browser to open Jupyter.


