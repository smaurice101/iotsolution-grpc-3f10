[--solutionname--] Details
============================

Generated On: --datetime-- UTC

TML Solution DAG Parameters' Details: User Chosen Parametets
----------------------------

STEP 1: Get TML Core Params: `tml_system_step_1_getparams_dag <--step1url-->`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. list-table::

   * - **User Parameter**
     - **Chosen Value**
   * - solutionname
     - --solutionname--
   * - solutiontitle
     - --solutiontitle--
   * - solutiondescription
     - --solutiondescription--
   * - brokerhost
     - --brokerhost--
   * - brokerport
     - --brokerport--
   * - cloudusername
     - --cloudusername--
   * - ingestdatamethod
     - --ingestdatamethod--
 
STEP 2: Create Kafka Topics: `tml_system_step_2_kafka_createtopic_dag <--step2url-->`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. list-table::

   * - **User Parameter**
     - **Chosen Value**
   * - companyname
     - --companyname--
   * - myname
     - --myname--
   * - myemail
     - --myemail--
   * - mylocation
     - --mylocation--
   * - replication
     - --replication--
   * - numpartitions
     - --numpartitions--
   * - enabletls
     - --enabletls--
   * - microserviceid
     - --microserviceid--
   * - raw_data_topic
     - --raw_data_topic--
   * - preprocess_data_topic
     - --preprocess_data_topic--
   * - ml_data_topic
     - --ml_data_topic--
   * - prediction_data_topic
     - --prediction_data_topic--

STEP 3: `Produce to Kafka Topics <--step3url-->`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. list-table::

   * - **User Parameter**
     - **Chosen Value**
   * - PRODUCETYPE
     - --PRODUCETYPE--
   * - inputfile
     - --inputfile--
   * - TOPIC
     - --TOPIC--
   * - PORT
     - --PORT--
   * - IDENTIFIER
     - --IDENTIFIER--
   * - HTTPADDR
     - --HTTPADDR--
   * - FROMHOST
     - --FROMHOST--
   * - TOHOST
     - --TOHOST--
   * - CLIENTPORT
     - --CLIENTPORT--
   * - TSS_CLIENTPORT
     - --TSSCLIENTPORT--
   * - TML_CLIENTPORT
     - --TMLCLIENTPORT--
   * - docfolder
     - --docfolderprocess--
   * - doctopic
     - --doctopic--
   * - chunks
     - --chunks--
   * - docingestinterval
     - --docingestinterval--

STEP 4: Preprocesing Data: `tml-system-step-4-kafka-preprocess-dag <--step4url-->`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. list-table::

   * - **User Parameter**
     - **Chosen Value**
   * - raw_data_topic
     - --raw_data_topic--
   * - preprocess_data_topic
     - --preprocess_data_topic--
   * - preprocessconditions
     - --preprocessconditions--
   * - delay
     - --delay--
   * - maxrows
     - --maxrows--
   * - array
     - --array--
   * - saveasarray
     - --saveasarray--
   * - topicid
     - --topicid--
   * - rawdataoutput
     - --rawdataoutput--
   * - asynctimeout
     - --asynctimeout--
   * - timedelay
     - --timedelay--
   * - preprocesstypes
     - --preprocesstypes--
   * - pathtotmlattrs
     - --pathtotmlattrs--
   * - identifier
     - --identifier--
   * - jsoncriteria
     - --jsoncriteria--

STEP 4a: Preprocesing Data: `tml-system-step-4a-kafka-preprocess-dag <--step4aurl-->`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. list-table::

   * - **User Parameter**
     - **Chosen Value**
   * - raw_data_topic
     - --raw_data_topic1--
   * - preprocess_data_topic
     - --preprocess_data_topic1--
   * - preprocessconditions
     - --preprocessconditions1--
   * - delay
     - --delay1--
   * - maxrows
     - --maxrows1--
   * - array
     - --array1--
   * - saveasarray
     - --saveasarray1--
   * - topicid
     - --topicid1--
   * - rawdataoutput
     - --rawdataoutput1--
   * - asynctimeout
     - --asynctimeout1--
   * - timedelay
     - --timedelay1--
   * - preprocesstypes
     - --preprocesstypes1--
   * - pathtotmlattrs
     - --pathtotmlattrs1--
   * - identifier
     - --identifier1--
   * - jsoncriteria
     - --jsoncriteria1--

STEP 4b: Preprocesing Data: `tml-system-step-4b-kafka-preprocess-dag <--step4burl-->`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. list-table::

   * - **User Parameter**
     - **Chosen Value**
   * - raw_data_topic
     - --raw_data_topic2--
   * - preprocess_data_topic
     - --preprocess_data_topic2--
   * - preprocessconditions
     - --preprocessconditions2--
   * - delay
     - --delay2--
   * - maxrows
     - --maxrows2--
   * - array
     - --array2--
   * - saveasarray
     - --saveasarray2--
   * - topicid
     - --topicid2--
   * - rawdataoutput
     - --rawdataoutput2--
   * - asynctimeout
     - --asynctimeout2--
   * - timedelay
     - --timedelay2--
   * - preprocesstypes
     - --preprocesstypes2--
   * - pathtotmlattrs
     - --pathtotmlattrs2--
   * - identifier
     - --identifier2--
   * - jsoncriteria
     - --jsoncriteria2--

STEP 4c: Preprocesing Data: `tml-system-step-4c-kafka-preprocess-dag  <--step4curl-->`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. list-table::

   * - **User Parameter**
     - **Chosen Value**
   * - raw_data_topic
     - --raw_data_topic3--
   * - preprocess_data_topic
     - --preprocess_data_topic3--
   * - delay
     - --delay3--
   * - maxrows
     - --maxrows3--
   * - array
     - --array3--
   * - saveasarray
     - --saveasarray3--
   * - topicid
     - --topicid3--
   * - rawdataoutput
     - --rawdataoutput3--
   * - asynctimeout
     - --asynctimeout3--
   * - timedelay
     - --timedelay3--
   * - searchterms
     - --rtmssearchterms--
   * - rtmsstream
     - --rtmsstream--
   * - identifier
     - --identifier3--
   * - rememberpastwindows
     - --rememberpastwindows--
   * - patternwindowthreshold
     - --patternwindowthreshold--
   * - localsearchtermfolder
     - --localsearchtermfolder--
   * - localsearchtermfolderinterval
     - --localsearchtermfolderinterval--
   * - rtmsscorethreshold
     - --rtmsscorethreshold--
   * - rtmsscorethresholdtopic
     - --rtmsscorethresholdtopic--
   * - attackscorethreshold
     - --attackscorethreshold--
   * - attackscorethresholdtopic
     - --attackscorethresholdtopic--
   * - patternscorethreshold
     - --patternscorethreshold--
   * - patternscorethresholdtopic
     - --patternscorethresholdtopic--
   * - rtmsfoldername
     - --rtmsfoldername--
   * - rtmsmaxwindows
     - --rtmsmaxwindows--
   * - RTMS Output Github Link
     - `Output Data URL <--rtmsoutputurl-->`_

STEP 5: Entity Based Machine Learning : `tml-system-step-5-kafka-machine-learning-dag <--step5url-->`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. list-table::

   * - **User Parameter**
     - **Chosen Value**
   * - preprocess_data_topic
     - --preprocess_data_topic--
   * - ml_data_topic
     - --ml_data_topic--
   * - modelruns
     - --modelruns--
   * - offset
     - --offset--
   * - islogistic
     - --islogistic--
   * - networktimeout
     - --networktimeout--
   * - modelsearchtuner
     - --modelsearchtuner--
   * - processlogic
     - --processlogic--
   * - dependentvariable
     - --dependentvariable--
   * - independentvariables
     - --independentvariables--
   * - rollbackoffsets
     - --rollbackoffsets--
   * - topicid
     - --topicid--
   * - consumefrom
     - --consumefrom--
   * - fullpathtotrainingdata
     - --fullpathtotrainingdata--
   * - transformtype
     - --transformtype--
   * - sendcoefto
     - --sendcoefto--
   * - coeftoprocess
     - --coeftoprocess--
   * - coefsubtopicnames
     - --coefsubtopicnames--
   * - ML Output Github Link
     - `Output Data URL <--mloutputurl-->`_

STEP 6: Entity Based Predictions: `tml-system-step-6-kafka-predictions-dag <--step6url-->`_
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. list-table::

   * - **User Parameter**
     - **Chosen Value**
   * - preprocess_data_topic
     - --preprocess_data_topic--
   * - ml_prediction_topic
     - --ml_prediction_topic--
   * - streamstojoin
     - --streamstojoin--
   * - inputdata
     - --inputdata--
   * - consumefrom
     - --consumefrom2--
   * - offset
     - --offset--
   * - delay
     - --delay--
   * - usedeploy
     - --usedeploy--
   * - networktimeout
     - --networktimeout--
   * - maxrows
     - --maxrows--
   * - topicid
     - --topicid--
   * - pathtoalgos
     - --pathtoalgos--

STEP 7: Real-Time Visualization: `tml-system-step-7-kafka-visualization-dag <--step7url-->`_
^^^^^^^^^^^^^^^^^^^^^

.. list-table::

   * - **User Parameter**
     - **Chosen Value**
   * - vipervizport
     - --vipervizport--
   * - topic
     - --topic--
   * - dashboardhtml
     - --dashboardhtml--
   * - secure
     - --secure--
   * - offset
     - --offset--
   * - append
     - --append--
   * - chip
     - --chip--
   * - rollbackoffset
     - --rollbackoffset--

STEP 8: `tml_system_step_8_deploy_solution_to_docker_dag <--step8url-->`_
^^^^^^^^^^^^^^^^^^^^^
.. list-table::

   * - **User Parameter**
     - **Chosen Value**
   * - Docker Container
     - --dockercontainer--
   * - Docker Run Command
     - --dockerrun--

STEP 9: `tml_system_step_9_privategpt_qdrant_dag <--step9url-->`_
^^^^^^^^^^^^^^^^^^^^^
.. list-table::

   * - **User Parameter**
     - **Chosen Value**
   * - PrivateGPT Container
     - --pgptcontainername--
   * - PrivateGPT Run Command
     - --privategptrun--
   * - Qdrant Container
     - --qdrantcontainer--
   * - Qdrant Run Command
     - --qdrantrun--
   * - Consumefrom
     - --consumefrom--
   * - pgpt_data_topic
     - --pgpt_data_topic--
   * - offset
     - --offset--
   * - rollbackoffset
     - --rollbackoffset--
   * - topicid
     - --topicid--
   * - enabletls
     - --enabletls--
   * - partition
     - --partition--
   * - prompt
     - --prompt--
   * - context
     - --context--
   * - jsonkeytogather
     - --jsonkeytogather--
   * - keyattribute
     - --keyattribute--
   * - keyprocesstype
     - --keyprocesstype--
   * - vectordbcollectionname
     - --vectordbcollectionname--
   * - concurrency
     - --concurrency--
   * - CUDA_VISIBLE_DEVICES
     - --cuda--
   * - pgpthost
     - --pgpthost--
   * - pgptport
     - --pgptport--
   * - hyperbatch
     - --hyperbatch--
   * - docfolder
     - --docfolder--
   * - docfolderingestinterval
     - --docfolderingestinterval--
   * - useidentifierinprompt
     - --useidentifierinprompt--
   * - searchterms
     - --searchterms--
   * - streamall
     - --streamall--
   * - temperature
     - --temperature--
   * - vectorsearchtype
     - --vectorsearchtype--
   * - llm
     - --llmmodel--
   * - embedding
     - --embedding--
   * - vectorsize
     - --vectorsize--
   * - contextwindowsize
     - --contextwindowsize--
   * - vectordimension
     - --vectordimension--
   * - mitrejson
     - --mitrejson--

STEP 9b: `tml_system_step_9b_agenticai_dag <--step9burl-->`_
^^^^^^^^^^^^^^^^^^^^^
.. list-table::

   * - **User Parameter**
     - **Chosen Value**
   * - rollbackoffset
     - --agenticai-rollbackoffset--
   * - ollama-model
     - --agenticai-ollama-model--
   * - deletevectordbcount
     - --agenticai-deletevectordbcount--
   * - vectordbpath
     - --agenticai-vectordbpath--
   * - temperature
     - --agenticai-temperature--
   * - topicid
     - --agenticai-topicid--
   * - enabletls
     - --agenticai-enabletls--
   * - partition
     - --agenticai-partition--
   * - vectordbcollectionname
     - --agenticai-vectordbcollectionname--
   * - ollamacontainername
     - --agenticai-ollamacontainername--
   * - mainip
     - --agenticai-mainip--
   * - mainport
     - --agenticai-mainport--
   * - embedding
     - --agenticai-embedding--
   * - agents_topic_prompt
     - --agenticai-agents_topic_prompt--
   * - teamlead_topic
     - --agenticai-teamlead_topic--
   * - teamleadprompt
     - --agenticai-teamleadprompt--
   * - supervisor_topic
     - --agenticai-supervisor_topic--
   * - supervisorprompt
     - --agenticai-supervisorprompt--
   * - agenttoolfunctions
     - --agenticai-agenttoolfunctions--
   * - agent_team_supervisor_topic
     - --agenticai-agent_team_supervisor_topic--
   * - concurrency
     - --agenticai-concurrency--
   * - CUDA_VISIBLE_DEVICES
     - --agenticai-cuda--

STEP 10: `tml_system_step_10_documentation_dag <--step10url-->`_
^^^^^^^^^^^^^^^^^^^^^
.. list-table::

   * - **User Parameter**
     - **Chosen Value**
   * - Solution Documentation URL
     - --readthedocs--
