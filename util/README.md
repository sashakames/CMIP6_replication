
Utility scripts and data:

- data/cmip5_statistics_var_list.py:  long and short name lists of most oftenly
     accessed variables in CMIP5 (derived from IPCC WDC data access statistics)

- util/MakeSelectionFiles/make_selection_file.py: helper function to generate selection
     files based on user input and CMIP6 CVs.
     usage: python make_selection_file.py -h
- util/Selection: example selection files generated by:
    python make_selection_file.py -a CMIP, ScenarioMIP, CFMIP -m IPSL-CM6A-LR -v ta,ta700,tas,tasAdjust,tasmax,tasmin,prAdjust,pr_atm,ua,uas,va,vas,ts,tsAdjust,tsice,tslsi,zg,hus,huss,psl,pslAdjust,ps,thetao,thetaoga,hur,hurs,rhs,rhsmax,rhsmin,sfcWind,sfcWindmax,sic,rsds_atm,rsdssi,clt,cltcalipso,cltisccp,wmo,tos,tso,rlds_atm,rldssi,so,soga,rlut,rlut4co2,snd,rlus,rlussi,wmosq,rsus,rsussi,rsut,rsut4co2

