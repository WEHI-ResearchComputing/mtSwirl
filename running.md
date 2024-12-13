# Run Instructions

To run on WEHI Milton HPC:

Clone the repo:
```bash
git clone git@github.com:bahlolab/mtSwirl_HPC.git
cd mtSwirl_HPC
```

Edit the input config file, e.g.
```bash
nano input.json
```

Run the pipeline:

```bash
module load miniwdl
miniwdl run mtSwirl/WDL/v2.5_MongoSwirl_Single/fullMitoPipeline_v2_5_Single.wdl --input input.json
```

If the run is successful, the output JSON will be printed to the terminal, listing all output files.
