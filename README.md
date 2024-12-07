```
LORA fine tune traininer results:

Epoch	Training Loss	Validation Loss	Accuracy
1	No log	0.361943	{'accuracy': 0.877}
2	0.411800	0.554825	{'accuracy': 0.852}
3	0.411800	0.790283	{'accuracy': 0.858}
4	0.188100	0.676550	{'accuracy': 0.876}
5	0.188100	0.902954	{'accuracy': 0.869}
6	0.052100	1.006464	{'accuracy': 0.865}
7	0.052100	1.026726	{'accuracy': 0.874}
8	0.018000	1.103825	{'accuracy': 0.874}
9	0.018000	1.127349	{'accuracy': 0.876}
10	0.005000	1.131871	{'accuracy': 0.879}



Based on the results from training, we can observe training loss is dropping, validation loss is rising and accuracy has minor improment.
We may assume that overfitting happened here since we directly jumped to LORA fine-tuning.
Instead, perhaps first try out transfer learning of the model to compare the result beofre moving to LORA to fine-tune even furter
```