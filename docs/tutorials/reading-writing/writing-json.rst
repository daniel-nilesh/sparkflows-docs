Saving as JSON Files
=====================

Fire Insights enables you to write your DataFrame to JSON Files.


Workflow for writing as JSON files
----------------------


.. figure:: ../../_assets/tutorials/read-write/writing-json/1.PNG
   :alt: JSONWorkflow
   :width: 100%
   

Reading From Dataset
----------------------

Node ``TransactionDataset`` creates DataFrame of your dataset named 'Transaction Dataset' by reading data from HDFS, HIVE etc. which have been defined earlier in Fire by using the Dataset feature. As a user you just have to select the Dataset of your interest and configure the details as shown below.


.. figure:: ../../_assets/tutorials/read-write/writing-json/5.PNG
   :alt: NodeDatasetStructured
   :width: 100%

Processor output
----------------

.. figure:: ../../_assets/tutorials/read-write/writing-json/2.PNG
   :alt: NodeDatasetStructured
   :width: 100%

SaveJSON Processor Configuration
--------------------


Node ``SaveJSON`` saves DataFrame into the specified path in JSON Format. When running on Hadoop, JSON files gets saved into HDFS.

   
.. figure:: ../../_assets/tutorials/read-write/writing-json/3.PNG
   :alt: JSONWorkflow
   :width: 100%

Once the workflow is executed successfully the json file will be saved to specified location.

.. figure:: ../../_assets/tutorials/read-write/writing-json/4.PNG
   :alt: JSONWorkflow
   :width: 100%
