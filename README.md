# swot_data_stats

## coverage_cycles_passes

If you care to use `papermill` (to run ipynbs from python cli) then remember to install it along with other dependencies:
```
python -m pip install pandas tqdm papermill
```
pandas is the only absolute requirement. Easy enough to adapt. This is how you run it from python cli/shell:

```shell
python -m papermill coverage_cycles_passes/coverage_cycles_passes.ipynb tests/<dataset>.ipynb \
    -p dataset <dataset> \
    -p token <token>
```
