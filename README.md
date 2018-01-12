# CERN-SFT-Warmup-exercise-GSOC-2017

Display live information about a Spark job in a notebook
The objective is to spawn a Spark job and monitor its execution. In addition, the function displays some kind of information about the job in a
Jupyter notebook via JavaScript graphics.
# preparation for this task you will need to:
1) Install Spark on your machine and run some simple test locally.
2) Install Jupyter on your machine and launch a local notebook server.
3) Use d3.js to embedd particular JavaScript graphics.
4) Query the Spark REST API for different types of information about the running job.
  for e.g: No of tasks executed/finished/pending.
The Python function executes a Spark application and monitors it. 

The body of your function launches the Spark job and, while it is running, request some
information to the Spark REST API (for instance, completed and pending tasks). This information
is then converted into a JavaScript display that is automatically refreshed as the Spark job
executes (for example, a progress bar).
