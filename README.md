# wdlviz

**Visualize [WDL](https://openwdl.org/) workflows using [miniwdl](https://github.com/chanzuckerberg/miniwdl) and [Graphviz](https://graphviz.org/)**

```
pip3 install wdlviz
wdlviz https://github.com/broadinstitute/warp/raw/develop/pipelines/skylab/smartseq2_single_sample/SmartSeq2SingleSample.wdl
```

![image](https://github.com/miniwdl-ext/wdlviz/assets/356550/aa2ebe05-a285-493b-adc8-fd7a4b4d1d2e)

See `wdlviz --help` for customization options. For example, add `--input --output` to include all the input & output declarations (often unwieldy, so omitted by default).
