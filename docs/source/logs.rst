Latest Logs From Latest Build
==============================

Generated On: 2024-12-05 18:18:24 UTC

These are the latest logs generated from your latest build.  

.. tip:: 
   Complete logs from all builds can be found `here on GitHub <https://github.com/167594225-myseneca/cyt160-raspberrypi/blob/main/tml-airflow/logs/logs.txt>`_

.. code-block:: 
  :linenos:

  [INFO 2024-12-05_18:14:56] STEP 1: completed - TML system parameters successfully gathered

  [INFO 2024-12-05_18:15:03] STEP 2: Create topics started

  [INFO 2024-12-05_18:15:21] STEP 2: Completed

  [INFO 2024-12-05_18:15:35] STEP 3: producing data started

  [INFO 2024-12-05_18:15:39] MQTT connection established...

  [INFO 2024-12-05_18:15:42] STEP 4: Preprocessing started

  [INFO 2024-12-05_18:15:45] STEP 4: Preprocessing started

  [INFO 2024-12-05_18:15:52] STEP 5: Machine learning started

  [INFO 2024-12-05_18:15:58] STEP 6: Predictions started

  [INFO 2024-12-05_18:16:01] STEP 7: Visualization started

  [INFO 2024-12-05_18:16:07] STEP 7: /Viperviz/viperviz-linux-amd64 0.0.0.0 9005

  [INFO 2024-12-05_18:16:22] STEP 9: Success starting Qdrant.  Here is the run command: docker run -d -p 6333:6333 -v $(pwd)/qdrant_storage:/qdrant/storage:z qdrant/qdrant

  [INFO 2024-12-05_18:16:27] STEP 9: Starting privateGPT

  [INFO 2024-12-05_18:16:29] STEP 8: Starting docker push for: jonalearning/cybersecuritywithprivategpt-64f6-amd64

  [INFO 2024-12-05_18:16:48] STEP 9: Success starting privateGPT.  Here is the run command: docker run -d -p 8001:8001 --net=host --env PORT=8001 --env GPU=0 --env COLLECTION=tml --env WEB_CONCURRENCY=1 --env CUDA_VISIBLE_DEVICES=0 maadsdocker/tml-privategpt-no-gpu-amd64

  [INFO 2024-12-05_18:17:07] STEP 8: Docker Container created.  Will push it now.  Here is the commit command: docker commit 682ead5b54fc jonalearning/cybersecuritywithprivategpt-64f6-amd64 - message=0

  [INFO 2024-12-05_18:18:01] STEP 8: Successfully ran Docker push: docker push jonalearning/cybersecuritywithprivategpt-64f6-amd64 - message=0

  [INFO 2024-12-05_18:18:24] STEP 10: Started to build the documentation

  [INFO 2024-12-05_18:18:25] STEP 10: Documentation successfully built on GitHub..Readthedocs build in process and should complete in few seconds


