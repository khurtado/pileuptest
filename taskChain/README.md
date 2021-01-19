# Running like:

```
cmssw_enforce_guid_in_filename.py --input_pkl /tmpscratch/users/khurtado/work/dec17/psettweakmigration/taskChain/job/WMTaskSpace/cmsRun1/PSet.pkl --output_pkl /tmpscratch/users/khurtado/work/dec17/psettweakmigration/taskChain/job/WMTaskSpace/cmsRun1/PSet.pkl --input_source PoolSource
GUID in this CMSSW release (CMSSW_10_6_11_patch1) is supported
Considering a source of type PoolSource
Traceback (most recent call last):
  File "/tmpscratch/users/khurtado/work/dec17/psettweakmigration/stepChain/job/PSetTweaks/cmssw_enforce_guid_in_filename.py", line 39, in <module>
    main()
  File "/tmpscratch/users/khurtado/work/dec17/psettweakmigration/stepChain/job/PSetTweaks/cmssw_enforce_guid_in_filename.py", line 37, in main
    do_loop(args, adjust_guid)
  File "/tmpscratch/users/khurtado/work/dec17/psettweakmigration/stepChain/job/PSetTweaks/tweak_program_helpers.py", line 43, in do_loop
    process = func(process, args)
  File "/tmpscratch/users/khurtado/work/dec17/psettweakmigration/stepChain/job/PSetTweaks/cmssw_enforce_guid_in_filename.py", line 24, in adjust_guid
    adjust_source_guid(input_source)
  File "/tmpscratch/users/khurtado/work/dec17/psettweakmigration/stepChain/job/PSetTweaks/tweak_program_helpers.py", line 130, in adjust_source_guid
    if not guidRegEx.search(input_source.fileNames[0]):
IndexError: list index out of range
````
