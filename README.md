# code-detection
The official implemention of "Uncovering LLM-Generated Code: A Zero-Shot Synthetic Code Detector via Code Rewriting".

## Source Code
We refactored the implementation into a Jupyter notebook format, shown in ```nbs``` dirs.

## datas, model checkpoints
Datas and Model checkpoints stored at: https://drive.google.com/file/d/1UtRPTw_w7D1TKuYIrEVtTzBNUj-b2O4-/view?usp=sharing


## nbs
**Some key Jupyter Notebooks.**

```gather_all_baseline.ipynb``` 

Collect the results of statistical baselines in a single run.

```apps_dataset_prepro.ipynb, apps_process.ipynb, comments_remove.ipynb, data_collection.ipynb```

Operations on the dataset.

```simcse_data.ipynb, simcse_inference.ipynb```

Operations for SimCSE (self-supervised contrastive learning).


```impact_code_correctness.ipynb```

Experimental study on code correctness.

```impact_of_m.ipynb```

Experimental study on rewriting number m.

```vary_codelength.ipynb```

Experimental study on the impact of code length.

```vary_decoding_temperature.ipynb```

Experimental study on the impact of decoding temperature.

```vary_identifier_replace.ipynb```

Experimental study on the impact of Revised Synthetic Code.

```vllm_results_gather.ipynb```
Summarize the experimental results of our method.
