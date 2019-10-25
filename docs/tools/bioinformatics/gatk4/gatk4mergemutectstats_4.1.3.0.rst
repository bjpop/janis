:orphan:

GATK4: MergeMutectStats
===============================================

1 contributor · 3 versions

:ID: ``GATK4MergeMutectStats``
:Python: ``janis_bioinformatics.tools.gatk4.mergemutectstats.versions import Gatk4MergeMutectStats_4_1_3``
:Versions: 4.1.4.0, 4.1.3.0, 4.1.2.0
:Container: broadinstitute/gatk:4.1.3.0
:Authors: Hollizeck Sebastian
:Citations: TBD
:Created: 2019-09-09
:Updated: 2019-09-09
:Required inputs:
   - ``statsFiles: Array<TextFile>``
:Outputs: 
   - ``out: TextFile``

Documentation
-------------

URL: `TBD <TBD>`_

TBD

------

Additional configuration (inputs)
---------------------------------

==============  ==================  =================
name            type                documentation
==============  ==================  =================
statsFiles      Array<TextFile>     Callability stats
mergedStatsOut  Optional<Filename>
==============  ==================  =================
