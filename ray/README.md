To build the package:

export IBM_POWERAI_LICENSE_ACCEPT=yes
conda build . -c powerai -c https://public.dhe.ibm.com/ibmdl/export/pub/software/server/ibm-ai/conda/
