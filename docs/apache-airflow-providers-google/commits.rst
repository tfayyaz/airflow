
 .. Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

 ..   http://www.apache.org/licenses/LICENSE-2.0

 .. Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.


Package apache-airflow-providers-google
------------------------------------------------------

Google services including:

  - `Google Ads <https://ads.google.com/>`__
  - `Google Cloud (GCP) <https://cloud.google.com/>`__
  - `Google Firebase <https://firebase.google.com/>`__
  - `Google LevelDB <https://github.com/google/leveldb/>`__
  - `Google Marketing Platform <https://marketingplatform.google.com/>`__
  - `Google Workspace <https://workspace.google.pl/>`__ (formerly Google Suite)


This is detailed commit list of changes for versions provider package: ``google``.
For high-level changelog, see :doc:`package information including changelog <index>`.



6.4.0
.....

Latest change: 2022-02-08

================================================================================================  ===========  ============================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ============================================================================================
`e97374020 <https://github.com/apache/airflow/commit/e9737402081aa9c9bac748de1d75b387b3b8da42>`_  2022-02-08   ``Create CustomJob and Datasets operators for Vertex AI service (#21253)``
`34d63fabc <https://github.com/apache/airflow/commit/34d63fabc0f2a85df38a78a89f9929e110951d11>`_  2022-02-08   ``Fix BigQueryDataTransferServiceHook.get_transfer_run() request parameter (#21293)``
`6b88d432d <https://github.com/apache/airflow/commit/6b88d432d959df73433528fe3d62194239f13edd>`_  2022-02-06   ``Support to upload file to Google Shared Drive (#21319)``
`1a77bc648 <https://github.com/apache/airflow/commit/1a77bc6481580ab6817267b6e075634caaa025be>`_  2022-02-06   ``:bug: (BigQueryHook) fix compatibility with sqlalchemy engine (#19508)``
`6c3a67d4f <https://github.com/apache/airflow/commit/6c3a67d4fccafe4ab6cd9ec8c7bacf2677f17038>`_  2022-02-05   ``Add documentation for January 2021 providers release (#21257)``
`39e395f98 <https://github.com/apache/airflow/commit/39e395f9816c04ef2f033eb0b4f635fc3018d803>`_  2022-02-04   ``Add more SQL template fields renderers (#21237)``
`e840acf8d <https://github.com/apache/airflow/commit/e840acf8d1840761b72b596ccd4280efece0c974>`_  2022-02-04   ``Fix BigQuery system test (#21320)``
`ddb5246bd <https://github.com/apache/airflow/commit/ddb5246bd1576e2ce6abf8c80c3328d7d71a75ce>`_  2022-02-03   ``Refactor operator links to not create ad hoc TaskInstances (#21285)``
`1d4b709e2 <https://github.com/apache/airflow/commit/1d4b709e20b07c6f0b5d1bab1935e19557df2913>`_  2022-01-28   ``Revert "Create CustomJob and Datasets operators for Vertex AI service (#20077)" (#21203)``
`48d44b885 <https://github.com/apache/airflow/commit/48d44b885b0b205a8a4f8ff864716127476ff7f4>`_  2022-01-28   ``Cloudsql import links fix. (#21199)``
`640c0b676 <https://github.com/apache/airflow/commit/640c0b67631c5f2c8ee866b0726fa7a8a452cd3c>`_  2022-01-28   ``Create CustomJob and Datasets operators for Vertex AI service (#20077)``
`cb7305321 <https://github.com/apache/airflow/commit/cb73053211367e2c2dd76d5279cdc7dc7b190124>`_  2022-01-27   ``Add optional features in providers. (#21074)``
`60aa518eb <https://github.com/apache/airflow/commit/60aa518ebfe8d794ee216c8283cba841d6510189>`_  2022-01-26   ``batch as templated field in DataprocCreateBatchOperator (#20905)``
`623163f16 <https://github.com/apache/airflow/commit/623163f16ad2bbdd47d499e423fd5e37d36a028b>`_  2022-01-25   ``Extend dataproc example dag (#21091)``
`86ef016ea <https://github.com/apache/airflow/commit/86ef016eabd90819163503ef07c0da50373142ad>`_  2022-01-23   ``Make timeout Optional for wait_for_operation (#20981)``
`506efb6fa <https://github.com/apache/airflow/commit/506efb6fa3999ac21a8539e863d81dc684abe52a>`_  2022-01-21   ``Squelch more deprecation warnings (#21003)``
`372849486 <https://github.com/apache/airflow/commit/372849486cd455a4ff4821b01805a442f1a78417>`_  2022-01-21   ``Fix last google provider MyPy errors (#21010)``
`73c0d241d <https://github.com/apache/airflow/commit/73c0d241d804507abc651a365f93d60c543349d5>`_  2022-01-21   ``Remove a few stray ':type's in docs (#21014)``
`602abe839 <https://github.com/apache/airflow/commit/602abe8394fafe7de54df7e73af56de848cdf617>`_  2022-01-20   ``Remove ':type' lines now sphinx-autoapi supports typehints (#20951)``
`b8526abc2 <https://github.com/apache/airflow/commit/b8526abc2c220b1e07eed83694dfee972c2e2609>`_  2022-01-19   ``Add encoding parameter to 'GCSToLocalFilesystemOperator' to fix #20901 (#20919)``
`58452f97d <https://github.com/apache/airflow/commit/58452f97dbcddb4c57a021e9c7fc76139aa9633b>`_  2022-01-03   ``Add hook for integrating with Google Calendar (#20542)``
================================================================================================  ===========  ============================================================================================

6.3.0
.....

Latest change: 2021-12-31

================================================================================================  ===========  =====================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =====================================================================================
`f77417eb0 <https://github.com/apache/airflow/commit/f77417eb0d3f12e4849d80645325c02a48829278>`_  2021-12-31   ``Fix K8S changelog to be PyPI-compatible (#20614)``
`97496ba2b <https://github.com/apache/airflow/commit/97496ba2b41063fa24393c58c5c648a0cdb5a7f8>`_  2021-12-31   ``Update documentation for provider December 2021 release (#20523)``
`a22d5bd07 <https://github.com/apache/airflow/commit/a22d5bd07696d9cafe10a3e246ea9f3a381585ee>`_  2021-12-31   ``Fix mypy errors in Google Cloud provider (#20611)``
`4233ebe5c <https://github.com/apache/airflow/commit/4233ebe5cea4862dbf16c9d7c72c4fdd11db9774>`_  2021-12-31   ``Fix setting of project ID in ''provide_authorized_gcloud'' (#20428)``
`83f8e178b <https://github.com/apache/airflow/commit/83f8e178ba7a3d4ca012c831a5bfc2cade9e812d>`_  2021-12-31   ``Even more typing in operators (template_fields/ext) (#20608)``
`746ee587d <https://github.com/apache/airflow/commit/746ee587da485acdc816129fe71df23e4f024e0b>`_  2021-12-31   ``Delete pods by default in KubernetesPodOperator (#20575)``
`41dbe2c4f <https://github.com/apache/airflow/commit/41dbe2c4fcfe39c7f5fb5a4b8a341561dd7e3cc1>`_  2021-12-30   ``Fix mypy errors in google/cloud/operators/stackdriver (#20601)``
`dda688776 <https://github.com/apache/airflow/commit/dda688776c196eea708abfda0462af6c92809031>`_  2021-12-30   ``Fix Google mlengine MyPy errors (#20569)``
`d56e7b56b <https://github.com/apache/airflow/commit/d56e7b56bb9827daaf8890557147fd10bdf72a7e>`_  2021-12-30   ``Fix template_fields type to have MyPy friendly Sequence type (#20571)``
`bd9e8cef2 <https://github.com/apache/airflow/commit/bd9e8cef2687de0b047003e159fd8f3f08c6c61f>`_  2021-12-30   ``Fix Google Mypy Dataproc errors (#20570)``
`a6e60ce25 <https://github.com/apache/airflow/commit/a6e60ce25d9f3d621a7b4089834ca5e50cd123db>`_  2021-12-30   ``Change download_video parameter to resourceName (#20528)``
`af4a2b024 <https://github.com/apache/airflow/commit/af4a2b0240fbf79a0a6774a9662243050e8fea9c>`_  2021-12-30   ``Fix big query to mssql/mysql transfer issues (#20001)``
`a0821235f <https://github.com/apache/airflow/commit/a0821235fb6877a471973295fe42283ef452abf6>`_  2021-12-30   ``Use typed Context EVERYWHERE (#20565)``
`da88ed194 <https://github.com/apache/airflow/commit/da88ed1943e85850fcdf32c663ec2940c65dbe75>`_  2021-12-29   ``Fix MyPy errors in Google Cloud (again) (#20469)``
`3a480f5ff <https://github.com/apache/airflow/commit/3a480f5ff41c2da4ae4fd6b2289e064ee42048a5>`_  2021-12-29   ``Fix passing the gzip compression parameter on sftp_to_gcs. (#20553)``
`bfd6d45ce <https://github.com/apache/airflow/commit/bfd6d45cecbc7714cea8e2ce5d8920bdb4819887>`_  2021-12-29   ``switch to follow_redirects on httpx.get call in CloudSQL provider (#20239)``
`7d4d38b54 <https://github.com/apache/airflow/commit/7d4d38b546c44287f8a9d09c4fc141cbea736511>`_  2021-12-29   ``avoid deprecation warnings in BigQuery transfer operators (#20502)``
`b7086f981 <https://github.com/apache/airflow/commit/b7086f9815d3856cb4f3ee5bbc78657f19df9d2d>`_  2021-12-28   ``Use Python3.7+ syntax in pyupgrade (#20501)``
`a4622e19f <https://github.com/apache/airflow/commit/a4622e19fa0edc983cb0b29ca6a92969d0cb46fd>`_  2021-12-22   ``Support regional GKE cluster (#18966)``
`2ffdcf4b4 <https://github.com/apache/airflow/commit/2ffdcf4b41158b21e5a08314691d4159dbd44dcb>`_  2021-12-21   ``Fixes docstring for PubSubCreateSubscriptionOperator (#20237)``
`d4c4f9e09 <https://github.com/apache/airflow/commit/d4c4f9e09ee8b0453ff8503c30274eeaa80e7fde>`_  2021-12-21   ``Fix mypy errors for google.cloud_build (#20234)``
`c6dbb3f88 <https://github.com/apache/airflow/commit/c6dbb3f8856be75ff2619476ab3ca587a52e033a>`_  2021-12-21   ``Fix MyPy for Google Bigquery (#20329)``
`ed604b62f <https://github.com/apache/airflow/commit/ed604b62f3dfb4d76d6f1eaf4d639dc65956d8f2>`_  2021-12-18   ``Fix remaining MyPy errors in Google Provider (#20358)``
`17404f1f1 <https://github.com/apache/airflow/commit/17404f1f10efd41f98eb8a0317b578ff40f9c77d>`_  2021-12-16   ``Move source_objects datatype check out of GCSToBigQueryOperator.__init__ (#20347)``
`174681911 <https://github.com/apache/airflow/commit/174681911f96f17d41a4f560ca08d5e200944f7f>`_  2021-12-16   ``Fix MyPy Errors for dataproc package (#20327)``
`2fb5e1d0e <https://github.com/apache/airflow/commit/2fb5e1d0ec306839a3ff21d0bddbde1d022ee8c7>`_  2021-12-15   ``Fix cached_property MyPy declaration and related MyPy errors (#20226)``
`21b866188 <https://github.com/apache/airflow/commit/21b866188662b08bac0de778daec83cb28864097>`_  2021-12-15   ``Fix missing get_backup method for Dataproc Metastore (#20326)``
`cdaa9a252 <https://github.com/apache/airflow/commit/cdaa9a252900091f4c0e912a6d2a8890b7cb571a>`_  2021-12-15   ``Fix MyPy errors for google.cloud.tasks (#20233)``
`43efde623 <https://github.com/apache/airflow/commit/43efde6230487b003f715e04d195126f63f261ff>`_  2021-12-15   ``Fix MyPy Errors for Apache Beam (and Dataflow) provider. (#20301)``
`c4b369410 <https://github.com/apache/airflow/commit/c4b369410155dfc461d2b95ee66cb1927f8e4230>`_  2021-12-15   ``Fix MyPy errors in leveldb (#20222)``
`1570519a9 <https://github.com/apache/airflow/commit/1570519a976dfb9de1aba9c2c0bee169e7ab5ee1>`_  2021-12-14   ``Fix MyPy errors for google.cloud.transfers (#20229)``
`632bd0133 <https://github.com/apache/airflow/commit/632bd0133e0920c036f1cd83d100f477726fcb41>`_  2021-12-13   ``Fix MyPY errors for google.cloud.example_dags (#20232)``
`644051abc <https://github.com/apache/airflow/commit/644051abcbb87aab906e050eacce3a70379060dd>`_  2021-12-13   ``Fix MyPy errors for google/marketing_platform and suite (#20227)``
`a20846380 <https://github.com/apache/airflow/commit/a2084638020613979fa1ed9ba944050f274bb160>`_  2021-12-13   ``Organize S3 Classes in Amazon Provider (#20167)``
`98514cc15 <https://github.com/apache/airflow/commit/98514cc1599751d7611b3180c60887da0a25ff5e>`_  2021-12-13   ``Add optional location to bigquery data transfer service (#15088) (#20221)``
`1f662571b <https://github.com/apache/airflow/commit/1f662571b2133df09da22aea35936bb10b8ebffa>`_  2021-12-12   ``Fix MyPy errors in google.cloud.sensors (#20228)``
`22341b90d <https://github.com/apache/airflow/commit/22341b90da1d7efb0d9c1d6c4dc054e0238d1f27>`_  2021-12-11   ``Add Google Cloud Tasks how-to documentation (#20145)``
`e9262752d <https://github.com/apache/airflow/commit/e9262752dce86225e960b420287a51c532b21107>`_  2021-12-11   ``Finalised Datastore documentation (#20138)``
`fa96b0939 <https://github.com/apache/airflow/commit/fa96b093952f96449d6d328a2b9e9300b81cf08e>`_  2021-12-09   ``Update Sphinx and Sphinx-AutoAPI (#20079)``
`ed8b63ba2 <https://github.com/apache/airflow/commit/ed8b63ba2460f47744f4dcf40019592816bb89b5>`_  2021-12-08   ``Providers facebook hook multiple account (#19377)``
`50bf53665 <https://github.com/apache/airflow/commit/50bf5366564957cc0f057ca923317c421fffdeaa>`_  2021-12-08   ``Remove deprecated method call (blob.download_as_string) (#20091)``
`564fe635b <https://github.com/apache/airflow/commit/564fe635bdb0ba0b26a7b55f63fbe92d4f173e9d>`_  2021-12-06   ``Added example DAG for MSSQL to Google Cloud Storage (GCS) (#19873)``
`cb082d361 <https://github.com/apache/airflow/commit/cb082d361a61da7040e044ff2c1f7758142a9b2d>`_  2021-12-02   ``Remove deprecated template_fields from GoogleDriveToGCSOperator (#19991)``
`6977c4757 <https://github.com/apache/airflow/commit/6977c475720aa18889cd11117a0135e857f2efca>`_  2021-12-01   ``BigQueryHook fix typo in run_load doc string (#19924)``
`f6dca1fa5 <https://github.com/apache/airflow/commit/f6dca1fa5e70ef08798adeb5a6bfc70f41229646>`_  2021-12-01   ``Update doc reference links (#19909)``
================================================================================================  ===========  =====================================================================================

6.2.0
.....

Latest change: 2021-11-30

================================================================================================  ===========  ========================================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ========================================================================================================
`853576d90 <https://github.com/apache/airflow/commit/853576d9019d2aca8de1d9c587c883dcbe95b46a>`_  2021-11-30   ``Update documentation for November 2021 provider's release (#19882)``
`fb478c00c <https://github.com/apache/airflow/commit/fb478c00cdc5e78d5e85fe5ac103707c829be2fb>`_  2021-11-28   ``Move 'bucket_name' validation out of '__init__' in Google Marketing Platform operators (#19383)``
`e9e530979 <https://github.com/apache/airflow/commit/e9e530979a9176fa6842a2365ce3ff1bb42dfae2>`_  2021-11-28   ``Update 'default_args' value in example_functions DAG from str to int (#19865)``
`bf68b9a84 <https://github.com/apache/airflow/commit/bf68b9a8461eda634a7d91aa56575fb950960eaa>`_  2021-11-26   ``Create dataproc serverless spark batches operator (#19248)``
`a192cecf6 <https://github.com/apache/airflow/commit/a192cecf6bb9b22e058b8c0015c351131185282b>`_  2021-11-26   ``updates pipeline_timeout CloudDataFusionStartPipelineOperator (#18773)``
`eb163c81d <https://github.com/apache/airflow/commit/eb163c81d16532252d6196fd70c85e7ea6236279>`_  2021-11-25   ``Fix GCS system tests (#19227)``
`744d11bdb <https://github.com/apache/airflow/commit/744d11bdb2acd52794a959572695943df8729a37>`_  2021-11-25   ``Clean up ''default_args'' usage in docs (#19803)``
`0b2e1a874 <https://github.com/apache/airflow/commit/0b2e1a8744ac0d5965cb11f6a6fa74cee1d03f3d>`_  2021-11-22   ``Added wait mechanizm to the DataprocJobSensor to avoid 509 errors when Job is not available (#19740)``
`3336bb6c3 <https://github.com/apache/airflow/commit/3336bb6c3cfeea3f5fe9c17f3958db47cc867f61>`_  2021-11-19   ``Fix badly merged impersonation in GKEPodOperator (#19696)``
`952ef908b <https://github.com/apache/airflow/commit/952ef908bc8965641865aaeee9fbcd52a76d700b>`_  2021-11-19   ``Support impersonation_chain parameter in the GKEStartPodOperator (#19518)``
`853c16465 <https://github.com/apache/airflow/commit/853c16465a4d304a3b7d135356270fee87d3461b>`_  2021-11-18   ``Clean-up of google cloud example dags - batch 3 (#19664)``
`355dec8fe <https://github.com/apache/airflow/commit/355dec8fea5e2ef1a9b88363f201fce4f022fef3>`_  2021-11-17   ``Misc. documentation typos and language improvements (#19599)``
`b9d31cd44 <https://github.com/apache/airflow/commit/b9d31cd44962fc376fcf98380eaa1ea60fb6c835>`_  2021-11-17   ``Cleanup dynamic 'start_date' use for miscellaneous Google example DAGs (#19400)``
`daf234bd5 <https://github.com/apache/airflow/commit/daf234bd5e62d076b9bb861119355ab8c18e27a4>`_  2021-11-16   ``Remove reference to deprecated operator in example_dataproc (#19619)``
`48f228cf9 <https://github.com/apache/airflow/commit/48f228cf9ef7602df9bea6ce20d663ac0c4393e1>`_  2021-11-15   ``#16691 Providing more information in docs for DataprocCreateCluster operator migration (#19446)``
`6ef44b6a5 <https://github.com/apache/airflow/commit/6ef44b6a507a8e8d5f41a6731a0773046623d171>`_  2021-11-15   ``Clean-up of google cloud example dags - batch 2 (#19527)``
`dc0159e7e <https://github.com/apache/airflow/commit/dc0159e7e47a7f524ea937634472ffe78d906a16>`_  2021-11-14   ``Add support in GCP connection for reading key from Secret Manager (#19164)``
`4212c4932 <https://github.com/apache/airflow/commit/4212c4932433a50bda09f3e771a02f5ded4553a7>`_  2021-11-14   ``Update Azure modules to comply with AIP-21 (#19431)``
`aa2cb5545 <https://github.com/apache/airflow/commit/aa2cb5545f09d694b9143b323efcd4f6b6c66e60>`_  2021-11-12   ``Remove remaining 'pylint: disable' comments (#19541)``
`c8dc0311d <https://github.com/apache/airflow/commit/c8dc0311dadbcd1b85923a1018e954d979e74d36>`_  2021-11-08   ``Fix Cloud SQL system tests (#19014)``
`26ad55beb <https://github.com/apache/airflow/commit/26ad55beb00f5a0915ba4bec541e3d67044834e9>`_  2021-11-08   ``Add dataproc metastore operators (#18945)``
`9efb989d1 <https://github.com/apache/airflow/commit/9efb989d19e657a2cde2eef98804c5007f148ee1>`_  2021-11-07   ``Clean-up of google cloud example dags (#19436)``
`f421409b4 <https://github.com/apache/airflow/commit/f421409b4d431a2055eb273e7bc355819c880bd9>`_  2021-11-05   ``Fix typos in warnings, docstrings, exceptions (#19424)``
`a3c9956f7 <https://github.com/apache/airflow/commit/a3c9956f79310b529a79c1e43fb881c5e173d321>`_  2021-10-30   ``Add support of 'path' parameter for GCloud Storage Transfer Service operators (#17446)``
================================================================================================  ===========  ========================================================================================================

6.1.0
.....

Latest change: 2021-10-29

================================================================================================  ===========  ======================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ======================================================================================
`d9567eb10 <https://github.com/apache/airflow/commit/d9567eb106929b21329c01171fd398fbef2dc6c6>`_  2021-10-29   ``Prepare documentation for October Provider's release (#19321)``
`55abc2f62 <https://github.com/apache/airflow/commit/55abc2f620a96832661d1797442a834bf958bb3e>`_  2021-10-28   ``Support query timeout as an argument in CassandraToGCSOperator (#18927)``
`e4aa377da <https://github.com/apache/airflow/commit/e4aa377da7fe1801dff04d54c5ed4fd525af94c4>`_  2021-10-28   ``Update BigQueryCreateExternalTableOperator doc and parameters (#18676)``
`20847fdbf <https://github.com/apache/airflow/commit/20847fdbf8ecd3be394d24d47ce151c26d018ea1>`_  2021-10-27   ``Add value to "namespaceId" of query (#19163)``
`3c08c025c <https://github.com/apache/airflow/commit/3c08c025c5445ffc0533ac28d07ccf2e69a19ca8>`_  2021-10-27   ``Move validation of templated input params to run after the context init (#19048)``
`eba1b68b3 <https://github.com/apache/airflow/commit/eba1b68b30ad2818df0b8fde3be30688ec5c0042>`_  2021-10-27   ``Update dataflow.py (#19231)``
`7ecf29f70 <https://github.com/apache/airflow/commit/7ecf29f70d3fbb1d6174fe693334a0f7fce38a70>`_  2021-10-26   ``Fix hard-coded /tmp directory in CloudSQL Hook (#19229)``
`726a1517e <https://github.com/apache/airflow/commit/726a1517ec368e0f5906368350d6fa96836943ae>`_  2021-10-26   ``Fix bug in Dataflow hook when no jobs are returned (#18981)``
`d9192a55b <https://github.com/apache/airflow/commit/d9192a55bacab339c4634f090160bd2d8ed77d7f>`_  2021-10-22   ``Replacing non-attribute template_fields for BigQueryToMsSqlOperator (#19052)``
`4fae04a47 <https://github.com/apache/airflow/commit/4fae04a47119c9f2319ae5e533edcf457e4df003>`_  2021-10-21   ``Upgrade the Dataproc package to 3.0.0 and migrate from v1beta2 to v1 api (#18879)``
`0e95b5777 <https://github.com/apache/airflow/commit/0e95b5777242b00f41812c099f1cf8e2fc0df40c>`_  2021-10-19   ``Google provider catch invalid secret name (#18790)``
`86a2a19ad <https://github.com/apache/airflow/commit/86a2a19ad2bdc87a9ad14bb7fde9313b2d7489bb>`_  2021-10-17   ``More f-strings (#18855)``
`a418fd96f <https://github.com/apache/airflow/commit/a418fd96f70eac1d4d7dc91553f41d5153beda93>`_  2021-10-17   ``Use google cloud credentials when executing beam command in subprocess (#18992)``
`5c3e45382 <https://github.com/apache/airflow/commit/5c3e4538208cc317e6e45ae7b247e7fb83840f49>`_  2021-10-15   ``Fix BigQueryToMsSqlOperator documentation (#18995)``
`406b38b2e <https://github.com/apache/airflow/commit/406b38b2e3fcf9d7fad28573bf77bb9fee5847d1>`_  2021-10-15   ``Replace default api_version of FacebookAdsReportToGcsOperator (#18996)``
`1571f8054 <https://github.com/apache/airflow/commit/1571f80546853688778c2a3ec5194e5c8be0edbd>`_  2021-10-14   ``Add pre-commit hook for common misspelling check in files (#18964)``
`20df60de2 <https://github.com/apache/airflow/commit/20df60de24e1dbeab2dcf5b989b69080d1b3ed34>`_  2021-10-07   ``Dataflow Operators - use project and location from job in on_kill method. (#18699)``
`86bf2a29b <https://github.com/apache/airflow/commit/86bf2a29ba784b25c335408eb4647ad2eb48b525>`_  2021-10-04   ``Simplify strings previously split across lines (#18679)``
================================================================================================  ===========  ======================================================================================

6.0.0
.....

Latest change: 2021-09-30

================================================================================================  ===========  ========================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ========================================================================================
`840ea3efb <https://github.com/apache/airflow/commit/840ea3efb9533837e9f36b75fa527a0fbafeb23a>`_  2021-09-30   ``Update documentation for September providers release (#18613)``
`9279c44c9 <https://github.com/apache/airflow/commit/9279c44c91274b7ee31c244d41090c93e5753394>`_  2021-09-29   ``Fix part of Google system tests (#18494)``
`2fadf3c3c <https://github.com/apache/airflow/commit/2fadf3c3cf6e8a5d26953ebce6401ab5059ee05f>`_  2021-09-27   ``Fix kubernetes engine system test (#18548)``
`a458fcc57 <https://github.com/apache/airflow/commit/a458fcc573845ff65244a2dafd204ed70129f3e8>`_  2021-09-27   ``Updating miscellaneous provider DAGs to use TaskFlow API where applicable (#18278)``
`97d689231 <https://github.com/apache/airflow/commit/97d6892318ce2866f09f2c21247ed3b1b9975695>`_  2021-09-25   ``Rename AzureDataLakeStorage to ADLS (#18493)``
`a5439eee7 <https://github.com/apache/airflow/commit/a5439eee72cd380f8434e622e8bef7c35786ce39>`_  2021-09-23   ``Add index to the dataset name to have separate dataset for each example DAG (#18459)``
`18d7e1e22 <https://github.com/apache/airflow/commit/18d7e1e2270ffcbc8077ba700f209ae69eccef99>`_  2021-09-21   ``Fix BigQuery system test (#18373)``
`e25eea052 <https://github.com/apache/airflow/commit/e25eea052fd54c94b490a377de05c6bae4c24dbb>`_  2021-09-19   ``Inclusive Language (#18349)``
`7458f1e78 <https://github.com/apache/airflow/commit/7458f1e7861e5146da61cbff9393d72c88a3608c>`_  2021-09-18   ``Remove check for at least one schema in GCSToBigquery (#18150)``
`2474f8922 <https://github.com/apache/airflow/commit/2474f8922d0cb7435040f5e21ca61fb6b633dec2>`_  2021-09-13   ``Migrate Google Cloud Build from Discovery API to Python SDK (#18184)``
`8ae2bb9bf <https://github.com/apache/airflow/commit/8ae2bb9bfa8cfd62a8ae5f6edabce47800ccb140>`_  2021-09-13   ``Fix error when create external table using table resource (#17998)``
`9140ad8d8 <https://github.com/apache/airflow/commit/9140ad8d8f6dadd56bc592f5cdbf5585c2a8ce89>`_  2021-09-11   ``Use parameters instead of params (#18143)``
`3d4bfdcbb <https://github.com/apache/airflow/commit/3d4bfdcbb97c5d68761e5bfd2699a50ca0edd12a>`_  2021-09-10   ``Add missing __init__.py files for some test packages (#18142)``
`cfb602a33 <https://github.com/apache/airflow/commit/cfb602a33dc1904e2f51d74fa711722c8b702726>`_  2021-09-10   ``Fix ''BigQuery'' data extraction in ''BigQueryToMySqlOperator'' (#18073)``
`2fd3f27eb <https://github.com/apache/airflow/commit/2fd3f27ebd2a4f695968fb7cc5d119e087820928>`_  2021-09-10   ``Make next_dagrun_info take a data interval (#18088)``
`944dcfbb9 <https://github.com/apache/airflow/commit/944dcfbb918050274fd3a1cc51d8fdf460ea2429>`_  2021-09-07   ``Change TaskInstance and TaskReschedule PK from execution_date to run_id (#17719)``
`bfad233b9 <https://github.com/apache/airflow/commit/bfad233b91875fb2dec4217f1b0ae2ba8dd9820c>`_  2021-09-06   ``Fix providers tests in main branch with eager upgrades (#18040)``
`21348c194 <https://github.com/apache/airflow/commit/21348c194d4149237e357e0fff9ed444d27fa71d>`_  2021-09-03   ``fix(CloudSqlProxyRunner): don't query connections from Airflow DB (#18006)``
`9a0c10ba3 <https://github.com/apache/airflow/commit/9a0c10ba3fac3bb88f4f103114d4590b3fb191cb>`_  2021-09-01   ``deduplicate running jobs on BigQueryInsertJobOperator (#17496)``
`fe34582fc <https://github.com/apache/airflow/commit/fe34582fc2f418b96a5dc5c10b8b6a8b48bdb7ea>`_  2021-09-01   ``New google operator: SQLToGoogleSheetsOperator (#17887)``
`500780651 <https://github.com/apache/airflow/commit/500780651cfef9254d5e365c0de6f8c7af6d05bf>`_  2021-08-31   ``Add possibility to run DAGs from system tests and see DAGs logs (#17868)``
================================================================================================  ===========  ========================================================================================

5.1.0
.....

Latest change: 2021-08-30

================================================================================================  ===========  =========================================================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =========================================================================================================================
`0a6858847 <https://github.com/apache/airflow/commit/0a68588479e34cf175d744ea77b283d9d78ea71a>`_  2021-08-30   ``Add August 2021 Provider's documentation (#17890)``
`b5da846dd <https://github.com/apache/airflow/commit/b5da846dd1f27d798dc7dc4f4227de4418919874>`_  2021-08-30   ``Fix missing Data Fusion sensor integration (#17914)``
`07405e6df <https://github.com/apache/airflow/commit/07405e6df4508fbf3e67d879479e2afd37df8421>`_  2021-08-30   ``[AIRFLOW-9300] Add DatafusionPipelineStateSensor and aync option to the CloudDataFusionStartPipelineOperator (#17787)``
`42e13e1a5 <https://github.com/apache/airflow/commit/42e13e1a5a4c97a2085ddf96f7d93e7bf71949b8>`_  2021-08-30   ``Remove all deprecation warnings in providers (#17900)``
`aa5952e58 <https://github.com/apache/airflow/commit/aa5952e58c58cab65f49b9e2db2adf66f17e7599>`_  2021-08-27   ``Gcp ai hyperparameter tuning (#17790)``
`87769db98 <https://github.com/apache/airflow/commit/87769db98f963338855f59cfc440aacf68e008c9>`_  2021-08-27   ``Allow omission of 'initial_node_count' if 'node_pools' is specified (#17820)``
`be75dcd39 <https://github.com/apache/airflow/commit/be75dcd39cd10264048c86e74110365bd5daf8b7>`_  2021-08-23   ``Update description about the new ''connection-types'' provider meta-data``
`d04aa1352 <https://github.com/apache/airflow/commit/d04aa135268b8e0230be3af6598a3b18e8614c3c>`_  2021-08-20   ``[Airflow 13779] use provided parameters in the wait_for_pipeline_state hook (#17137)``
`76ed2a49c <https://github.com/apache/airflow/commit/76ed2a49c6cd285bf59706cf04f39a7444c382c9>`_  2021-08-19   ``Import Hooks lazily individually in providers manager (#17682)``
`b68d1935f <https://github.com/apache/airflow/commit/b68d1935f958a480f1e7d8dc1e3415707a14646b>`_  2021-08-19   ``Add error check for config_file parameter in GKEStartPodOperator (#17700)``
`29aab6434 <https://github.com/apache/airflow/commit/29aab6434ffe0fb8c83b6fd6c9e44310966d496a>`_  2021-08-17   ``Adds secrets backend/logging/auth information to provider yaml (#17625)``
`b06d52860 <https://github.com/apache/airflow/commit/b06d52860327cc0a52bcfc4f2305344b3f7c2b1d>`_  2021-08-11   ``Don't cache Google Secret Manager client (#17539)``
`67cbb0f18 <https://github.com/apache/airflow/commit/67cbb0f181f806edb16ca12fb7a2638b5f31eb58>`_  2021-08-02   ``Enable specifying dictionary paths in 'template_fields_renderers' (#17321)``
`c384f9b0f <https://github.com/apache/airflow/commit/c384f9b0f509bab704a70380465be18754800a52>`_  2021-07-29   ``GCP Secret Manager error handling for missing credentials (#17264)``
================================================================================================  ===========  =========================================================================================================================

5.0.0
.....

Latest change: 2021-07-26

================================================================================================  ===========  =======================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =======================================================================================
`87f408b1e <https://github.com/apache/airflow/commit/87f408b1e78968580c760acb275ae5bb042161db>`_  2021-07-26   ``Prepares docs for Rc2 release of July providers (#17116)``
`448e50bd2 <https://github.com/apache/airflow/commit/448e50bd23b4493980a41a5d4241ad3ecef087fb>`_  2021-07-26   ``Updating Google Cloud example DAGs to use XComArgs (#16875)``
`aaf44ccac <https://github.com/apache/airflow/commit/aaf44ccace2336d00240e7e093094a9b808402d9>`_  2021-07-26   ``Updating miscellaneous Google example DAGs to use XComArgs (#16876)``
`d01cc945d <https://github.com/apache/airflow/commit/d01cc945ddb03620216159335729a36c1a20f9f2>`_  2021-07-26   ``Fixes several failing tests after broken main (#17222)``
`babc4250f <https://github.com/apache/airflow/commit/babc4250f3c5420e8d8059d500ba8d0e95d70873>`_  2021-07-26   ``Fixes statich check failures (#17218)``
`5d2224795 <https://github.com/apache/airflow/commit/5d2224795b3548516311025d5549094a9b168f3b>`_  2021-07-25   ``Google Ads Hook: Support newer versions of the google-ads library (#17160)``
`966b25019 <https://github.com/apache/airflow/commit/966b2501995279b7b5f2e1d0bf1c63a511dd382e>`_  2021-07-25   ``Fix GCStoGCS operator with replace diabled and existing destination object (#16991)``
`763919d41 <https://github.com/apache/airflow/commit/763919d4152ffa13433e2489fec85ed286b7b196>`_  2021-07-25   ``Adding custom Salesforce connection type + SalesforceToS3Operator updates (#17162)``
`81bd40933 <https://github.com/apache/airflow/commit/81bd40933ea85a0d7807cf7f9a841157ec885cdf>`_  2021-07-23   ``[CASSANDRA-16814] Fix cassandra to gcs type inconsistency. (#17183)``
`026ffe65d <https://github.com/apache/airflow/commit/026ffe65d4738674512f691a56b922e82d0a2309>`_  2021-07-19   ``fix: dataprocpysparkjob project_id as self.project_id (#17075)``
`d02ded65e <https://github.com/apache/airflow/commit/d02ded65eaa7d2281e249b3fa028605d1b4c52fb>`_  2021-07-15   ``Fixed wrongly escaped characters in amazon's changelog (#17020)``
`b916b7507 <https://github.com/apache/airflow/commit/b916b7507921129dc48d6add1bdc4b923b60c9b9>`_  2021-07-15   ``Prepare documentation for July release of providers. (#17015)``
`a3f5c9380 <https://github.com/apache/airflow/commit/a3f5c93806258b5ad396a638ba0169eca7f9d065>`_  2021-07-13   ``Update alias for field_mask in Google Memmcache (#16975)``
`b0f7f91fe <https://github.com/apache/airflow/commit/b0f7f91fe29d1314b71c76de0f11d2dbe81c5c4a>`_  2021-07-07   ``Standardise dataproc location param to region (#16034)``
`866a601b7 <https://github.com/apache/airflow/commit/866a601b76e219b3c043e1dbbc8fb22300866351>`_  2021-06-28   ``Removes pylint from our toolchain (#16682)``
================================================================================================  ===========  =======================================================================================

4.0.0
.....

Latest change: 2021-06-18

================================================================================================  ===========  =========================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =========================================================================================
`bbc627a3d <https://github.com/apache/airflow/commit/bbc627a3dab17ba4cf920dd1a26dbed6f5cebfd1>`_  2021-06-18   ``Prepares documentation for rc2 release of Providers (#16501)``
`cbf8001d7 <https://github.com/apache/airflow/commit/cbf8001d7630530773f623a786f9eb319783b33c>`_  2021-06-16   ``Synchronizes updated changelog after buggfix release (#16464)``
`8a9c33783 <https://github.com/apache/airflow/commit/8a9c3378385454f16560d82e885ebc00c5ec069c>`_  2021-06-15   ``Remove class references in changelogs (#16454)``
`1fba5402b <https://github.com/apache/airflow/commit/1fba5402bb14b3ffa6429fdc683121935f88472f>`_  2021-06-15   ``More documentation update for June providers release (#16405)``
`3c5cc42e1 <https://github.com/apache/airflow/commit/3c5cc42e13322e9b2bc35be73bd04a8d59aa2447>`_  2021-06-14   ``Fix deprecation warnings location in google provider (#16403)``
`b272f9cec <https://github.com/apache/airflow/commit/b272f9cec99fd0e3373d23b706f33892cbcb9626>`_  2021-06-13   ``fix: ensure datetime-related values fully compatible with MySQL and BigQuery (#15026)``
`7f8f75eb8 <https://github.com/apache/airflow/commit/7f8f75eb80790d4be3167f5e1ffccc669a281d55>`_  2021-06-12   ``Add BigQueryToMsSqlOperator (#15422)``
`0c80a7d41 <https://github.com/apache/airflow/commit/0c80a7d41100bf8d18b661c8286d6056e6d5d2f1>`_  2021-06-11   ``Fixes AzureFileShare connection extras (#16388)``
`9c94b72d4 <https://github.com/apache/airflow/commit/9c94b72d440b18a9e42123d20d48b951712038f9>`_  2021-06-07   ``Updated documentation for June 2021 provider release (#16294)``
`1e647029e <https://github.com/apache/airflow/commit/1e647029e469c1bb17e9ad051d0184f3357644c3>`_  2021-06-01   ``Rename the main branch of the Airflow repo to be 'main' (#16149)``
`99d153528 <https://github.com/apache/airflow/commit/99d1535287df7f8cfced39baff7a08f6fcfdf8ca>`_  2021-05-31   ``Fix: GCS To BigQuery source_object (#16160)``
`e1137523d <https://github.com/apache/airflow/commit/e1137523d4e9cb5d5cfe8584963620677a4ad789>`_  2021-05-30   ``Fix: Unnecessary downloads in ''GCSToLocalFilesystemOperator'' (#16171)``
`904709d34 <https://github.com/apache/airflow/commit/904709d34fbe0b6062d72932b72954afe13ec148>`_  2021-05-27   ``Check synctatic correctness for code-snippets (#16005)``
`86768859c <https://github.com/apache/airflow/commit/86768859c689bf02ced96e71996a3a30da1b5888>`_  2021-05-26   ``Fix bigquery type error when export format is parquet (#16027)``
`6ae9aeec3 <https://github.com/apache/airflow/commit/6ae9aeec3f866ecfce83945ad1e831be9f8e5ebb>`_  2021-05-26   ``pass wait_for_done parameter down to _DataflowJobsController (#15541)``
`476d0f6e3 <https://github.com/apache/airflow/commit/476d0f6e3d2059f56532cda36cdc51aa86bafb37>`_  2021-05-22   ``Bump pyupgrade v2.13.0 to v2.18.1 (#15991)``
`aa4713e43 <https://github.com/apache/airflow/commit/aa4713e43f92d3e4c68c3ad00e2d44caaf29aafe>`_  2021-05-21   ``Use api version only in GoogleAdsHook not operators (#15266)``
`76a80bb17 <https://github.com/apache/airflow/commit/76a80bb17c9cecbe3767dab471f6a79084c822ea>`_  2021-05-19   ``Move plyvel to google provider extra (#15812)``
`bb115da0b <https://github.com/apache/airflow/commit/bb115da0b78036ace5e31e2139c12ca044b3a97d>`_  2021-05-17   ``Get rid of requests as core dependency (#15781)``
`9c8391a13 <https://github.com/apache/airflow/commit/9c8391a13f6ba29749675cf23f2f874f96b0cc8c>`_  2021-05-10   ``Fix spelling (#15699)``
`3711a29e5 <https://github.com/apache/airflow/commit/3711a29e5e253ede4ab12efe5990e83240e8a9a9>`_  2021-05-09   ``Fix argument ordering and type of bucket and object (#15738)``
`a01567c47 <https://github.com/apache/airflow/commit/a01567c47159da8c2824ac5f15629b51f49af958>`_  2021-05-08   ``Fix sql_to_gcs docstring lint error (#15730)``
`f3fada910 <https://github.com/apache/airflow/commit/f3fada91013f7916b188ceceb0284bc9860d1388>`_  2021-05-07   ``Add short description to BaseSQLToGCSOperator docstring (#15728)``
`37681bca0 <https://github.com/apache/airflow/commit/37681bca0081dd228ac4047c17631867bba7a66f>`_  2021-05-07   ``Auto-apply apply_default decorator (#15667)``
`b8c0fde38 <https://github.com/apache/airflow/commit/b8c0fde38a7df9d00185bf53e9f303b98fd064dc>`_  2021-05-07   ``Add extra links for google dataproc (#10343)``
`3b4fdd0a7 <https://github.com/apache/airflow/commit/3b4fdd0a7a176bfb2e9a17d4627b1d4ed40f1c86>`_  2021-05-06   ``add oracle  connection link (#15632)``
`cf6324e43 <https://github.com/apache/airflow/commit/cf6324e43b2f7c183c3872704733b69d1498cda1>`_  2021-05-04   ``Implement BigQuery Table Schema Update Operator (#15367)``
`0f97a3970 <https://github.com/apache/airflow/commit/0f97a3970d2c652beedbf2fbaa33e2b2bfd69bce>`_  2021-05-04   ``Rename example bucket names to use INVALID BUCKET NAME by default (#15651)``
================================================================================================  ===========  =========================================================================================

3.0.0
.....

Latest change: 2021-05-01

================================================================================================  ===========  ====================================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ====================================================================================================
`807ad32ce <https://github.com/apache/airflow/commit/807ad32ce59e001cb3532d98a05fa7d0d7fabb95>`_  2021-05-01   ``Prepares provider release after PIP 21 compatibility (#15576)``
`814e471d1 <https://github.com/apache/airflow/commit/814e471d137aad68bd64a21d20736e7b88403f97>`_  2021-04-29   ``Update pre-commit checks (#15583)``
`bf2b48174 <https://github.com/apache/airflow/commit/bf2b48174a1ccfe398eefba7f04a5cacac421266>`_  2021-04-27   ``Add Connection Documentation for Providers (#15499)``
`4b031d39e <https://github.com/apache/airflow/commit/4b031d39e12110f337151cda6693e2541bf71c2c>`_  2021-04-27   ``Make Airflow code Pylint 2.8 compatible (#15534)``
`e229f3541 <https://github.com/apache/airflow/commit/e229f3541dd764db54785625875a7c5e94225736>`_  2021-04-27   ``Use Pip 21.* to install airflow officially (#15513)``
`71c673e42 <https://github.com/apache/airflow/commit/71c673e427a89cae2a9f3174c32c5c85556d6342>`_  2021-04-22   ``Update Docstrings of Modules with Missing Params (#15391)``
`3b9a91806 <https://github.com/apache/airflow/commit/3b9a91806ea102cc2bc00b545f63f57031f458c9>`_  2021-04-22   ``Bugfix: Fix rendering of ''object_name'' in ''GCSToLocalFilesystemOperator'' (#15487)``
`c5e302030 <https://github.com/apache/airflow/commit/c5e302030de7512a07120f71f388ad1859b26ca2>`_  2021-04-21   ``Fix typo in DataprocCreateClusterOperator (#15462)``
`42a1ca8aa <https://github.com/apache/airflow/commit/42a1ca8aab905a0eb1ffb3da30cef9c76830abff>`_  2021-04-20   ``Fixes wrongly specified path for leveldb hook (#15453)``
`6da36bad2 <https://github.com/apache/airflow/commit/6da36bad2c5c86628284d91ad6de418bae7cd029>`_  2021-04-18   ``[Airflow-15245] - passing custom image family name to the DataProcClusterCreateoperator (#15250)``
`f64990560 <https://github.com/apache/airflow/commit/f6499056069fd2331b121144e67f6c6e95d7ca5b>`_  2021-04-15   ``fix docstring typos (#15392)``
`7bf69edca <https://github.com/apache/airflow/commit/7bf69edca0d0622deb171f5a16af754dbcd04ce2>`_  2021-04-08   ``Fix typo in a docstring (#15276)``
================================================================================================  ===========  ====================================================================================================

2.2.0
.....

Latest change: 2021-04-06

================================================================================================  ===========  ====================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ====================================================================================
`042be2e4e <https://github.com/apache/airflow/commit/042be2e4e06b988f5ba2dc146f53774dabc8b76b>`_  2021-04-06   ``Updated documentation for provider packages before April release (#15236)``
`eae22cec9 <https://github.com/apache/airflow/commit/eae22cec9c87e8dad4d6e8599e45af1bdd452062>`_  2021-04-06   ``Adds 'Trino' provider (with lower memory footprint for tests) (#15187)``
`e49722859 <https://github.com/apache/airflow/commit/e49722859b81cfcdd7e4bb8e8aba4efb049a8590>`_  2021-04-05   ``Updates 3.6 limits for latest versions of a few libraries (#15209)``
`1d641d8f1 <https://github.com/apache/airflow/commit/1d641d8f114660eee18c6246081cfe991bb74baa>`_  2021-04-01   ``update remaining old import paths of operators (#15127)``
`099c490cf <https://github.com/apache/airflow/commit/099c490cffae9556e56e141addcb41e9676e0d8f>`_  2021-03-28   ``Override project in dataprocSubmitJobOperator (#14981)``
`537969889 <https://github.com/apache/airflow/commit/53796988929d7b5de98cd322fdea9e0a8edec0a1>`_  2021-03-27   ``Improve docstrings for various modules (#15047)``
`a7ca1b3b0 <https://github.com/apache/airflow/commit/a7ca1b3b0bdf0b7677e53be1b11e833714dfbbb4>`_  2021-03-26   ``Fix Sphinx Issues with Docstrings (#14968)``
`a7e144bec <https://github.com/apache/airflow/commit/a7e144bec855f6ccf0fa5ae8447894195ffe170f>`_  2021-03-23   ``Google Dataflow Hook to handle no Job Type (#14914)``
`72ea841b4 <https://github.com/apache/airflow/commit/72ea841b4bb439495b0f58e043774d38f701100e>`_  2021-03-22   ``GCS to BigQuery Transfer Operator with Labels and Description parameter (#14881)``
`e172bd0e1 <https://github.com/apache/airflow/commit/e172bd0e16d5b13105734fe9eb8effc44d593c29>`_  2021-03-22   ``Update docstrings to adhere to sphinx standards (#14918)``
`68e4c4dcb <https://github.com/apache/airflow/commit/68e4c4dcb0416eb51a7011a3bb040f1e23d7bba8>`_  2021-03-20   ``Remove Backport Providers (#14886)``
`ddc9133d3 <https://github.com/apache/airflow/commit/ddc9133d36f88dbecd260a4f28ac2dec39395edf>`_  2021-03-15   ``Add GCS timespan transform operator (#13996)``
`943baff67 <https://github.com/apache/airflow/commit/943baff6701f9f8591090bf76219571d7f5e2cc5>`_  2021-03-10   ``Add job labels to bigquery check operators. (#14685)``
`6dc24c95e <https://github.com/apache/airflow/commit/6dc24c95e3bb46ac42fc80b1948aa79ae6c6fbd1>`_  2021-03-07   ``Fix grammar and remove duplicate words (#14647)``
`e7bb17aeb <https://github.com/apache/airflow/commit/e7bb17aeb83b2218620c5320241b0c9f902d74ff>`_  2021-03-06   ``Use built-in 'cached_property' on Python 3.8 where possible (#14606)``
`7daebefd1 <https://github.com/apache/airflow/commit/7daebefd15355b3f1331c6c58f66f3f88d38a10a>`_  2021-03-05   ``Use libyaml C library when available. (#14577)``
`35c9a9029 <https://github.com/apache/airflow/commit/35c9a902929b79cf7cf53ac5b90c3565dddb97dc>`_  2021-03-01   ``Add Google leveldb hook and operator (#13109) (#14105)``
================================================================================================  ===========  ====================================================================================

2.1.0
.....

Latest change: 2021-02-27

================================================================================================  ===========  ===============================================================================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ===============================================================================================================================================
`589d6dec9 <https://github.com/apache/airflow/commit/589d6dec922565897785bcbc5ac6bb3b973d7f5d>`_  2021-02-27   ``Prepare to release the next wave of providers: (#14487)``
`50a1504c5 <https://github.com/apache/airflow/commit/50a1504c524257e53eff06589b71973cfab5bf54>`_  2021-02-27   ``Fix spellings (#14483)``
`bfef559cf <https://github.com/apache/airflow/commit/bfef559cf6138eec3ac77c64289fb1d45133d8be>`_  2021-02-27   ``Corrects order of argument in docstring in GCSHook.download method (#14497)``
`33214d932 <https://github.com/apache/airflow/commit/33214d9326bb0bb52f06e230895f4f68fc952664>`_  2021-02-26   ``Refactor SQL/BigQuery/Qubole/Druid Check operators (#12677)``
`c28197998 <https://github.com/apache/airflow/commit/c281979982c36f16c4c346c996a0c8d6ca7c630d>`_  2021-02-23   ``Documentation and example dag for CloudDLPDeidentifyContentOperator, GCSObjectExistenceSensor, GCSObjectsWithPrefixExistenceSensor (#14033)``
`ca35bd7f7 <https://github.com/apache/airflow/commit/ca35bd7f7f6bc2fb4f2afd7762114ce262c61941>`_  2021-02-21   ``By default PIP will install all packages in .local folder (#14125)``
`a7e4266d6 <https://github.com/apache/airflow/commit/a7e4266d675d5283cdd34c6451c8ef0f2858a501>`_  2021-02-21   ``Refactor GoogleDriveToGCSOperator to use common methods (#14276)``
`1ab406663 <https://github.com/apache/airflow/commit/1ab406663ead7475ac14644553ac48466777bd78>`_  2021-02-16   ``Add GoogleDriveToLocalOperator (#14191)``
`59c94c679 <https://github.com/apache/airflow/commit/59c94c679e996ab7a75b4feeb1755353f60d030f>`_  2021-02-13   ``Add 'exists_ok' flag to BigQueryCreateEmptyTable(Dataset)Operator (#14026)``
`e31b27d59 <https://github.com/apache/airflow/commit/e31b27d593f7379f38ced34b6e4ce8947b91fcb8>`_  2021-02-13   ``Add materialized view support for BigQuery (#14201)``
`e3bcaa3ba <https://github.com/apache/airflow/commit/e3bcaa3ba351234effe52ad380345c4e39003fcb>`_  2021-02-12   ``Correct typo in GCSObjectsWtihPrefixExistenceSensor  (#14179)``
`7faa2d978 <https://github.com/apache/airflow/commit/7faa2d978c3a4e1eb2f7c6a931c9475712015f9f>`_  2021-02-10   ``Add BigQueryUpdateTableOperator (#14149)``
`1da697216 <https://github.com/apache/airflow/commit/1da69721651455c9108c00ca5f6723d6557524a9>`_  2021-02-10   ``Fixes to dataproc operators and hook (#14086)``
`02288cf2b <https://github.com/apache/airflow/commit/02288cf2baf590e448cd008f6216ccf8b776a67a>`_  2021-02-10   ``Add param to CloudDataTransferServiceOperator (#14118)``
`7d3864547 <https://github.com/apache/airflow/commit/7d38645472b0502212504b09d85b0e1271d74274>`_  2021-02-09   ``#9803 fix bug in copy operation without wildcard  (#13919)``
`b0c382426 <https://github.com/apache/airflow/commit/b0c382426c943cbf7bd7c09583d9c5d3137413ee>`_  2021-02-07   ``Add gdrive_to_gcs operator, drive sensor, additional functionality to drive hook, and supporting tests (#13982)``
`5d7d46bb3 <https://github.com/apache/airflow/commit/5d7d46bb33c1d529c1549b593ee27bbc7f56ea29>`_  2021-02-05   ``Improve GCSToSFTPOperator paths handling (#11284)``
`10343ec29 <https://github.com/apache/airflow/commit/10343ec29f8f0abc5b932ba26faf49bc63c6bcda>`_  2021-02-05   ``Corrections in docs and tools after releasing provider RCs (#14082)``
================================================================================================  ===========  ===============================================================================================================================================

2.0.0
.....

Latest change: 2021-02-04

================================================================================================  ===========  =========================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  =========================================================================================
`88bdcfa0d <https://github.com/apache/airflow/commit/88bdcfa0df5bcb4c489486e05826544b428c8f43>`_  2021-02-04   ``Prepare to release a new wave of providers. (#14013)``
`1872d8719 <https://github.com/apache/airflow/commit/1872d8719d24f94aeb1dcba9694837070b9884ca>`_  2021-02-03   ``Add Apache Beam operators (#12814)``
`0e8c77b93 <https://github.com/apache/airflow/commit/0e8c77b93a5ca5ecfdcd1c4bd91f54846fc15d57>`_  2021-02-03   ``Support google-cloud-logging' >=2.0.0 (#13801)``
`833e33832 <https://github.com/apache/airflow/commit/833e3383230e1f6f73f8022ddf439d3d531eff01>`_  2021-02-02   ``Fix four bugs in StackdriverTaskHandler (#13784)``
`d2efb3323 <https://github.com/apache/airflow/commit/d2efb33239d36e58fb69066fd23779724cb11a90>`_  2021-02-02   ``Support google-cloud-monitoring>=2.0.0 (#13769)``
`ac2f72c98 <https://github.com/apache/airflow/commit/ac2f72c98dc0821b33721054588adbf2bb53bb0b>`_  2021-02-01   ``Implement provider versioning tools (#13767)``
`823741cfe <https://github.com/apache/airflow/commit/823741cfea3e7a2584d1e68126db3d6e6739b08f>`_  2021-01-28   ``Improve GCS system test envs (#13946)``
`6d6588fe2 <https://github.com/apache/airflow/commit/6d6588fe2b8bb5fa33e930646d963df3e0530f23>`_  2021-01-28   ``Add Google Cloud Workflows Operators (#13366)``
`810c15ed8 <https://github.com/apache/airflow/commit/810c15ed85d7bcde8d5b8bc44e1cbd4859e29d2e>`_  2021-01-27   ``Fix and improve GCP BigTable hook and system test (#13896)``
`661661733 <https://github.com/apache/airflow/commit/6616617331bf6e8548bf6391cebb636220c1cc53>`_  2021-01-27   ``Add env variables to PubSub example dag (#13794)``
`f473ca713 <https://github.com/apache/airflow/commit/f473ca7130f844bc59477674e641b42b80698bb7>`_  2021-01-24   ``Replace 'google_cloud_storage_conn_id' by 'gcp_conn_id' when using 'GCSHook' (#13851)``
`a9ac2b040 <https://github.com/apache/airflow/commit/a9ac2b040b64de1aa5d9c2b9def33334e36a8d22>`_  2021-01-23   ``Switch to f-strings using flynt. (#13732)``
`9592be88e <https://github.com/apache/airflow/commit/9592be88e57cc7f59b9eac978292abd4d7692c0b>`_  2021-01-22   ``Fix Google Spanner example dag (#13842)``
`af52fdb51 <https://github.com/apache/airflow/commit/af52fdb51152a72441a44a271e498b1ec20dfd57>`_  2021-01-22   ``Improve environment variables in GCP Dataflow system test (#13841)``
`e7946f1cb <https://github.com/apache/airflow/commit/e7946f1cb7c144181443cbcc843d90bd597b09b5>`_  2021-01-22   ``Improve environment variables in GCP Datafusion system test (#13837)``
`61c1d6ec6 <https://github.com/apache/airflow/commit/61c1d6ec6ce638f8ccd76705f69e9474c308389a>`_  2021-01-22   ``Improve environment variables in GCP Memorystore system test (#13833)``
`202f66093 <https://github.com/apache/airflow/commit/202f66093ad12c293f97204b0775bef2b077cd9a>`_  2021-01-22   ``Improve environment variables in GCP Lifeciences system test (#13834)``
`70bf307f3 <https://github.com/apache/airflow/commit/70bf307f3894214c523701940b89ac0b991a3a63>`_  2021-01-21   ``Add How To Guide for Dataflow (#13461)``
`3fd5ef355 <https://github.com/apache/airflow/commit/3fd5ef355556cf0ad7896bb570bbe4b2eabbf46e>`_  2021-01-21   ``Add missing logos for integrations (#13717)``
`309788e5e <https://github.com/apache/airflow/commit/309788e5e2023c598095a4ee00df417d94b6a5df>`_  2021-01-18   ``Refactor DataprocOperators to support google-cloud-dataproc 2.0 (#13256)``
`7ec858c45 <https://github.com/apache/airflow/commit/7ec858c4523b24e7a3d6dd1d49e3813e6eee7dff>`_  2021-01-17   ``updated Google DV360 Hook to fix SDF issue (#13703)``
`ef8617ec9 <https://github.com/apache/airflow/commit/ef8617ec9d6e4b7c433a29bd388f5102a7a17c11>`_  2021-01-14   ``Support google-cloud-tasks>=2.0.0 (#13347)``
`189af5404 <https://github.com/apache/airflow/commit/189af54043a6aa6e7557bda6cf7cfca229d0efd2>`_  2021-01-13   ``Add system tests for Stackdriver operators (#13644)``
`a6f999b62 <https://github.com/apache/airflow/commit/a6f999b62e3c9aeb10ab24342674d3670a8ad259>`_  2021-01-11   ``Support google-cloud-automl >=2.1.0 (#13505)``
`947dbb73b <https://github.com/apache/airflow/commit/947dbb73bba736eb146f33117545a18fc2fd3c09>`_  2021-01-11   ``Support google-cloud-datacatalog>=3.0.0 (#13534)``
`2fb68342b <https://github.com/apache/airflow/commit/2fb68342b01da4cb5d79ac9e5c0f7687d74351f3>`_  2021-01-07   ``Replace deprecated module and operator in example_tasks.py (#13527)``
`003584bbf <https://github.com/apache/airflow/commit/003584bbf1d66a3545ad6e6fcdceb0410fc83696>`_  2021-01-05   ``Fix failing backport packages test (#13497)``
`7d1ea4cb1 <https://github.com/apache/airflow/commit/7d1ea4cb102e7d9878eeeaab5b098ae7767b844b>`_  2021-01-05   ``Replace deprecated module and operator in example_tasks.py (#13473)``
`c7d75ad88 <https://github.com/apache/airflow/commit/c7d75ad887cd12d5603563c5fa873c0e2f8975aa>`_  2021-01-05   ``Revert "Support google-cloud-datacatalog 3.0.0 (#13224)" (#13482)``
`feb84057d <https://github.com/apache/airflow/commit/feb84057d34b2f64e3b5dcbaae2d3b18f5f564e4>`_  2021-01-04   ``Support google-cloud-datacatalog 3.0.0 (#13224)``
`3a3e73998 <https://github.com/apache/airflow/commit/3a3e7399810fd399d08f136e6936743c16508fc6>`_  2021-01-04   ``Fix insert_all method of BigQueryHook to support tables without schema (#13138)``
`c33d2c06b <https://github.com/apache/airflow/commit/c33d2c06b68c8b9a5a36c965ab8be540a2dca967>`_  2021-01-02   ``Fix another pylint c-extension-no-member (#13438)``
`f6518dd6a <https://github.com/apache/airflow/commit/f6518dd6a1217d906d863fe13dc37916efd78b3e>`_  2021-01-02   ``Generalize MLEngineStartTrainingJobOperator to custom images (#13318)``
`9de712708 <https://github.com/apache/airflow/commit/9de71270838ad3cc59043f1ab0bb6ca97af13622>`_  2020-12-31   ``Support google-cloud-bigquery-datatransfer>=3.0.0 (#13337)``
`406181d64 <https://github.com/apache/airflow/commit/406181d64ac32d133523ca52f954bc50a07defc4>`_  2020-12-31   ``Add Parquet data type to BaseSQLToGCSOperator (#13359)``
`295d66f91 <https://github.com/apache/airflow/commit/295d66f91446a69610576d040ba687b38f1c5d0a>`_  2020-12-30   ``Fix Grammar in PIP warning (#13380)``
`13a9747bf <https://github.com/apache/airflow/commit/13a9747bf1d92020caa5d4dc825e096ce583f2df>`_  2020-12-28   ``Revert "Support google-cloud-tasks>=2.0.0 (#13334)" (#13341)``
`04ec45f04 <https://github.com/apache/airflow/commit/04ec45f045419ec87432ee285ac0828ab68008c3>`_  2020-12-28   ``Add DataprocCreateWorkflowTemplateOperator (#13338)``
`1f712219f <https://github.com/apache/airflow/commit/1f712219fa8971d98bc486896603ce8109c42844>`_  2020-12-28   ``Support google-cloud-tasks>=2.0.0 (#13334)``
`f4745c8ce <https://github.com/apache/airflow/commit/f4745c8ce1955c28676b5afe129a88a61aa743b9>`_  2020-12-26   ``Fix typo in example (#13321)``
`e9d65bd45 <https://github.com/apache/airflow/commit/e9d65bd4582b083914f2fc1213bea44cf41d1a08>`_  2020-12-24   ``Decode Remote Google Logs (#13115)``
`e7aeacf33 <https://github.com/apache/airflow/commit/e7aeacf335d373007a32ac65680ba6b5b19f5c9f>`_  2020-12-24   ``Add OracleToGCS Transfer (#13246)``
`323084e97 <https://github.com/apache/airflow/commit/323084e97ddacbc5512709bf0cad8f53082d16b0>`_  2020-12-24   ``Add timeout option to gcs hook methods. (#13156)``
`0b626c804 <https://github.com/apache/airflow/commit/0b626c8042b304a52d6c481fa6eb689d655f33d3>`_  2020-12-22   ``Support google-cloud-redis>=2.0.0 (#13117)``
`9042a5855 <https://github.com/apache/airflow/commit/9042a585539a18953d688fff455438f4061732d1>`_  2020-12-22   ``Add more operators to example DAGs for Cloud Tasks (#13235)``
`8c00ec89b <https://github.com/apache/airflow/commit/8c00ec89b97aa6e725379d08c8ff29a01be47e73>`_  2020-12-22   ``Support google-cloud-pubsub>=2.0.0 (#13127)``
`b26b0df5b <https://github.com/apache/airflow/commit/b26b0df5b03c4cd826fd7b2dff5771d64e18e6b7>`_  2020-12-22   ``Update compatibility with google-cloud-kms>=2.0 (#13124)``
`9a1d3820d <https://github.com/apache/airflow/commit/9a1d3820d6f1373df790da8751f25e723f9ce037>`_  2020-12-22   ``Support google-cloud-datacatalog>=1.0.0 (#13097)``
`f95b1c9c9 <https://github.com/apache/airflow/commit/f95b1c9c95c059e85ad5676daaa191929785fee2>`_  2020-12-21   ``Add regional support to dataproc workflow template operators (#12907)``
`6cf76d7ac <https://github.com/apache/airflow/commit/6cf76d7ac01270930de7f105fb26428763ee1d4e>`_  2020-12-18   ``Fix typo in pip upgrade command :( (#13148)``
`23f27c1b1 <https://github.com/apache/airflow/commit/23f27c1b1cdbcb6bb50fd2aa772aeda7151d5634>`_  2020-12-18   ``Add system tests for CloudKMSHook (#13122)``
`cddbf81b1 <https://github.com/apache/airflow/commit/cddbf81b12650ee5905b0f762c1213caa1d3a7ed>`_  2020-12-17   ``Fix Google BigQueryHook method get_schema() (#13136)``
`1259c712a <https://github.com/apache/airflow/commit/1259c712a42d69135dc389de88f79942c70079a3>`_  2020-12-17   ``Update compatibility with google-cloud-os-login>=2.0.0 (#13126)``
`bcf77586e <https://github.com/apache/airflow/commit/bcf77586eff9907fa057cf2633115d5ab3e4142b>`_  2020-12-16   ``Fix Data Catalog operators (#13096)``
`5090fb0c8 <https://github.com/apache/airflow/commit/5090fb0c8967d2d8719c6f4a468f2151395b5444>`_  2020-12-15   ``Add script to generate integrations.json (#13073)``
`b4b9cf559 <https://github.com/apache/airflow/commit/b4b9cf55970ca41fa7852ab8d25e59f4c379f8c2>`_  2020-12-14   ``Check for missing references to operator guides (#13059)``
`1c1ef7ee6 <https://github.com/apache/airflow/commit/1c1ef7ee693fead93e269dfd9774a72b6eed2e85>`_  2020-12-14   ``Add project_id to client inside BigQuery hook update_table method (#13018)``
================================================================================================  ===========  =========================================================================================

1.0.0
.....

Latest change: 2020-12-09

================================================================================================  ===========  ======================================================================================================================================================================
Commit                                                                                            Committed    Subject
================================================================================================  ===========  ======================================================================================================================================================================
`32971a1a2 <https://github.com/apache/airflow/commit/32971a1a2de1db0b4f7442ed26facdf8d3b7a36f>`_  2020-12-09   ``Updates providers versions to 1.0.0 (#12955)``
`b40dffa08 <https://github.com/apache/airflow/commit/b40dffa08547b610162f8cacfa75847f3c4ca364>`_  2020-12-08   ``Rename remaing modules to match AIP-21 (#12917)``
`9b39f2478 <https://github.com/apache/airflow/commit/9b39f24780e85f859236672e9060b2fbeee81b36>`_  2020-12-08   ``Add support for dynamic connection form fields per provider (#12558)``
`1dcd3e13f <https://github.com/apache/airflow/commit/1dcd3e13fd0a078fc9440e91b77f6f87aa60dd3b>`_  2020-12-05   ``Add support for extra links coming from the providers (#12472)``
`2037303ee <https://github.com/apache/airflow/commit/2037303eef93fd36ab13746b045d1c1fee6aa143>`_  2020-11-29   ``Adds support for Connection/Hook discovery from providers (#12466)``
`02d94349b <https://github.com/apache/airflow/commit/02d94349be3d201ce9d37d7358573c937fd010df>`_  2020-11-29   ``Don't use time.time() or timezone.utcnow() for duration calculations (#12353)``
`76bcd08dc <https://github.com/apache/airflow/commit/76bcd08dcae8d62307f5e9b8c2e182b54ed22a27>`_  2020-11-28   ``Added '@apply_defaults' decorator. (#12620)``
`e1ebfa68b <https://github.com/apache/airflow/commit/e1ebfa68b109b5993c47891cfd0b9b7e46b6d770>`_  2020-11-27   ``Add DataflowJobMessagesSensor and DataflowAutoscalingEventsSensor (#12249)``
`3fa51f94d <https://github.com/apache/airflow/commit/3fa51f94d7a17f170ddc31908d36c91f4456a20b>`_  2020-11-24   ``Add check for duplicates in provider.yaml files (#12578)``
`c34ef853c <https://github.com/apache/airflow/commit/c34ef853c890e08f5468183c03dc8f3f3ce84af2>`_  2020-11-20   ``Separate out documentation building per provider  (#12444)``
`9e3b2c554 <https://github.com/apache/airflow/commit/9e3b2c554dadf58972198e4e16f15af2f15ec37a>`_  2020-11-19   ``GCP Secrets Optional Lookup (#12360)``
`008035450 <https://github.com/apache/airflow/commit/00803545023b096b8db4fbd6eb473843096d7ce4>`_  2020-11-18   ``Update provider READMEs for 1.0.0b2 batch release (#12449)``
`7ca0b6f12 <https://github.com/apache/airflow/commit/7ca0b6f121c9cec6e25de130f86a56d7c7fbe38c>`_  2020-11-18   ``Enable Markdownlint rule MD003/heading-style/header-style (#12427) (#12438)``
`8d0950646 <https://github.com/apache/airflow/commit/8d09506464c8480fa42e8bfe6a36c6f631cd23f6>`_  2020-11-18   ``Fix download method in GCSToBigQueryOperator (#12442)``
`2c0920fba <https://github.com/apache/airflow/commit/2c0920fba5d2f05d2e29cead91127686af277ec2>`_  2020-11-17   ``Adds mechanism for provider package discovery. (#12383)``
`2cda2f2a0 <https://github.com/apache/airflow/commit/2cda2f2a0a94e5aaed87f0998fa57b4f8bff5e43>`_  2020-11-17   ``Add missing pre-commit definition - provider-yamls (#12393)``
`80a957f14 <https://github.com/apache/airflow/commit/80a957f142f260daed262b8e93a4d02c12cfeabc>`_  2020-11-17   ``Add Dataflow sensors - job metrics (#12039)``
`ae7cb4a1e <https://github.com/apache/airflow/commit/ae7cb4a1e2a96351f1976cf5832615e24863e05d>`_  2020-11-17   ``Update wrong commit hash in backport provider changes (#12390)``
`917e6c442 <https://github.com/apache/airflow/commit/917e6c4424985271c53dd8c413b211896ee55726>`_  2020-11-16   ``Add provide_file_and_upload to GCSHook (#12310)``
`cfa4ecfeb <https://github.com/apache/airflow/commit/cfa4ecfeb02661f40b4778733384ac085fb5f04b>`_  2020-11-15   ``Add DataflowJobStatusSensor and support non-blocking execution of jobs (#11726)``
`6889a333c <https://github.com/apache/airflow/commit/6889a333cff001727eb0a66e375544a28c9a5f03>`_  2020-11-15   ``Improvements for operators and hooks ref docs (#12366)``
`7825e8f59 <https://github.com/apache/airflow/commit/7825e8f59034645ab3247229be83a3aa90baece1>`_  2020-11-13   ``Docs installation improvements (#12304)``
`32b59f835 <https://github.com/apache/airflow/commit/32b59f8350f55793df6838a32de662a80483ecda>`_  2020-11-12   ``Fixes the sending of an empty list to BigQuery 'list_rows' (#12307)``
`250436d96 <https://github.com/apache/airflow/commit/250436d962c8c950d38c1eb5e54a998891648cc9>`_  2020-11-10   ``Fix spelling in Python files (#12230)``
`502ba309e <https://github.com/apache/airflow/commit/502ba309ea470943f0e99c634269e3d2d13ce6ca>`_  2020-11-10   ``Enable Markdownlint rule - MD022/blanks-around-headings (#12225)``
`dd2095f4a <https://github.com/apache/airflow/commit/dd2095f4a8b07c9b1a4c279a3578cd1e23b71a1b>`_  2020-11-10   ``Simplify string expressions & Use f-string (#12216)``
`f37c6e6fc <https://github.com/apache/airflow/commit/f37c6e6fce8b704f5af28caa16d0ed7d873a0e4a>`_  2020-11-10   ``Add Compute Engine SSH hook (#9879)``
`85a18e13d <https://github.com/apache/airflow/commit/85a18e13d9dec84275283ff69e34704b60d54a75>`_  2020-11-09   ``Point at pypi project pages for cross-dependency of provider packages (#12212)``
`59eb5de78 <https://github.com/apache/airflow/commit/59eb5de78c70ee9c7ae6e4cba5c7a2babb8103ca>`_  2020-11-09   ``Update provider READMEs for up-coming 1.0.0beta1 releases (#12206)``
`61feb6ec4 <https://github.com/apache/airflow/commit/61feb6ec453f8dda1a0e1fe3ebcc0f1e3224b634>`_  2020-11-09   ``Provider's readmes generated for elasticsearch and google packages (#12194)``
`b2a28d159 <https://github.com/apache/airflow/commit/b2a28d1590410630d66966aa1f2b2a049a8c3b32>`_  2020-11-09   ``Moves provider packages scripts to dev (#12082)``
`fcb6b00ef <https://github.com/apache/airflow/commit/fcb6b00efef80c81272a30cfc618202a29e0c6a9>`_  2020-11-08   ``Add authentication to AWS with Google credentials (#12079)``
`2ef3b7ef8 <https://github.com/apache/airflow/commit/2ef3b7ef8cafe3bdc8bf8db70fbc519b98576366>`_  2020-11-08   ``Fix ERROR - Object of type 'bytes' is not JSON serializable when using store_to_xcom_key parameter (#12172)``
`0caec9fd3 <https://github.com/apache/airflow/commit/0caec9fd32bee2b3036b5d7bdcb56bd6a3b9dccf>`_  2020-11-06   ``Dataflow - add waiting for successful job cancel (#11501)``
`cf9437d79 <https://github.com/apache/airflow/commit/cf9437d79f9658d1309e4bfe847fe63d52ec7b99>`_  2020-11-06   ``Simplify string expressions (#12123)``
`91a64db50 <https://github.com/apache/airflow/commit/91a64db505e50712cd53928b4f2b84aece3cc1c0>`_  2020-11-04   ``Format all files (without excepions) by black (#12091)``
`fd3db778e <https://github.com/apache/airflow/commit/fd3db778e715d0f164dda7ee8f672d477a323291>`_  2020-11-04   ``Add server side cursor support for postgres to GCS operator (#11793)``
`f1f194026 <https://github.com/apache/airflow/commit/f1f1940261744b4fdb67b0b5654488494efa9c64>`_  2020-11-04   ``Add DataflowStartSQLQuery operator (#8553)``
`41bf172c1 <https://github.com/apache/airflow/commit/41bf172c1dc75099f4f9d8b3f3350b4b1f523ef9>`_  2020-11-04   ``Simplify string expressions (#12093)``
`5f5244b74 <https://github.com/apache/airflow/commit/5f5244b74df93cadbb99643cec76281460ca4411>`_  2020-11-04   ``Add template fields renderers to Biguery and Dataproc operators (#12067)``
`4e8f9cc8d <https://github.com/apache/airflow/commit/4e8f9cc8d02b29c325b8a5a76b4837671bdf5f68>`_  2020-11-03   ``Enable Black - Python Auto Formmatter (#9550)``
`8c42cf1b0 <https://github.com/apache/airflow/commit/8c42cf1b00c90f0d7f11b8a3a455381de8e003c5>`_  2020-11-03   ``Use PyUpgrade to use Python 3.6 features (#11447)``
`45ae145c2 <https://github.com/apache/airflow/commit/45ae145c25a19b4185c33ac0c4da920324b3987e>`_  2020-11-03   ``Log BigQuery job id in insert method of BigQueryHook (#12056)``
`e324b37a6 <https://github.com/apache/airflow/commit/e324b37a67e32c368df50604a00160d7766b5c33>`_  2020-11-03   ``Add job name and progress logs to Cloud Storage Transfer Hook (#12014)``
`6071fdd58 <https://github.com/apache/airflow/commit/6071fdd58470bb2a6c23fc16481e292b7247d0bb>`_  2020-11-02   ``Improve handling server errors in DataprocSubmitJobOperator (#11947)``
`2f703df12 <https://github.com/apache/airflow/commit/2f703df12dfd6511722ff9a82d5a569d092fccc2>`_  2020-10-30   ``Add SalesforceToGcsOperator (#10760)``
`e5713e00b <https://github.com/apache/airflow/commit/e5713e00b3afcba6f78006ec0e360da317858e4d>`_  2020-10-29   ``Add drain option when canceling Dataflow pipelines (#11374)``
`37eaac3c5 <https://github.com/apache/airflow/commit/37eaac3c5dc93804413c10a6ca124fd7831befc0>`_  2020-10-29   ``The PRs which are not approved run subset of tests (#11828)``
`79cb77199 <https://github.com/apache/airflow/commit/79cb771992279d40ddd9eb6b0277382313a32898>`_  2020-10-28   ``Fixing re pattern and changing to use a single character class. (#11857)``
`5a439e84e <https://github.com/apache/airflow/commit/5a439e84eb6c0544dc6c3d6a9f4ceeb2172cd5d0>`_  2020-10-26   ``Prepare providers release 0.0.2a1 (#11855)``
`240c7d4d7 <https://github.com/apache/airflow/commit/240c7d4d72aac8f6aab98f5913e8f54c4f1372ff>`_  2020-10-26   ``Google Memcached hooks - improve protobuf messages handling (#11743)``
`8afdb6ac6 <https://github.com/apache/airflow/commit/8afdb6ac6a7997cb14806bc2734c81c00ed8da97>`_  2020-10-26   ``Fix spellings (#11825)``
`872b1566a <https://github.com/apache/airflow/commit/872b1566a11cb73297e657ff325161721b296574>`_  2020-10-25   ``Generated backport providers readmes/setup for 2020.10.29 (#11826)``
`6ce855af1 <https://github.com/apache/airflow/commit/6ce855af118daeaa4c249669079ab9d9aad23945>`_  2020-10-24   ``Fix spelling (#11821)``
`483068745 <https://github.com/apache/airflow/commit/48306874538eea7cfd42358d5ebb59705204bfc4>`_  2020-10-24   ``Use Python 3 style super classes (#11806)``
`727c739af <https://github.com/apache/airflow/commit/727c739afb565d4d394a8faedc969334cb8e738e>`_  2020-10-22   ``Improve Cloud Memorystore for Redis example (#11735)``
`1da8379c9 <https://github.com/apache/airflow/commit/1da8379c913843834353b44861c62f332a461bdf>`_  2020-10-22   ``Fix static checks after merging #10121 (#11737)``
`91503308c <https://github.com/apache/airflow/commit/91503308c723b186ce6f4026f2a3e2c21030f6e5>`_  2020-10-22   ``Add Google Cloud Memorystore Memcached Operators (#10121)``
`950c16d0b <https://github.com/apache/airflow/commit/950c16d0b0ab67bb7af11909de751029faf0313a>`_  2020-10-21   ``Retry requests in case of error in Google ML Engine Hook (#11712)``
`2bfc53b5e <https://github.com/apache/airflow/commit/2bfc53b5eb67406d418371b74dc9bc5a07be238e>`_  2020-10-21   ``Fix doc errors in google provider files. (#11713)``
`53e606210 <https://github.com/apache/airflow/commit/53e6062105be0ae1761a354e2055eb0779d12e73>`_  2020-10-21   ``Enforce strict rules for yamllint (#11709)``
`349b0811c <https://github.com/apache/airflow/commit/349b0811c3022605426ba57d30936240a7c2848a>`_  2020-10-20   ``Add D200 pydocstyle check (#11688)``
`2d854c350 <https://github.com/apache/airflow/commit/2d854c3505ccad66e9a7d94267e51bed800433c2>`_  2020-10-19   ``Add service_account to Google ML Engine operator (#11619)``
`46a121fb7 <https://github.com/apache/airflow/commit/46a121fb7b77c0964e053b58750e2d8bc2bd0b2a>`_  2020-10-18   ``docs: Update Bigquery clustering docstrings (#11232)``
`49c58147f <https://github.com/apache/airflow/commit/49c58147fed8a52869d0b0ecc00c102c11972ad0>`_  2020-10-18   ``Strict type checking for provider Google (#11609)``
`0823d46a7 <https://github.com/apache/airflow/commit/0823d46a7f267f2e45195a175021825367938add>`_  2020-10-16   ``Add type annotations for AWS operators and hooks (#11434)``
`3c10ca650 <https://github.com/apache/airflow/commit/3c10ca6504be37fabff9a10caefea3fe4df31a02>`_  2020-10-16   ``Add DataflowStartFlexTemplateOperator (#8550)``
`8865d14df <https://github.com/apache/airflow/commit/8865d14df4d58dd5f1a4d2ff81c77469959f175a>`_  2020-10-16   ``Strict type checking for provider google cloud  (#11548)``
`16e712971 <https://github.com/apache/airflow/commit/16e7129719f1c0940aef2a93bed81368e997a746>`_  2020-10-13   ``Added support for provider packages for Airflow 2.0 (#11487)``
`06141d6d0 <https://github.com/apache/airflow/commit/06141d6d01398115e5e54c5766a46ae5514ba2f7>`_  2020-10-12   ``Google cloud operator strict type check (#11450)``
`d305876be <https://github.com/apache/airflow/commit/d305876bee328287ff391a29cc1cd632468cc731>`_  2020-10-12   ``Remove redundant None provided as default to dict.get() (#11448)``
`1845cd11b <https://github.com/apache/airflow/commit/1845cd11b77f302777ab854e84bef9c212c604a0>`_  2020-10-11   ``Strict type check for google ads and cloud hooks (#11390)``
`bd204bb91 <https://github.com/apache/airflow/commit/bd204bb91b4bc069284f9a44757c6baba8884140>`_  2020-10-11   ``Optionally set null marker in csv exports in BaseSQLToGCSOperator (#11409)``
`75071831b <https://github.com/apache/airflow/commit/75071831baa936d292354f98aac46cd808a4b2b8>`_  2020-10-10   ``Remove redundant parentheses from Python files (#10967)``
`8baf657fc <https://github.com/apache/airflow/commit/8baf657fc2b21a601b99b752e4f1176bf8a934ce>`_  2020-10-09   ``Fix regression in DataflowTemplatedJobStartOperator (#11167)``
`b0fcf6755 <https://github.com/apache/airflow/commit/b0fcf675595494b306800e1a516548dc0dc671f8>`_  2020-10-07   ``Add AzureFileShareToGCSOperator (#10991)``
`47b05a87f <https://github.com/apache/airflow/commit/47b05a87f004dc273a4757ba49f03808a86f77e7>`_  2020-10-07   ``Improve handling of job_id in BigQuery operators (#11287)``
`0a0e1af80 <https://github.com/apache/airflow/commit/0a0e1af80038ef89974c3c8444461fe867945daa>`_  2020-10-03   ``Fix Broken Markdown links in Providers README TOC (#11249)``
`ca4238eb4 <https://github.com/apache/airflow/commit/ca4238eb4d9a2aef70eb641343f59ee706d27d13>`_  2020-10-02   ``Fixed month in backport packages to October (#11242)``
`5220e4c38 <https://github.com/apache/airflow/commit/5220e4c3848a2d2c81c266ef939709df9ce581c5>`_  2020-10-02   ``Prepare Backport release 2020.09.07 (#11238)``
`cb52fb0ae <https://github.com/apache/airflow/commit/cb52fb0ae1de1f1140babaed0e97299e4aaf96bf>`_  2020-09-27   ``Add example DAG and system test for MySQLToGCSOperator (#10990)``
`99accec29 <https://github.com/apache/airflow/commit/99accec29d71b0a57fd4e90151b9d4d10321be07>`_  2020-09-25   ``Fix incorrect Usage of Optional[str] & Optional[int] (#11141)``
`e3f96ce7a <https://github.com/apache/airflow/commit/e3f96ce7a8ac098aeef5e9930e6de6c428274d57>`_  2020-09-24   ``Fix incorrect Usage of Optional[bool] (#11138)``
`daf8f3108 <https://github.com/apache/airflow/commit/daf8f31080f06c044b4336071bd383bbbcdc6085>`_  2020-09-23   ``Add template fields renderers for better UI rendering (#11061)``
`f3e87c503 <https://github.com/apache/airflow/commit/f3e87c503081a3085dff6c7352640d7f08beb5bc>`_  2020-09-22   ``Add D202 pydocstyle check (#11032)``
`cb979f9f2 <https://github.com/apache/airflow/commit/cb979f9f213bb3c9835a3dc924f84a07f5387378>`_  2020-09-22   ``Get Airflow configs with sensitive data from CloudSecretManagerBackend (#11024)``
`76545bb3d <https://github.com/apache/airflow/commit/76545bb3d6fa82ce8eae072dbc74a3b76d8fd53c>`_  2020-09-16   ``Add example dag and system test for S3ToGCSOperator (#10951)``
`22c631625 <https://github.com/apache/airflow/commit/22c631625fd68abe280528f33b7cfd7603ebf66c>`_  2020-09-16   ``Fix more docs spellings (#10965)``
`12a652f53 <https://github.com/apache/airflow/commit/12a652f5344c7f03c3d780556ca1829b235fdb2d>`_  2020-09-13   ``Fix parameter name collision in AutoMLBatchPredictOperator #10723 (#10869)``
`41a62735e <https://github.com/apache/airflow/commit/41a62735edcebbd9c39e505280646ef5d25aa1d5>`_  2020-09-11   ``Add on_kill method to BigQueryInsertJobOperator (#10866)``
`3e91da56e <https://github.com/apache/airflow/commit/3e91da56e8c63a90dc859d8996a896b5d9f8cd43>`_  2020-09-11   ``fix typo in firebase/example_filestore DAG (#10875)``
`68cc7273b <https://github.com/apache/airflow/commit/68cc7273bf0c0f562748b5f663da5c12d2cba6a7>`_  2020-09-10   ``Add on_kill method to DataprocSubmitJobOperator (#10847)``
`f92095721 <https://github.com/apache/airflow/commit/f92095721450c14605c986e165544a7bfb712a3d>`_  2020-09-10   ``Fix and remove some more typos from spelling_wordlist.txt (#10845)``
`9549274d1 <https://github.com/apache/airflow/commit/9549274d110f689a0bd709db829a4d69e274eed9>`_  2020-09-09   ``Upgrade black to 20.8b1 (#10818)``
`078bfaf60 <https://github.com/apache/airflow/commit/078bfaf60adc5aebac8c347e7f6e5339ab9b56c0>`_  2020-09-08   ``Extract missing gcs_to_local example DAG from gcs example (#10767)``
`10ce31127 <https://github.com/apache/airflow/commit/10ce31127f1ff87176158935925afce46a989917>`_  2020-09-08   ``Deprecate using global as the default region in Google Dataproc operators and hooks (#10772)``
`f14f37971 <https://github.com/apache/airflow/commit/f14f3797163cc45fdcdabfb36ee7d638f70e470d>`_  2020-09-07   ``[AIRFLOW-10672] Refactor BigQueryToGCSOperator to use new method (#10773)``
`c8ee45568 <https://github.com/apache/airflow/commit/c8ee4556851c36b3b6e644a7746a49583dd53db1>`_  2020-09-07   ``Refactor DataprocCreateCluster operator to use simpler interface (#10403)``
`ece685b5b <https://github.com/apache/airflow/commit/ece685b5b895ad1175440b49bf9e620dffd8248d>`_  2020-09-05   ``Asynchronous execution of Dataproc jobs with a Sensor (#10673)``
`6e3d7b63d <https://github.com/apache/airflow/commit/6e3d7b63d3b34c34f8b38a7b41f4a5876e1f731f>`_  2020-09-04   ``Add masterConfig parameter to MLEngineStartTrainingJobOperator (#10578)``
`804548d58 <https://github.com/apache/airflow/commit/804548d58f2036fd4516824a38d0639ba5d5ab0e>`_  2020-09-01   ``Add Dataprep operators (#10304)``
`11c00bc82 <https://github.com/apache/airflow/commit/11c00bc820483691a87cdb16d519dce8dc57c40e>`_  2020-08-30   ``Fix typos: duplicated "the" (#10647)``
`2ca615cff <https://github.com/apache/airflow/commit/2ca615cffefe97dfa38e1b7f60d9ed33c6628992>`_  2020-08-29   ``Update Google Cloud branding (#10642)``
`1b533f617 <https://github.com/apache/airflow/commit/1b533f617e2e0200597d114d7570f6c0d69da1a0>`_  2020-08-28   ``Fix broken master - DLP (#10635)``
`5ae82a56d <https://github.com/apache/airflow/commit/5ae82a56dab599de44f1be7027cecc4ef86f7bb6>`_  2020-08-28   ``Fix Google DLP example and improve ops idempotency (#10608)``
`3867f7662 <https://github.com/apache/airflow/commit/3867f7662559761864ec4e7be26b776c64c2f199>`_  2020-08-28   ``Update Google Cloud branding (#10615)``
`91ff31ad1 <https://github.com/apache/airflow/commit/91ff31ad1021235bd21c87ad9dbc0b216a908671>`_  2020-08-27   ``Documentation for Google Cloud Data Loss Prevention (#8201) (#9651)``
`fdd9b6f65 <https://github.com/apache/airflow/commit/fdd9b6f65b608c516b8a062b058972d9a45ec9e3>`_  2020-08-25   ``Enable Black on Providers Packages (#10543)``
`d76026545 <https://github.com/apache/airflow/commit/d7602654526fdd2876466371404784bd17cfe0d2>`_  2020-08-25   ``PyDocStyle: No whitespaces allowed surrounding docstring text (#10533)``
`d1bce91bb <https://github.com/apache/airflow/commit/d1bce91bb21d5a468fa6a0207156c28fe1ca6513>`_  2020-08-25   ``PyDocStyle: Enable D403: Capitalized first word of docstring (#10530)``
`866701c80 <https://github.com/apache/airflow/commit/866701c8019f49dcb02c9696e4f6e9ce67d13ca6>`_  2020-08-25   ``Fix typo in "Cloud" (#10534)``
`47265e7b5 <https://github.com/apache/airflow/commit/47265e7b58bc28bcbbffc981442b6cc27a3af39c>`_  2020-08-24   ``Fix typo in PostgresHook (#10529)``
`3696c34c2 <https://github.com/apache/airflow/commit/3696c34c28c6bc7b442deab999d9ecba24ed0e34>`_  2020-08-24   ``Fix typo in the word "release" (#10528)``
`2f2d8dbfa <https://github.com/apache/airflow/commit/2f2d8dbfafefb4be3dd80f22f31c649c8498f148>`_  2020-08-25   ``Remove all "noinspection" comments native to IntelliJ (#10525)``
`3734876d9 <https://github.com/apache/airflow/commit/3734876d9898067ee933b84af522d53df6160d7f>`_  2020-08-24   ``Implement impersonation in google operators (#10052)``
`b0598b535 <https://github.com/apache/airflow/commit/b0598b5351d2d027286e2333231b6c0c0704dba2>`_  2020-08-24   ``Add support for creating multiple replicated clusters in Bigtable hook and operator (#10475)``
`ee7ca128a <https://github.com/apache/airflow/commit/ee7ca128a17937313566f2badb6cc569c614db94>`_  2020-08-22   ``Fix broken Markdown refernces in Providers README (#10483)``
`515cc72c9 <https://github.com/apache/airflow/commit/515cc72c995429c8c007f853ade385d79fcbac90>`_  2020-08-22   ``Fix typo in timed_out (#10459)``
`7c206a82a <https://github.com/apache/airflow/commit/7c206a82a6f074abcc4898a005ecd2c84a920054>`_  2020-08-22   ``Replace assigment with Augmented assignment (#10468)``
`88c7d2e52 <https://github.com/apache/airflow/commit/88c7d2e526af4994066f65f830e2fa8edcbbce2e>`_  2020-08-21   ``Dataflow operators don't not always create a virtualenv (#10373)``
`083c3c129 <https://github.com/apache/airflow/commit/083c3c129bc3458d410f5ff37d7f5a9a7ad548b7>`_  2020-08-18   ``Simplified GCSTaskHandler configuration (#10365)``
`1ae5bdf23 <https://github.com/apache/airflow/commit/1ae5bdf23e3ac7cca05325ef8b255a7cf067e18e>`_  2020-08-17   ``Add test for GCSTaskHandler (#9600) (#9861)``
`e195a980b <https://github.com/apache/airflow/commit/e195a980bc8e9d42f3eb4ac134950977b9e5158f>`_  2020-08-16   ``Add type annotations for mlengine_operator_utils (#10297)``
`382c1011b <https://github.com/apache/airflow/commit/382c1011b6bcebd22760e2f98419281ef1a09d1b>`_  2020-08-16   ``Add Bigtable Update Instance Hook/Operator (#10340)``
`bfa5a8d5f <https://github.com/apache/airflow/commit/bfa5a8d5f10458c14d380c4042ecfbac627d0639>`_  2020-08-15   ``CI: Fix failing docs-build (#10342)``
`be46d20fb <https://github.com/apache/airflow/commit/be46d20fb431cc1d91c935e8894dfc7756c18993>`_  2020-08-15   ``Improve idempotency of BigQueryInsertJobOperator (#9590)``
`47387a69e <https://github.com/apache/airflow/commit/47387a69e623676b57b6d42ff07e729da2d21bff>`_  2020-08-14   ``Catch Permission Denied exception when getting secret from GCP Secret Manager. (#10326)``
`2f0613b0c <https://github.com/apache/airflow/commit/2f0613b0c2fdf176d9f13a8cd12162c60c64b644>`_  2020-08-13   ``Implement Google BigQuery Table Partition Sensor (#10218)``
`f6734b3b8 <https://github.com/apache/airflow/commit/f6734b3b850d33d3712763f93c114e80f5af9ffb>`_  2020-08-12   ``Enable Sphinx spellcheck for doc generation (#10280)``
`8f8db8959 <https://github.com/apache/airflow/commit/8f8db8959e526be54d700845d36ee9f315bae2ea>`_  2020-08-12   ``DbApiHook: Support kwargs in get_pandas_df (#9730)``
`ef088314f <https://github.com/apache/airflow/commit/ef088314f8f1b29ac636a7584cf9dda04b1df816>`_  2020-08-09   ``Added DataprepGetJobsForJobGroupOperator (#10246)``
`b43f90abf <https://github.com/apache/airflow/commit/b43f90abf4c7219d5d59cccb0514256bd3f2fdc7>`_  2020-08-09   ``Fix various typos in the repo (#10263)``
`c29533888 <https://github.com/apache/airflow/commit/c29533888fadd40f5e9ce63e728bd8691182e542>`_  2020-08-08   ``Add labels param to Google MLEngine Operators (#10222)``
`cdec30125 <https://github.com/apache/airflow/commit/cdec3012542b45d23a05f62d69110944ba542e2a>`_  2020-08-07   ``Add correct signature to all operators and sensors (#10205)``
`eff0f0321 <https://github.com/apache/airflow/commit/eff0f03210d30a4aed9ed457eaaea9c9f05d54d1>`_  2020-08-06   `` Update guide for Google Cloud Secret Manager Backend (#10172)``
`24c8e4c2d <https://github.com/apache/airflow/commit/24c8e4c2d6e359ecc2c7d6275dccc68de4a82832>`_  2020-08-06   ``Changes to all the constructors to remove the args argument (#10163)``
`010322692 <https://github.com/apache/airflow/commit/010322692e6e3f0adc156f0beb81e267da0e97bb>`_  2020-08-06   ``Improve handling Dataproc cluster creation with ERROR state (#9593)``
`1437cb749 <https://github.com/apache/airflow/commit/1437cb74955f4e10af5d70ebadde1e6b163fb9b7>`_  2020-08-04   ``Add correct signatures for operators in google provider package (#10144)``
`6efa1b9cb <https://github.com/apache/airflow/commit/6efa1b9cb763ae0bdbc884a54d24dbdc39d9e3a6>`_  2020-08-03   ``Add additional Cloud Datastore operators (#10032)``
`27020f8e5 <https://github.com/apache/airflow/commit/27020f8e588575d53e63f9f9daecd3a522656644>`_  2020-08-03   ``Add try clause to DataFusionHook.wait_for_pipeline_state (#10031)``
`4e3799fec <https://github.com/apache/airflow/commit/4e3799fec4c23d0f43603a0489c5a6158aeba035>`_  2020-08-02   ``[AIRFLOW-4541] Replace os.mkdirs usage with pathlib.Path(path).mkdir (#10117)``
`85c56b173 <https://github.com/apache/airflow/commit/85c56b1737c2bf61751836571300445c0aebae1a>`_  2020-08-02   ``Add missing params to GCP Pub/Sub creation_subscription (#10106)``
`b79466c12 <https://github.com/apache/airflow/commit/b79466c12f3ae717c31804acc2e9ffcd60f9611c>`_  2020-08-02   ``Fix sensor not providing arguments for GCSHook (#10074)``
`4ee35d027 <https://github.com/apache/airflow/commit/4ee35d027988c6456767faeb108a7f686d5117f2>`_  2020-08-02   ``Fix hook not passing gcp_conn_id to base class (#10075)``
`aeea71274 <https://github.com/apache/airflow/commit/aeea71274d4527ff2351102e94aa38bda6099e7f>`_  2020-08-02   ``Remove 'args' parameter from provider operator constructors (#10097)``
`4c84661ad <https://github.com/apache/airflow/commit/4c84661adb5bb5c581bb4193b4c7e935cbe07758>`_  2020-07-31   ``Split Display Video 360 example into smaler DAGs (#10077)``
`59cbff087 <https://github.com/apache/airflow/commit/59cbff0874dd5318cda4b9ce7b7eeb1aad1dad4d>`_  2020-07-29   ``Fix docstrings in BigQueryGetDataOperator (#10042)``
`81b87d48e <https://github.com/apache/airflow/commit/81b87d48ed002d7a7f7bcb72a58e82d40a176fe2>`_  2020-07-27   ``Add unit tests for GcpBodyFieldSanitizer in Google providers (#9996)``
`7d24b088c <https://github.com/apache/airflow/commit/7d24b088cd736cfa18f9214e4c9d6ce2d5865f3d>`_  2020-07-25   ``Stop using start_date in default_args in example_dags (2) (#9985)``
`8b10a4b35 <https://github.com/apache/airflow/commit/8b10a4b35e45d536a6475bfe1491ee75fad50186>`_  2020-07-25   ``Stop using start_date in default_args in example_dags (#9982)``
`ef98edf4d <https://github.com/apache/airflow/commit/ef98edf4da2d9b74d5cf5b21e81577b3151edb79>`_  2020-07-23   ``Add more information about using GoogleAdsHook (#9951)``
`33f0cd265 <https://github.com/apache/airflow/commit/33f0cd2657b2e77ea3477e0c93f13f1474be628e>`_  2020-07-22   ``apply_default keeps the function signature for mypy (#9784)``
`39a0288a4 <https://github.com/apache/airflow/commit/39a0288a47536dfd9b651ecd075887d3e45fcfc4>`_  2020-07-22   ``Add Google Authentication for experimental API (#9848)``
`c2db0dfeb <https://github.com/apache/airflow/commit/c2db0dfeb13ee679bf4d7b57874f0fcb39c0f0ed>`_  2020-07-22   ``More strict rules in mypy (#9705) (#9906)``
`c4244e18b <https://github.com/apache/airflow/commit/c4244e18bb894eb2180b8972052e56110fe5cbc9>`_  2020-07-22   ``Fix calling 'get_client' in BigQueryHook.table_exists (#9916)``
`5eacc1642 <https://github.com/apache/airflow/commit/5eacc164201a121cd06126aff613cbe0919d35cc>`_  2020-07-22   ``Add support for impersonation in GCP hooks (#9915)``
`1cfdebf5f <https://github.com/apache/airflow/commit/1cfdebf5f8841d61a11540b88c7913686e89e085>`_  2020-07-21   ``Fix insert_job method of BigQueryHook (#9899)``
`c8c52e69c <https://github.com/apache/airflow/commit/c8c52e69c8d9cc1f26f63d95aecc0a6498d40b6f>`_  2020-07-21   ``Remove type hint causing DeprecationWarning in Firestore operators (#9819)``
`eb6f1d1cf <https://github.com/apache/airflow/commit/eb6f1d1cf0503fa763c0d8d34a2fe16efb390b9c>`_  2020-07-16   ``Fix typo in datafusion operator (#9859)``
`b01d95ec2 <https://github.com/apache/airflow/commit/b01d95ec22b01ed79123178acd74ef40d57aaa7c>`_  2020-07-15   ``Change DAG.clear to take dag_run_state (#9824)``
`6d65c15d1 <https://github.com/apache/airflow/commit/6d65c15d156a41d5e735e44a1170426559a17d1f>`_  2020-07-15   ``Add guide for AI Platform (previously Machine Learning Engine) Operators  (#9798)``
`770de53eb <https://github.com/apache/airflow/commit/770de53eb57bd57ffc555ad15b18f0c058dbebe7>`_  2020-07-15   ``BigQueryTableExistenceSensor needs to specify keyword arguments (#9832)``
`2d8dbacdf <https://github.com/apache/airflow/commit/2d8dbacdf6c19a598a7f55bcf65e28703aed6201>`_  2020-07-15   ``Add CloudVisionDeleteReferenceImageOperator  (#9698)``
`9f017951b <https://github.com/apache/airflow/commit/9f017951b94d9bf52b5ee66d72aa8dd822f07269>`_  2020-07-15   ``Add Google Deployment Manager Hook (#9159)``
`ed5004cca <https://github.com/apache/airflow/commit/ed5004cca753650dc222fbb8e67573938c6c16d9>`_  2020-07-14   ``Allow 'replace' flag in gcs_to_gcs operator. (#9667)``
`553bb7af7 <https://github.com/apache/airflow/commit/553bb7af7cb7a50f7141b5b89297713cee6d19f6>`_  2020-07-13   ``Keep functions signatures in decorators (#9786)``
`68925904e <https://github.com/apache/airflow/commit/68925904e49aac6968defb6834863f4e6347fe59>`_  2020-07-13   ``Add multiple file upload functionality to GCS hook (#8849)``
`1de78e8f9 <https://github.com/apache/airflow/commit/1de78e8f97f48f8f4abd167a0120ffab8af6127a>`_  2020-07-12   ``Add Google Stackdriver link (#9765)``
`092d33f29 <https://github.com/apache/airflow/commit/092d33f298a7dbb871b1e1b4c17aad3989e89b79>`_  2020-07-11   ``Fix StackdriverTaskHandler + add system tests (#9761)``
`b2305660f <https://github.com/apache/airflow/commit/b2305660f0eb55ebd31fdc7fe4e8aeed8c1f8c00>`_  2020-07-09   ``Update example DAG for AI Platform operators (#9727)``
`23f80f34a <https://github.com/apache/airflow/commit/23f80f34adec86da24e4896168c53d213d01a7f6>`_  2020-07-08   ``Move gcs & wasb task handlers to their respective provider packages (#9714)``
`44d4ae809 <https://github.com/apache/airflow/commit/44d4ae809c1e3784ff95b6a5e95113c3412e56b3>`_  2020-07-06   ``Upgrade to latest pre-commit checks (#9686)``
`a79e2d4c4 <https://github.com/apache/airflow/commit/a79e2d4c4aa105f3fac5ae6a28e29af9cd572407>`_  2020-07-06   ``Move provider's log task handlers to the provider package (#9604)``
`cd3d9d934 <https://github.com/apache/airflow/commit/cd3d9d93402f06a08f35e3586802f11a18c4f1f3>`_  2020-07-02   ``Fix using .json template extension in GMP operators (#9566)``
`4799af30e <https://github.com/apache/airflow/commit/4799af30ee02c596647d1538854769124f9f4961>`_  2020-06-30   ``Extend BigQuery example with include clause (#9572)``
`e33f1a12d <https://github.com/apache/airflow/commit/e33f1a12d72ac234e4897f44b326a332acf85901>`_  2020-06-30   ``Add template_ext to BigQueryInsertJobOperator (#9568)``
`40add26d4 <https://github.com/apache/airflow/commit/40add26d459c2511a6d9d305ae7300f0d6104211>`_  2020-06-29   ``Remove almost all references to airflow.contrib (#9559)``
`c420dbd6e <https://github.com/apache/airflow/commit/c420dbd6e13e17867eb4ccc4271b37966310ac0f>`_  2020-06-27   ``Bump Pylint to 2.5.3 (#9294)``
`0051c89cb <https://github.com/apache/airflow/commit/0051c89cba02d55236c913ce0110f7d5111ba436>`_  2020-06-26   ``nitpick fix (#9527)``
`87fdbd070 <https://github.com/apache/airflow/commit/87fdbd0708d942af98d35604fe5962962e25d246>`_  2020-06-25   ``Use literal syntax instead of function calls to create data structure (#9516)``
`7256f4caa <https://github.com/apache/airflow/commit/7256f4caa226f8f8632d6e2d38d8c94cb3250a6f>`_  2020-06-22   ``Pylint fixes and deprecation of rare used methods in Connection (#9419)``
`e13a14c87 <https://github.com/apache/airflow/commit/e13a14c8730f4f633d996dd7d3468fe827136a84>`_  2020-06-21   ``Enable & Fix Whitespace related PyDocStyle Checks (#9458)``
`5b680e27e <https://github.com/apache/airflow/commit/5b680e27e8118861ef484c00a4b87c6885b0a518>`_  2020-06-19   ``Don't use connection to store task handler credentials (#9381)``
`d0e7db402 <https://github.com/apache/airflow/commit/d0e7db4024806af35e3c9a2cae460fdeedd4d2ec>`_  2020-06-19   ``Fixed release number for fresh release (#9408)``
`416334e2e <https://github.com/apache/airflow/commit/416334e2ecd21d8a532af6102f1cfa9ac921a97a>`_  2020-06-19   ``Properly propagated warnings in operators (#9348)``
`12af6a080 <https://github.com/apache/airflow/commit/12af6a08009b8776e00d8a0aab92363eb8c4e8b1>`_  2020-06-19   ``Final cleanup for 2020.6.23rc1 release preparation (#9404)``
`c7e5bce57 <https://github.com/apache/airflow/commit/c7e5bce57fe7f51cefce4f8a41ce408ac5675d13>`_  2020-06-19   ``Prepare backport release candidate for 2020.6.23rc1 (#9370)``
`4e09c6442 <https://github.com/apache/airflow/commit/4e09c64423bfaabd02a18b5fe7757dc15451ab73>`_  2020-06-18   ``Adds GCP Secret Manager Hook (#9368)``
`40bf8f28f <https://github.com/apache/airflow/commit/40bf8f28f97f17f40d993d207ea740eba54593ee>`_  2020-06-18   ``Detect automatically the lack of reference to the guide in the operator descriptions (#9290)``
`f6bd817a3 <https://github.com/apache/airflow/commit/f6bd817a3aac0a16430fc2e3d59c1f17a69a15ac>`_  2020-06-16   ``Introduce 'transfers' packages (#9320)``
`639972d99 <https://github.com/apache/airflow/commit/639972d995d848b16a3f283576efdbde28b8fdef>`_  2020-06-16   ``Add support for latest Apache Beam SDK in Dataflow operators (#9323)``
`1459970b3 <https://github.com/apache/airflow/commit/1459970b3b9780e139ce029ae889fd8f69a37bc7>`_  2020-06-15   ``Rename CloudBuildCreateBuildOperator to CloudBuildCreateOperator (#9314)``
`431ea3291 <https://github.com/apache/airflow/commit/431ea3291c9bf236bccdf8446d753c630ada2b25>`_  2020-06-15   ``Resolve upstream tasks when template field is XComArg (#8805)``
`aee6ab94e <https://github.com/apache/airflow/commit/aee6ab94eb956347ad560cfe2673bc6011074513>`_  2020-06-15   ``Wait for pipeline state in Data Fusion operators (#8954)``
`fb1c8b83d <https://github.com/apache/airflow/commit/fb1c8b83d400506a16c10e3d6623a913847e5cf5>`_  2020-06-10   ``Add test for BQ operations using location (#9206)``
`a26afbfa5 <https://github.com/apache/airflow/commit/a26afbfa51b0981ae742c6171938b57a80aace2b>`_  2020-06-10   ``Make generated job_id more informative in BQ insert_job (#9203)``
`c41192fa1 <https://github.com/apache/airflow/commit/c41192fa1fc5c2b3e7b8414c59f656ab67bbef28>`_  2020-06-10   ``Upgrade pendulum to latest major version ~2.0 (#9184)``
`b1c8c5ed5 <https://github.com/apache/airflow/commit/b1c8c5ed5bba3a852a5446f3fdd1131b4b22637a>`_  2020-06-09   ``Allows using private endpoints in GKEStartPodOperator (#9169)``
`5918efc86 <https://github.com/apache/airflow/commit/5918efc86a2217caa641a6ada289eee1c21407f8>`_  2020-06-05   ``Add 3.8 to the test matrices (#8836)``
`9bcdadaf7 <https://github.com/apache/airflow/commit/9bcdadaf7e6e73d3d2246fbbd32a9f30a1b43ca9>`_  2020-06-05   ``Add 'main' param to template_fields in DataprocSubmitPySparkJobOperator (#9154)``
`f56811dff <https://github.com/apache/airflow/commit/f56811dff3af66cbceb0418f11e00507bab58674>`_  2020-06-05   ``[AIRFLOW-6290] Create guide for GKE operators (#8883)``
`76962867b <https://github.com/apache/airflow/commit/76962867b5877cf5ffd1b6004453f783c0732ab1>`_  2020-06-04   ``Fix sql_to_gcs hook gzip of schema_file (#9140)``
`17adcea83 <https://github.com/apache/airflow/commit/17adcea835cb7b0cf2d8da0ac7dda5549cfa3e45>`_  2020-06-02   ``Fix handling of subprocess error handling in s3_file_transform and gcs (#9106)``
`789852546 <https://github.com/apache/airflow/commit/78985254683c359f7444a7eb5f6ee4967c37d61f>`_  2020-06-01   ``Add BigQueryInsertJobOperator (#8868)``
`29eb68b90 <https://github.com/apache/airflow/commit/29eb68b90b5df692ac322be0939af5e7fa9b71bc>`_  2020-05-31   ``Create guide for Dataproc Operators (#9037)``
`886afaf62 <https://github.com/apache/airflow/commit/886afaf622602aa97f925bc3ee4fc27aa995c445>`_  2020-05-29   ``Add example dag and system test for LocalFilesystemToGCSOperator (#9043)``
`a779c4dfc <https://github.com/apache/airflow/commit/a779c4dfc278d6ece480b012764ea5814dc78dee>`_  2020-05-29   ``add separate example dags and system tests for GCSToGoogleSheetsOperator (#9066)``
`ada26be23 <https://github.com/apache/airflow/commit/ada26be23c913796c2ae77b91cb7d113dfec75a6>`_  2020-05-29   ``Add correct description for dst param in LocalFilesystemToGCSOperator (#9055)``
`81b2761b8 <https://github.com/apache/airflow/commit/81b2761b86dae2d21a6ee859d49c08d46fea6def>`_  2020-05-29   ``add example dag and system test for GoogleSheetsToGCSOperator (#9056)``
`0b0e4f7a4 <https://github.com/apache/airflow/commit/0b0e4f7a4cceff3efe15161fb40b984782760a34>`_  2020-05-26   ``Preparing for RC3 relase of backports (#9026)``
`00642a46d <https://github.com/apache/airflow/commit/00642a46d019870c4decb3d0e47c01d6a25cb88c>`_  2020-05-26   ``Fixed name of 20 remaining wrongly named operators. (#8994)``
`3994030ea <https://github.com/apache/airflow/commit/3994030ea678727daaf9c2bfed0ca94a096f8d2a>`_  2020-05-26   ``Refactor BigQuery operators (#8858)``
`cdb3f2545 <https://github.com/apache/airflow/commit/cdb3f25456e49d0199cd7ccd680626dac01c9be6>`_  2020-05-26   ``All classes in backport providers are now importable in Airflow 1.10 (#8991)``
`1d36b0303 <https://github.com/apache/airflow/commit/1d36b0303b8632fce6de78ca4e782ae26ee06fea>`_  2020-05-23   ``Fix references in docs (#8984)``
`cf5cf45e1 <https://github.com/apache/airflow/commit/cf5cf45e1c0dff9a40e02f0dc221542f974831a7>`_  2020-05-23   ``Support YAML input for CloudBuildCreateOperator (#8808)``
`499493c5c <https://github.com/apache/airflow/commit/499493c5c5cf324ab8452ead80a10b71ce0c3b14>`_  2020-05-19   ``[AIRFLOW-6586] Improvements to gcs sensor (#7197)``
`375d1ca22 <https://github.com/apache/airflow/commit/375d1ca229464617780623c61c6e8a1bf570c87f>`_  2020-05-19   ``Release candidate 2 for backport packages 2020.05.20 (#8898)``
`841d81664 <https://github.com/apache/airflow/commit/841d81664737c25d73d095a7dab5de80d369c87c>`_  2020-05-19   ``Allow setting the pooling time in DLPHook (#8824)``
`12c5e5d8a <https://github.com/apache/airflow/commit/12c5e5d8ae25fa633efe63ccf4db389e2b796d79>`_  2020-05-17   ``Prepare release candidate for backport packages (#8891)``
`f3521fb0e <https://github.com/apache/airflow/commit/f3521fb0e36733d8bd356123e56a453fd37a6dca>`_  2020-05-16   ``Regenerate readme files for backport package release (#8886)``
`15273f0ea <https://github.com/apache/airflow/commit/15273f0ea05ec579c631ce26b5d620233ebdc4d2>`_  2020-05-16   ``Check for same task instead of Equality to detect Duplicate Tasks (#8828)``
`92585ca4c <https://github.com/apache/airflow/commit/92585ca4cb375ac879f4ab331b3a063106eb7b92>`_  2020-05-15   ``Added automated release notes generation for backport operators (#8807)``
`e1e833bb2 <https://github.com/apache/airflow/commit/e1e833bb260879ecb9a1f80f28450a3656c0e598>`_  2020-05-13   ``Update GoogleBaseHook to not follow 308 and use 60s timeout (#8816)``
`8b5491971 <https://github.com/apache/airflow/commit/8b54919711a203c3f35d98c6310a55d4df5da590>`_  2020-05-12   ``Refactor BigQuery hook methods to use python library (#8631)``
`6911dfe83 <https://github.com/apache/airflow/commit/6911dfe8372a33df67ce1fdd3c2bca1047718f60>`_  2020-05-12   ``Fix template fields in Google operators (#8840)``
`4b06fde0f <https://github.com/apache/airflow/commit/4b06fde0f10ce178b3c336c5d901e3b089f2863d>`_  2020-05-12   ``Fix Flake8 errors (#8841)``
`1d12c347c <https://github.com/apache/airflow/commit/1d12c347cb258e7081804da1f9f5ffdedc003163>`_  2020-05-12   ``Refactor BigQuery check operators (#8813)``
`493b685d7 <https://github.com/apache/airflow/commit/493b685d7879cfee532390ba0909d4b1d8764267>`_  2020-05-10   ``Add separate example DAGs and system tests for google cloud speech (#8778)``
`79ef8bed8 <https://github.com/apache/airflow/commit/79ef8bed891c22eb76adf99158288d1b44426dc0>`_  2020-05-10   ``Added Upload Multiple Entity Read Files to specified big query dataset (#8610)``
`280f1f0c4 <https://github.com/apache/airflow/commit/280f1f0c4cc49aba1b2f8b456326795733769d18>`_  2020-05-10   ``Correctly restore upstream_task_ids when deserializing Operators (#8775)``
`58aefb23b <https://github.com/apache/airflow/commit/58aefb23b1d456bbb24876a4e3ff14f25d6274b0>`_  2020-05-08   ``Added SDFtoGCSOperator (#8740)``
`723c52c94 <https://github.com/apache/airflow/commit/723c52c942b49b0e8c8fa8667a4a6a45fa249498>`_  2020-05-07   ``Add documentation for SpannerDeployInstanceOperator (#8750)``
`25ee4211b <https://github.com/apache/airflow/commit/25ee4211b345ce7c19fb7366fd230838c34f1d47>`_  2020-05-06   ``Support all RuntimeEnvironment parameters in DataflowTemplatedJobStartOperator (#8531)``
`8d6f1aa4b <https://github.com/apache/airflow/commit/8d6f1aa4b5bb8809ffc55dc0c62e6d0e89f331e5>`_  2020-05-05   ``Support num_retries field in env var for GCP connection (#8700)``
`67caae0f2 <https://github.com/apache/airflow/commit/67caae0f25db4eec42b8e81c85683aabdd8d6c1a>`_  2020-05-04   ``Add system test for gcs_to_bigquery (#8556)``
`bc45fa675 <https://github.com/apache/airflow/commit/bc45fa6759203b4c26b52e693dac97486a84204e>`_  2020-05-03   ``Add system test and docs for Facebook Ads operators (#8503)``
`a28c66f23 <https://github.com/apache/airflow/commit/a28c66f23d373cd0f8bfc765a515f21d4b66a0e9>`_  2020-04-30   ``[AIRFLOW-4734] Upsert functionality for PostgresHook.insert_rows() (#8625)``
`992a24ce4 <https://github.com/apache/airflow/commit/992a24ce41067d3b73f293878e71835892cbb632>`_  2020-04-28   ``Split and improve BigQuery example DAG (#8529)``
`c1fb28230 <https://github.com/apache/airflow/commit/c1fb28230fa0d36ef86c452c70254b253a113f9c>`_  2020-04-28   ``Refactor BigQueryHook dataset operations (#8477)``
`e8d0f8fea <https://github.com/apache/airflow/commit/e8d0f8feab0ec08e248cd381359112ad6a832f5b>`_  2020-04-26   ``Improve idempodency in CloudDataTransferServiceCreateJobOperator (#8430)``
`37fdfa977 <https://github.com/apache/airflow/commit/37fdfa9775f43a5fa15de9c53ab33ecdf97513c5>`_  2020-04-26   ``[AIRFLOW-6281] Create guide for GCS to GCS transfer operators (#8442)``
`14b22e6ff <https://github.com/apache/airflow/commit/14b22e6ffeb3af1f68e8362a1d0061b41364019c>`_  2020-04-25   ``Add hook and operator for Google Cloud Life Sciences (#8481)``
`72ddc94d1 <https://github.com/apache/airflow/commit/72ddc94d1ee08b414102e0b8ac197a3d8e965707>`_  2020-04-23   ``Pass location using parmamter in Dataflow integration (#8382)``
`912aa4b42 <https://github.com/apache/airflow/commit/912aa4b4237695275db6379cf2f0a633ea6087bc>`_  2020-04-23   ``Added GoogleDisplayVideo360DownloadLineItemsOperator (#8174)``
`57c8c0583 <https://github.com/apache/airflow/commit/57c8c05839f66ed2909b1bee8ff6976432db82aa>`_  2020-04-22   ``Use python client in BQ hook create_empty_table/dataset and table_exists (#8377)``
`5d3a7eef3 <https://github.com/apache/airflow/commit/5d3a7eef30b30fa466d8173f13abe4c356d73aef>`_  2020-04-20   ``Allow multiple extra_packages in Dataflow (#8394)``
`79c99b1b6 <https://github.com/apache/airflow/commit/79c99b1b6ae2ff5b0c8ab892f7f3fb1b44724121>`_  2020-04-18   ``Added location parameter to BigQueryCheckOperator (#8273)``
`79d3f33c1 <https://github.com/apache/airflow/commit/79d3f33c1b65c9c7e7b1a75e25d38cab9aa4517f>`_  2020-04-17   ``Clean up temporary files in Dataflow operators (#8313)``
`efcffa323 <https://github.com/apache/airflow/commit/efcffa323ddb5aa9f5907aa86808f3f3b4f5bd87>`_  2020-04-16   ``Add Dataproc SparkR Example (#8240)``
`b198a1fa9 <https://github.com/apache/airflow/commit/b198a1fa94c44228dc7358552aeb6a5371ae0da2>`_  2020-04-15   ``Create guide for BigQuery operators (#8276)``
`2636cc932 <https://github.com/apache/airflow/commit/2636cc932c3b156644edd46635cf9ff995c83159>`_  2020-04-14   ``Raise exception when GCP credential doesn't support account impersonation (#8213)``
`eee4ebaee <https://github.com/apache/airflow/commit/eee4ebaeeb1991480ee178ddb600bc69b2a88764>`_  2020-04-14   ``Added Facebook Ads Operator #7887 (#8008)``
`8cae07ea1 <https://github.com/apache/airflow/commit/8cae07ea1873a90516120d9ffbd28e7fdd2f78a4>`_  2020-04-14   ``fixed typo (#8294)``
`45c898330 <https://github.com/apache/airflow/commit/45c8983306ab1c54abdacd8f870e790fad25cb37>`_  2020-04-13   ``Less aggressive eager upgrade of requirements (#8267)``
`1fd9ed384 <https://github.com/apache/airflow/commit/1fd9ed3840361afa1e9456ccb0dfd5a60fba4e85>`_  2020-04-13   ``Add mypy plugin for decorators. (#8145)``
`327b0a9f7 <https://github.com/apache/airflow/commit/327b0a9f77bbcbe3f977a37de04264c2eff4bee1>`_  2020-04-13   ``Added GoogleDisplayVideo360UploadLineItemsOperator (#8216)``
`bb5e403a3 <https://github.com/apache/airflow/commit/bb5e403a320e7377e5040cb180f61b4f5a9ea558>`_  2020-04-10   ``Honor schema type for MySQL to GCS data pre-process (#8090)``
`87969a350 <https://github.com/apache/airflow/commit/87969a350ddd41e9e77776af6d780b31e363eaca>`_  2020-04-09   ``[AIRFLOW-6515] Change Log Levels from Info/Warn to Error (#8170)``
`3fc89f29f <https://github.com/apache/airflow/commit/3fc89f29f5bcd1529089fa6cb9c44843614f9ec5>`_  2020-04-06   ``[AIRFLOW-7106] Cloud data fusion integration - Allow to pass args to start pipeline (#7849)``
`7ef75d239 <https://github.com/apache/airflow/commit/7ef75d2393f30d155de550e6d1ee8c055e2abfee>`_  2020-04-03   ``[AIRFLOW-7117] Honor self.schema in sql_to_gcs as schema to upload (#8049)``
`ed2bc0057 <https://github.com/apache/airflow/commit/ed2bc00576b39a88e3e1fb79092494f4bfdcbf5c>`_  2020-04-02   ``Add Google Ads list accounts operator (#8007)``
`3808a6206 <https://github.com/apache/airflow/commit/3808a6206e70d4af84b39ea7078df54f02c1435e>`_  2020-04-01   ``Unify Google class/package names (#8033)``
`8a0240257 <https://github.com/apache/airflow/commit/8a02402576f83869d5134b4bddef5d73c15a8320>`_  2020-03-31   ``Rename CloudBaseHook to GoogleBaseHook and move it to google.common (#8011)``
`8e8978007 <https://github.com/apache/airflow/commit/8e897800716c8ccedd1c53f2d083cb295786aa50>`_  2020-03-31   ``Add more refactor steps for providers.google (#8010)``
`aae3b8fb2 <https://github.com/apache/airflow/commit/aae3b8fb27870cb3cfba5ed73e35e08d520ef014>`_  2020-03-31   ``Individual package READMEs (#8012)``
`779023968 <https://github.com/apache/airflow/commit/779023968f983c91701f687bc823dc338934cdad>`_  2020-03-30   ``[AIRFLOW-7075] Operators for storing information from GCS into GA (#7743)``
`49abce521 <https://github.com/apache/airflow/commit/49abce52178c81954f8a25608f70ffe02fcf7b19>`_  2020-03-30   ``Improve system tests for Cloud Build (#8003)``
`0f19a930d <https://github.com/apache/airflow/commit/0f19a930d1a7dec2a96bab0de144829f83cc0626>`_  2020-03-29   ``Remove GKEStartPodOperator when backporting (#7908)``
`0e1c238b2 <https://github.com/apache/airflow/commit/0e1c238b2fff3a092c93368125bc8d82abc4b308>`_  2020-03-28   ``Get Airflow Variables from GCP Secrets Manager (#7946)``
`eb4af4f94 <https://github.com/apache/airflow/commit/eb4af4f944c77e67e167bbb6b0a2aaf075a95b50>`_  2020-03-28   ``Make BaseSecretsBackend.build_path generic (#7948)``
`01f99426f <https://github.com/apache/airflow/commit/01f99426fddd2a24552f352edcb271fa78cf3b15>`_  2020-03-28   ``Add download/upload operators for GCS and Google Sheets (#7866)``
`892522f8e <https://github.com/apache/airflow/commit/892522f8e2aeedc1ad842a08aaea967b0cae077f>`_  2020-03-26   ``Change signature of GSheetsHook methods (#7853)``
`bfd425157 <https://github.com/apache/airflow/commit/bfd425157a746402b516f8fc9e48f4ddccd794ce>`_  2020-03-26   ``Improve idempotency in MLEngineHook.create_model (#7811)``
`f9c226343 <https://github.com/apache/airflow/commit/f9c226343d94a7732da280d1dd086bf1ba291c77>`_  2020-03-26   ``Fix CloudSecretsManagerBackend invalid connections_prefix (#7861)``
`e3920f12f <https://github.com/apache/airflow/commit/e3920f12f483b53950507c50f6ab6a4318072859>`_  2020-03-26   ``Improve setUp/tearDown in Cloud Firestore system test (#7862)``
`8ba8a7295 <https://github.com/apache/airflow/commit/8ba8a7295a31f6b44894bfcaea36fa93b8d8c0d0>`_  2020-03-26   ``Improve example DAGs for Cloud Memorystore (#7855)``
`f7d1a437c <https://github.com/apache/airflow/commit/f7d1a437c17461b5ab768b75d58f0cb026b2a818>`_  2020-03-26   ``Fix CloudMemorystoreCreateInstanceAndImportOperator operator (#7856)``
`beef6c230 <https://github.com/apache/airflow/commit/beef6c230e4ff266af7c16b639bfda659b2bf6c0>`_  2020-03-26   ``Improve authorization in GCP system tests (#7863)``
`5f165f3e4 <https://github.com/apache/airflow/commit/5f165f3e4231ebd420ce643211a93e1fecf4877e>`_  2020-03-26   ``[AIRFLOW-5801] Get GCP credentials from file instead of JSON blob (#7869)``
`686d7d50b <https://github.com/apache/airflow/commit/686d7d50bd21622724d6818021355bc6885fd3de>`_  2020-03-25   ``Standardize SecretBackend class names (#7846)``
`1982c3fdc <https://github.com/apache/airflow/commit/1982c3fdca1f04cfc41fc5b5e285d8f01c6b76ab>`_  2020-03-24   ``Run Dataflow for ML Engine summary in venv (#7809)``
`eef87b995 <https://github.com/apache/airflow/commit/eef87b9953347a65421f315a07dbef37ded9df66>`_  2020-03-23   ``[AIRFLOW-7105] Unify Secrets Backend method interfaces (#7830)``
`529db07b2 <https://github.com/apache/airflow/commit/529db07b2ee73d886e37e8b3415462c730187b15>`_  2020-03-23   ``Improve Google PubSub hook publish method (#7831)``
`4bde99f13 <https://github.com/apache/airflow/commit/4bde99f1323d72f6c84c1548079d5e98fc0a2a9a>`_  2020-03-23   ``Make airflow/providers pylint compatible (#7802)``
`a001489b5 <https://github.com/apache/airflow/commit/a001489b5928ebfc35f990a29d1c9c2ecb80bd61>`_  2020-03-23   ``Improve example DAG for ML Engine (#7810)``
`9e5a8e7f8 <https://github.com/apache/airflow/commit/9e5a8e7f83cf2368315fce62f8d81304f7ba2f04>`_  2020-03-23   ``Add call to Super class in 'google' providers (#7823)``
`b86bf79bf <https://github.com/apache/airflow/commit/b86bf79bff615e61de98bead4d02eace5690d5fb>`_  2020-03-23   ``Fix typo in GCP credentials_provider's docstring (#7818)``
`56c013ce9 <https://github.com/apache/airflow/commit/56c013ce922eb18e5f7dd4410986afbcc6f29025>`_  2020-03-23   ``Add missing docstring in BigQueryHook.create_empty_table (#7817)``
`426a79847 <https://github.com/apache/airflow/commit/426a79847ced832ca3f67c135fd8830ebf1de7d2>`_  2020-03-23   ``Imrove support for laatest API in  MLEngineStartTrainingJobOperator (#7812)``
`cdf1809fc <https://github.com/apache/airflow/commit/cdf1809fce0e59c8379a799f1738d8d813abbf51>`_  2020-03-23   ``[AIRFLOW-7104] Add Secret backend for GCP Secrets Manager (#7795)``
`27dac00e1 <https://github.com/apache/airflow/commit/27dac00e125b87626a0b87074d61e6d38031bf47>`_  2020-03-22   ``[AIRFLOW-7099] Improve system test for cloud transfer service (#7794)``
`0daf5d729 <https://github.com/apache/airflow/commit/0daf5d729acef4e9aef5226452dff774e80430cd>`_  2020-03-22   ``Add ability to specify a maximum modified time for objects in GCSToGCSOperator (#7791)``
`c8088c2bd <https://github.com/apache/airflow/commit/c8088c2bd70a16605a5d4b1a66a22309359d6712>`_  2020-03-20   ``[AIRFLOW-7100] Add GoogleAnalyticsGetAdsLinkOperator (#7781)``
`5106a2931 <https://github.com/apache/airflow/commit/5106a29314b413d168bcba7a64bf91c04fdb5dfe>`_  2020-03-20   ``[AIRFLOW-6752] Add GoogleAnalyticsRetrieveAdsLinksListOperator (#7748)``
`759ce2a80 <https://github.com/apache/airflow/commit/759ce2a80c95832fe4773c9f4fde23e1b03cbc6f>`_  2020-03-20   ``[AIRFLOW-6978] Add PubSubPullOperator (#7766)``
`6b9b214e4 <https://github.com/apache/airflow/commit/6b9b214e4c3b3afa8ea2e1a5c1e24993013d60ac>`_  2020-03-20   ``[AIRFLOW-6732] Add GoogleAdsHook and GoogleAdsToGcsOperator (#7692)``
`b11891696 <https://github.com/apache/airflow/commit/b11891696946d1461174b385c88d6af8abb99768>`_  2020-03-19   ``[AIRFLOW-7069] Fix cloudsql system tests (#7770)``
`ae854cae5 <https://github.com/apache/airflow/commit/ae854cae5a2cf8cae37edf7e0813ad01bccfbc30>`_  2020-03-19   ``[AIRFLOW-7082] Remove catch_http_exception decorator in GCP hooks (#7756)``
`7e1e954d2 <https://github.com/apache/airflow/commit/7e1e954d23ce272b0a71188f0f535e20d54be443>`_  2020-03-19   ``[AIRFLOW-7085] Cache credentials, project_id in GCP Base Hook (#7759)``
`6e21c139b <https://github.com/apache/airflow/commit/6e21c139b3cce3f895040939f0b02e3e0ba36141>`_  2020-03-19   ``[AIRFLOW-XXXX] Fix reference to GCP classes in guides (#7762)``
`ce022a3f7 <https://github.com/apache/airflow/commit/ce022a3f72b7735087d4c3bbe81d293a0ab75327>`_  2020-03-19   ``[AIRFLOW-XXXX] Add cross-references for operators guide (#7760)``
`029c84e55 <https://github.com/apache/airflow/commit/029c84e5527b6db6bdbdbe026f455da325bedef3>`_  2020-03-18   ``[AIRFLOW-5421] Add Presto to GCS transfer operator (#7718)``
`63a3102ed <https://github.com/apache/airflow/commit/63a3102ede8fb8f764d251b20cad5ee5bef84f50>`_  2020-03-18   ``[AIRFLOW-7064] Add CloudFirestoreExportDatabaseOperator (#7725)``
`73305c7bd <https://github.com/apache/airflow/commit/73305c7bd57f14444804c13b8b290f479832d3db>`_  2020-03-18   ``[AIRFLOW-7081] Remove env variables from GCP guide (#7755)``
`60fdbf6d9 <https://github.com/apache/airflow/commit/60fdbf6d9255d34a8967400e9585b1cd5d29d3e9>`_  2020-03-18   ``[AIRFLOW-5610] Add ability to specify multiple objects to copy in GCSToGCSOperator (#7728)``
`de7e934ca <https://github.com/apache/airflow/commit/de7e934ca3f21ce82f67accf92811b3ac044476f>`_  2020-03-17   ``[AIRFLOW-7079] Remove redundant code for storing template_fields (#7750)``
`0de0347b2 <https://github.com/apache/airflow/commit/0de0347b27a961c46ee49da6dfa9205321657749>`_  2020-03-17   ``[AIRFLOW-6855]: Escape project_dataset_table in SQL query in gcs to bq … (#7475)``
`91557c6f8 <https://github.com/apache/airflow/commit/91557c6f87529c010b8ad1110ece35fd7fd751e4>`_  2020-03-17   ``[AIRFLOW-7073] GKEStartPodOperator always use connection credentials (#7738)``
`51161dbd9 <https://github.com/apache/airflow/commit/51161dbd9de0c966016cec4d5036877890daee7c>`_  2020-03-16   ``[AIRFLOW-5664] Store timestamps with microseconds precision (#6354)``
`2bc020c43 <https://github.com/apache/airflow/commit/2bc020c43112dd3a769311de8d5012e8e8f399ee>`_  2020-03-14   ``[AIRFLOW-7055] Verbose logging option for google provider (#7711)``
`c997cab42 <https://github.com/apache/airflow/commit/c997cab42d8695ac444e63dfe4b948a7ea82ed89>`_  2020-03-13   ``[AIRFLOW-6724] Add Google Analytics 360 Accounts Retrieve Operator (#7630)``
`137896f32 <https://github.com/apache/airflow/commit/137896f326cd29b59902a887e4c4e58f940ff62b>`_  2020-03-12   ``[AIRFLOW-7034] Remove feature: Assigning Dag to task using Bitshift Op (#7685)``
`1f77f943d <https://github.com/apache/airflow/commit/1f77f943d5d85f66b6a988e8ef6506525eaf4732>`_  2020-03-10   ``[AIRFLOW-6980] Improve system tests and building providers package (#7615)``
`bf9b6b6d7 <https://github.com/apache/airflow/commit/bf9b6b6d70455352bbf807871c8eeb6324be7e54>`_  2020-03-09   ``[AIRFLOW-5013] Add GCP Data Catalog Hook and operators (#7664)``
`e5130dc9f <https://github.com/apache/airflow/commit/e5130dc9fe89187e95071e678ea3b46600866762>`_  2020-03-09   ``[AIRFLOW-2911] Add job cancellation capability to Dataflow service (#7659)``
`faf0df4b9 <https://github.com/apache/airflow/commit/faf0df4b9460b7f037ee390addbd2c6effcae013>`_  2020-03-09   ``[AIRFLOW-XXXX] Fix upsert operator in BQ example DAG (#7666)``
`42eef3821 <https://github.com/apache/airflow/commit/42eef38217e709bc7a7f71bf0286e9e61293a43e>`_  2020-03-07   ``[AIRFLOW-6877] Add cross-provider dependencies as extras (#7506)``
`b5b9795f0 <https://github.com/apache/airflow/commit/b5b9795f0446bb484a91ee485f49ea456f1c26c4>`_  2020-03-07   ``[AIRFLOW-6973] Make GCSCreateBucketOperator idempotent (fix) (#7624)``
`6b65038fb <https://github.com/apache/airflow/commit/6b65038fb409ba1040e70305444816d8f5cfdc47>`_  2020-03-06   ``[AIRFLOW-6990] Improve system tests for Google Marketing Platform (#7631)``
`755fe5224 <https://github.com/apache/airflow/commit/755fe52249ba1cd965cf2f87fa7a428b8197a38a>`_  2020-03-05   ``[AIRFLOW-6915] Add AI Platform Console Link for MLEngineStartTrainingJobOperator (#7535)``
`cb2f33911 <https://github.com/apache/airflow/commit/cb2f339116cf2093da447748892fac68aecbb888>`_  2020-03-04   ``[AIRFLOW-6973] Make GCSCreateBucketOperator idempotent (#7609)``
`09fea3ce8 <https://github.com/apache/airflow/commit/09fea3ce8e4d7816281963bb8f2cb06f4de6db5c>`_  2020-03-04   ``[AIRFLOW-6977] Fix BigQuery DTS example DAG (#7612)``
`8230ccc48 <https://github.com/apache/airflow/commit/8230ccc48b157c89b2b893d42c6fe1523b83363a>`_  2020-03-04   ``[AIRFLOW-6926] Fix Google Tasks operators return types and idempotency (#7547)``
`0d1e3088a <https://github.com/apache/airflow/commit/0d1e3088aa9f16eaeeb7b18eccec8f35c79a53df>`_  2020-03-04   ``[AIRFLOW-6970] Improve GCP Video Intelligence system tests (#7604)``
`ab6bb0012 <https://github.com/apache/airflow/commit/ab6bb0012c38740b76e864d42d299c5c7a9972a3>`_  2020-03-03   ``[AIRFLOW-6971] Fix return type in CloudSpeechToTextRecognizeSpeechOperator (#7607)``
`3db4ade3d <https://github.com/apache/airflow/commit/3db4ade3dc9660c21c28187100a22008552f2bd3>`_  2020-02-29   ``[AIRFLOW-6924] Fix Google DLP operators return types (#7546)``
`008b4bab1 <https://github.com/apache/airflow/commit/008b4bab14222da068b737d6332db4963b994007>`_  2020-02-27   ``[AIRFLOW-6730] Use total_seconds instead of seconds (#7363)``
`bb552b2d9 <https://github.com/apache/airflow/commit/bb552b2d9fd595cc3eb1b3a2f637f29b814878d7>`_  2020-02-25   ``[AIRFLOW-6908] Lazy load AirflowException (#7528)``
`d1a34246a <https://github.com/apache/airflow/commit/d1a34246ac593901f8599b102dc3d7efa4dd61e4>`_  2020-02-25   ``[AIRFLOW-6593] Add GCP Stackdriver Alerting Hooks and Operators (#7322)``
`3320e432a <https://github.com/apache/airflow/commit/3320e432a129476dbc1c55be3b3faa3326a635bc>`_  2020-02-24   ``[AIRFLOW-6817] Lazy-load 'airflow.DAG' to keep user-facing API untouched (#7517)``
`dcf874352 <https://github.com/apache/airflow/commit/dcf87435219307d4e916a8abc2b819ad75e2b1cf>`_  2020-02-24   ``[AIRFLOW-6894] Prevent db query in example_dags (#7516)``
`4d03e33c1 <https://github.com/apache/airflow/commit/4d03e33c115018e30fa413c42b16212481ad25cc>`_  2020-02-22   ``[AIRFLOW-6817] remove imports from 'airflow/__init__.py', replaced implicit imports with explicit imports, added entry to 'UPDATING.MD' - squashed/rebased (#7456)``
`35b961637 <https://github.com/apache/airflow/commit/35b9616378d1cfba7c2eb3c71e20acb6734b7c77>`_  2020-02-21   ``[AIRFLOW-4973] Add Cloud Data Fusion Pipeline integration (#7486)``
`aff3a361b <https://github.com/apache/airflow/commit/aff3a361b4092212c0757f9ce88fa2e40d25d1f4>`_  2020-02-20   ``[AIRFLOW-6558] Campaign Manager operators for conversions (#7420)``
`9cbd7de6d <https://github.com/apache/airflow/commit/9cbd7de6d115795aba8bfb8addb060bfdfbdf87b>`_  2020-02-18   ``[AIRFLOW-6792] Remove _operator/_hook/_sensor in providers package and add tests (#7412)``
`5b199cb86 <https://github.com/apache/airflow/commit/5b199cb86be5b1aefbd8620185033d6f635713c1>`_  2020-02-17   ``[AIRFLOW-XXXX] Typo in example_bigquery DAG (#7429)``
`2c9345a8e <https://github.com/apache/airflow/commit/2c9345a8e03d37a2676efa2f2ea7e8b7814c5345>`_  2020-02-17   ``[AIRFLOW-6759] Added MLEngine operator/hook to cancel MLEngine jobs (#7400)``
`946bdc23c <https://github.com/apache/airflow/commit/946bdc23c039637b0383e1269f99bdd1b2426565>`_  2020-02-16   ``[AIRFLOW-6405] Add GCP BigQuery Table Upsert Operator (#7126)``
`2381c820c <https://github.com/apache/airflow/commit/2381c820c8aaeffc1c9b4ed47832038833400eb8>`_  2020-02-13   ``[AIRFLOW-6505] Let emoji encoded properly for json.dumps() (#7399)``
`04c1fefbf <https://github.com/apache/airflow/commit/04c1fefbf26a73ed13881d2ec14eada48028ff72>`_  2020-02-03   ``[AIRFLOW-6676] added GCSDeleteBucketOperator (#7307)``
`a0252748f <https://github.com/apache/airflow/commit/a0252748ff312daede15c6f0a3d39e16c774461c>`_  2020-02-03   ``[AIRFLOW-6717] Remove non-existent field from templated_fields (#7340)``
`97a429f9d <https://github.com/apache/airflow/commit/97a429f9d0cf740c5698060ad55f11e93cb57b55>`_  2020-02-02   ``[AIRFLOW-6714] Remove magic comments about UTF-8 (#7338)``
`9d8d07557 <https://github.com/apache/airflow/commit/9d8d0755789d4aeadc5d3015f3cdde62901f85b8>`_  2020-02-03   ``[AIRFLOW-6715] Fix Google Cloud DLP Example DAG (#7337)``
`cf141506a <https://github.com/apache/airflow/commit/cf141506a25dbba279b85500d781f7e056540721>`_  2020-02-02   ``[AIRFLOW-6708] Set unique logger names (#7330)``
`373c6aa4a <https://github.com/apache/airflow/commit/373c6aa4a208284b5ff72987e4bd8f4e2ada1a1b>`_  2020-01-30   ``[AIRFLOW-6682] Move GCP classes to providers package (#7295)``
`83c037873 <https://github.com/apache/airflow/commit/83c037873ff694eed67ba8b30f2d9c88b2c7c6f2>`_  2020-01-30   ``[AIRFLOW-6674] Move example_dags in accordance with AIP-21 (#7287)``
`057f3ae3a <https://github.com/apache/airflow/commit/057f3ae3a4afedf6d462ecf58b01dd6304d3e135>`_  2020-01-29   ``[AIRFLOW-6670][depends on AIRFLOW-6669] Move contrib operators to providers package (#7286)``
`ceea293c1 <https://github.com/apache/airflow/commit/ceea293c1652240e7e856c201e4341a87ef97a0f>`_  2020-01-28   ``[AIRFLOW-6656] Fix AIP-21 moving (#7272)``
`c42a375e7 <https://github.com/apache/airflow/commit/c42a375e799e5adb3f9536616372dc90ff47e6c8>`_  2020-01-27   ``[AIRFLOW-6644][AIP-21] Move service classes to providers package (#7265)``
`059eda05f <https://github.com/apache/airflow/commit/059eda05f82fefce4410f44f761f945a27d83daf>`_  2020-01-21   ``[AIRFLOW-6610] Move software classes to providers package (#7231)``
`f4d3e5e54 <https://github.com/apache/airflow/commit/f4d3e5e54507f52a00a9b95aa48eb0260e17224d>`_  2020-01-13   ``[AIRFLOW-6102] [AIP-21] Rename Dataproc operators (#7151)``
`e7bf8ecb4 <https://github.com/apache/airflow/commit/e7bf8ecb48f0299af8091433535ac573c2afd1cf>`_  2020-01-13   ``[AIRFLOW-6119] [AIP-21] Rename GCS operators, hooks and sensors (#7125)``
`5b6772cb8 <https://github.com/apache/airflow/commit/5b6772cb8391b248cb4b7be5fd3d5c035280fac1>`_  2020-01-09   ``[AIRFLOW-6125] [AIP-21] Rename S3 operator and SFTP operator (#7112)``
`4f8592ae8 <https://github.com/apache/airflow/commit/4f8592ae8f52ab7f42623d3b43eef0928c9aafb2>`_  2020-01-08   ``[AIRFLOW-6118] [AIP-21] Rename Pubsub operators and hook (#7046)``
`20299473f <https://github.com/apache/airflow/commit/20299473f11add6531f607256ee8a0f7f9507ab8>`_  2020-01-03   ``[AIRFLOW-6115] [AIP-21] Rename GCP vision operators (#7020)``
`18e8cea4e <https://github.com/apache/airflow/commit/18e8cea4e7487a7dfefc03661e5ebe54c4104ead>`_  2020-01-03   ``[AIRFLOW-6428] Fix import path for airflow.utils.dates.days_ago in Example DAGs (#7007)``
`95087af14 <https://github.com/apache/airflow/commit/95087af14091f28a83ced8ff1860b86dfd93f93d>`_  2019-12-31   ``[AIRFLOW-6110] [AIP-21] Rename natural_language service (#6968)``
`69629a5a9 <https://github.com/apache/airflow/commit/69629a5a948ab2c4ac04a4a4dca6ac86d19c11bd>`_  2019-12-09   ``[AIRFLOW-5807] Move SFTP from contrib to providers. (#6464)``
`25e9047a4 <https://github.com/apache/airflow/commit/25e9047a4a4da5fad4f85c366e3a6262c0a4f68e>`_  2019-12-09   ``[AIRFLOW-6193] Do not use asserts in Airflow main code (#6749)``
`ed0a14f32 <https://github.com/apache/airflow/commit/ed0a14f321b9dab3554ae395c11c147258536ce8>`_  2019-12-09   ``[AIRFLOW-6120] Rename GoogleCloudBaseHook (#6734)``
`2f2f89c14 <https://github.com/apache/airflow/commit/2f2f89c148e2b694aee9402707f68065ee7320f8>`_  2019-12-01   ``[AIRFLOW-6139] Consistent spaces in pylint enable/disable (#6701)``
`03c870a61 <https://github.com/apache/airflow/commit/03c870a6172ab232af6319a30ad8d46622359b10>`_  2019-11-26   ``[AIRFLOW-6010] Remove cyclic imports and pylint hacks (#6601)``
`5c4cfea8c <https://github.com/apache/airflow/commit/5c4cfea8c0f488496c1cbcc4c6c5db13d8210979>`_  2019-11-15   ``[AIRFLOW-5718] Add SFTPToGoogleCloudStorageOperator (#6393)``
`44a8c37a9 <https://github.com/apache/airflow/commit/44a8c37a9a8668469aa825ad21057cca6ac2c186>`_  2019-11-13   ``[AIRFLOW-XXX] Fix the docstring for Dataproc get_job method (#6581)``
`d633d3ac4 <https://github.com/apache/airflow/commit/d633d3ac44c395e6c43cd388f98fba1ce1c435a3>`_  2019-11-13   ``[AIRFLOW-5691] Rewrite Dataproc operators to use python library (#6371)``
`d985c02d9 <https://github.com/apache/airflow/commit/d985c02d9fa3d9ec946abc1735b0551fd61fb9f0>`_  2019-11-05   ``[AIRFLOW-XXX] Add How-To-Guide to GCP PubSub (#6497)``
`a296cdabd <https://github.com/apache/airflow/commit/a296cdabdb9c9c65cf9a48329cb776aed5c82d43>`_  2019-11-04   ``[AIRFLOW-5743] Move Google PubSub to providers package (#6476)``
`470b2a779 <https://github.com/apache/airflow/commit/470b2a779d031406a3d5925f2fa2ec40e5c3bccb>`_  2019-10-30   ``[AIRFLOW-5741] Move Cloud Natural Language to providers (#6421)``
`f2caa451f <https://github.com/apache/airflow/commit/f2caa451fc2b8ee59163314f9ec1cc372acbadf1>`_  2019-10-27   ``[AIRFLOW-5742] Move Google Cloud Vision to providers package (#6424)``
`16d7accb2 <https://github.com/apache/airflow/commit/16d7accb22c866d4fbf368e4d979dc1c4a41d93c>`_  2019-10-22   ``[AIRFLOW-4971] Add Google Display & Video 360 integration (#6170)``
`4e661f535 <https://github.com/apache/airflow/commit/4e661f535dea613f9b2e0075676f9a73a97461fe>`_  2019-10-22   ``[AIRFLOW-5379] Add Google Search Ads 360 operators (#6228)``
`19e32b4e2 <https://github.com/apache/airflow/commit/19e32b4e2c798f662e5d8d1e7c65036c5e7ac125>`_  2019-10-18   ``[AIRFLOW-5656] Rename provider to providers module (#6333)``
================================================================================================  ===========  ======================================================================================================================================================================
