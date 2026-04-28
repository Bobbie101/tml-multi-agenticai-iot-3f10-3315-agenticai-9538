Latest Logs From Latest Build
==============================

Generated On: 2026-04-28 07:00:00 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/Bobbie101/raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2026-04-28_06:58:57] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2026-04-28_06:58:59] STEP 2: Create topics started

  [INFO 2026-04-28_06:59:07] STEP 2: Completed

  [INFO 2026-04-28_06:59:11] STEP 3: producing data started

  [INFO 2026-04-28_06:59:12] STEP 4: Preprocessing started

  [INFO 2026-04-28_06:59:13] STEP 4: Preprocessing started

  [INFO 2026-04-28_06:59:14] STEP 7: Visualization started

  [INFO 2026-04-28_06:59:19] STEP 7: /Viperviz/viperviz-linux-arm64 0.0.0.0 6060

  [INFO 2026-04-28_06:59:22] STEP 9b: Starting ollama server

  [INFO 2026-04-28_06:59:25] STEP 3: reading local file..successfully

  [INFO 2026-04-28_06:59:32] STEP 9b: Ollama container.  Here is the run command: docker run -d -p 11434:11434 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z -v /mnt/c/maads/tml-airflow/rawdata/ollama:/root/.ollama:z --env OLLAMA_LOAD_TIMEOUT=30m0s --env PORT=11434 --env TSS=0 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env LLAMAMODEL="phi3:3.8b && phi3:3.8b && llama3.2:3b" --env mainembedding="nomic-embed-text" --env OLLAMASERVERPORT="http://127.0.0.1:11434" maadsdocker/tml-privategpt-with-gpu-nvidia-amd64-llama3-tools, v=125

  [INFO 2026-04-28_06:59:32] STEP 9b: Success starting Agentic AI.  Here is the run command: docker run -d -p 11434:11434 --net=host --gpus all -v /var/run/docker.sock:/var/run/docker.sock:z -v /mnt/c/maads/tml-airflow/rawdata/ollama:/root/.ollama:z --env OLLAMA_LOAD_TIMEOUT=30m0s --env PORT=11434 --env TSS=0 --env GPU=1 --env COLLECTION=tml-llm-model-v2 --env WEB_CONCURRENCY=2 --env CUDA_VISIBLE_DEVICES=0 --env TOKENIZERS_PARALLELISM=false --env temperature=0.1 --env LLAMAMODEL="phi3:3.8b && phi3:3.8b && llama3.2:3b" --env mainembedding="nomic-embed-text" --env OLLAMASERVERPORT="http://127.0.0.1:11434" maadsdocker/tml-privategpt-with-gpu-nvidia-amd64-llama3-tools

  [INFO 2026-04-28_06:59:57] STEP 8: Starting docker push for: Bobbie101/tml-multi-agenticai-iot-3f10-3315-agenticai-9538-arm64

  [INFO 2026-04-28_07:00:00] STEP 10: Started to build the documentation

  [INFO 2026-04-28_07:00:01] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


