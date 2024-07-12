# Optimizing and Compiling Neural Networks for RISC-V Multi-Core Processors

ACACES Course 2024 - Politecnico di Torino

**Authors**: Alessio Burrello, Daniele Jahier Pagliari

## Setup Instructions for Session #1

The ideal environment for running the Python notebooks (for the first Hands-on Session) is a local instance of Jupyter Lab. However, you will need a GPU to run all steps in a reasonable time.

### Instructions for Local Jupyter Lab

Clone the github repository from the command line:

```
git clone git@github.com:eml-eda/acaces-ocnn.git
```

Move into the cloned folder:

```
cd acaces-ocnn
```

Then, create a virtual environment to install packages locally:

```
python -m venv ./acaces_venv
```

And activate it:

```
source acaces_venv/bin/activate
```

Alternatively, you can use Conda as well if you prefer. Lastly, install the required packages with pip:

```
pip install -r requirements.txt
```

You are now ready to start the Jupyter Lab session. If you're running locally, this command should suffice:

```
jupyter lab
```

If you are in a remote machine, you may want to run this instead (where any port would work as long as it is not blocked by your firewall):

```
jupyter lab --ip='*' --port=58080 --no-browser
```

In the local scenario, a new browser window should popup automatically with the Jupyter Lab session. In the remote case, instead, you will see instructions in the terminal that suggest to access the server by opening a URL that looks like this:

```
http://localhost:58080/lab?token=<LONG_STRING>
```

Simply take that URL and paste it in your browser, replacing `localhost` with the IP or hostname of the remote server. You should now see the Jupyter Lab Interface. Simply open the first notebook `I_SuperNet.ipynb` and follow the instructions.

For the last hands_on, you need to download and import the following VM:
https://www.dropbox.com/scl/fo/x02v103y3dyrk340khgir/AONLAM_ihyZQr_Dg6ipimqw?rlkey=1fhhbji4e6syc4iu8ha9q8uux&dl=0

You need to execute the notebook internally to the VM.