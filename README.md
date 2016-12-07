"# TB_Burden-List
Tuberculosis Burden Data of vulnerable countries (15 years average)

Docker Hub repository link for Docker images:

https://hub.docker.com/r/rutulparikh/tb-wf/

First image, tagged as nigeria is for a specific country Nigeria
and
Second image, tagged as parameterized is a general image for getting data of various countries.


# How to get the results?
1. install and initialize Docker CLI
2. run the following command without quotes for Nigeria (specific)

"docker pull rutulparikh/tb-wf:nigeria"

The command will pull the image from docker.io, to get the result

"docker run rutulparikh/tb-wf:nigeria"

3. run the following command for general (non-specific)

"docker pull rutulparikh/tb-wf:parametrized"

It will pull the image from docker.io, to get the result for specific country

"docker run rutulparikh/tb-wf:parameterized country=Kenya"

This will get you the result of Kenya TB Burden data. You can put other countries in place of Kenya.

4. Dockerfile, startup.xml and run_workflow.py and tbdata.vt can be found in this repository.
