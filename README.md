# Test pileup
```
/cvmfs/cms.cern.ch/slc7_amd64_gcc820/cms/cmssw-wm-tools/201113/bin/cmssw_handle_pileup.py --input_pkl PSet.pkl --output_pkl PSet_output.pkl --pileup_dict pileupconf.json
Processing PreMixingModule mixData type mc
Traceback (most recent call last):
  File "/cvmfs/cms.cern.ch/slc7_amd64_gcc820/cms/cmssw-wm-tools/201113/bin/cmssw_handle_pileup.py", line 102, in <module>
    main()
  File "/cvmfs/cms.cern.ch/slc7_amd64_gcc820/cms/cmssw-wm-tools/201113/bin/cmssw_handle_pileup.py", line 100, in main
    do_loop(args, handle_pileup)
  File "/cvmfs/cms.cern.ch/share/overrides/python/tweak_program_helpers.py", line 43, in do_loop
    process = func(process, args)
  File "/cvmfs/cms.cern.ch/slc7_amd64_gcc820/cms/cmssw-wm-tools/201113/bin/cmssw_handle_pileup.py", line 87, in handle_pileup
    process = process_pileup_mixing_modules(process, args, mixModules, "mc")
  File "/cvmfs/cms.cern.ch/slc7_amd64_gcc820/cms/cmssw-wm-tools/201113/bin/cmssw_handle_pileup.py", line 62, in process_pileup_mixing_modules
    eventsAvailable = pileupDict[pileupType]["eventsAvailable"]
KeyError: 'eventsAvailable'
```
