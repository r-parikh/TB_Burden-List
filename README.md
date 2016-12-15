# TB_Burden-List
Tuberculosis Burden Data of vulnerable countries (15 years average)

Docker Hub repository link for Docker images:

https://hub.docker.com/r/rutulparikh/tb-wf/

First image, tagged as nigeria is for a specific country Nigeria
and
Second image, tagged as parameterized is a general image for getting data of various countries.


# How to get the results?
 Install and initialize Docker CLI
 Run the following command without for Nigeria (specific)

<pre>docker pull rutulparikh/tb-wf:nigeria</pre>

 The command will pull the image from docker.io, to get the result

<pre>docker run rutulparikh/tb-wf:nigeria</pre>

 Run the following command for general (non-specific)

<pre>docker pull rutulparikh/tb-wf:parametrized</pre>

 It will pull the image from docker.io, to get the result for specific country

<pre>docker run rutulparikh/tb-wf:parameterized country=Kenya</pre>

 This will get you the result of Kenya TB Burden data. You can put other countries in place of Kenya.

 Dockerfile, startup.xml and run_workflow.py and tbdata.vt can be found in this repository.
