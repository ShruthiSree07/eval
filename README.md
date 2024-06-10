Local Eval :
```
d3x dataset evaluate --dataset bertcontracts --config /home/sireesha-mandava/newconfigs/eval-llama-llama.yaml --semantic_similarity_evaluator.rag_configuration=/home/sireesha-mandava/newconfigs/rag-bgeemb-llmsum-nosllm.yaml

```

Sky Eval:
```
d3x dataset evaluate --dataset bertcontracts --config /home/data/sm/eval-llama-llama.yaml --semantic_similarity_evaluator.rag_configuration=/home/data/sm/rag-bgeemb-llmsum-nosllm.yaml -s --dkubex-url "https://a2816b1468a814386b21a27e9caa6e1d-1b4aacb928a87570.elb.us-west-2.amazonaws.com/" --dkubex-apikey="eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyIjoic2lyZWVzaGEtbWFuZGF2YSIsInR5cGUiOiJ1c2VyIiwiaWQiOiI0NmU4MDExMC1jY2RmLTRjMDMtODNmYS1lNTJmZDY0YjE4YjgifQ.ZZ89itfeRJPy7hYPWizwPHUTIGgyH6WjqIdnx1-41fA"
```

Note: no serving token for sky deployments
