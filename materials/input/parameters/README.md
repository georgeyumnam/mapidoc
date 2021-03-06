A dict of all parameters in the calculation, extracted from the final
vasprun.xml file. This includes parameters that have defaults and are not
explicitly specified in the INCAR file.











## Example response in JSON

```json
{
    "NELMDL": -5, 
    "LMUSIC": false, 
    "WC": 100.0, 
    "LCHIMAG": false, 
    "INIWAV": 1, 
    "APACO": 16.0, 
    "IBRION": 2, 
    "ICORELEVEL": 0, 
    "MODEL_GW": 0, 
    "LSCAAWARE": false, 
    "LDIPOL": false, 
    "ENCUTFOCK": 0.0, 
    "LRPA": true, 
    "HFSCREEN": 0.0, 
    "MAXMIX": -45, 
    "EMAX": -10.0, 
    "LBERRY": false, 
    "ENAUG": 298.798, 
    "LHFONE": false, 
    "ISYM": 2, 
    "MODEL_ALPHA": 1.0, 
    "AEXX": 0.0, 
    "LTCTE": false, 
    "IDIOT": 3, 
    "LELF": false, 
    "HFALPHA": 0.0, 
    "NBANDS": 25, 
    "LMAXPAW": -100, 
    "LSPIRAL": false, 
    "ISMEAR": 1, 
    "ENCUTGWSOFT": -2.0, 
    "EBREAK": 2e-08, 
    "IWAVPR": 11, 
    "WEIMIN": 0.001, 
    "NEDOS": 301, 
    "LCOMPAT": false, 
    "FOURORBIT": 0, 
    "LVEL": false, 
    "LDAU": false, 
    "LMAXMIX": 2, 
    "NOMEGAR": 0, 
    "ODDONLYGW": false, 
    "ISPIN": 2, 
    "GGA_COMPAT": true, 
    "BMIX_MAG": 1.0, 
    "NMAXFOCKAE": 0, 
    "SYMPREC": 1e-05, 
    "LVTOT": false, 
    "TEEND": 0.0001, 
    "AVECCONST": [
        0.0, 
        0.0, 
        0.0
    ], 
    "MAGDIPOL": [
        0.0, 
        0.0, 
        0.0
    ], 
    "ODDONLY": false, 
    "ORBITALMAG": false, 
    "EDIFFG": 2e-05, 
    "LZEROZ": false, 
    "NGX": 42, 
    "NGY": 42, 
    "LASYNC": false, 
    "ROPT": [
        -0.00025, 
        -0.00025
    ], 
    "NBLOCK": 1, 
    "LMAGBLOCH": false, 
    "NRMM": 4, 
    "NBANDSLF": -1, 
    "IDIPOL": 0, 
    "HFSCREENC": 0.0, 
    "EVENONLYGW": false, 
    "LRHFCALC": false, 
    "EFERMI": 0.0, 
    "LREAL_COMPAT": false, 
    "OMEGATL": -200.0, 
    "EDIFF": 2e-06, 
    "LEPSILON": false, 
    "EFIELD": 0.0, 
    "DIPOL": [
        -100.0, 
        -100.0, 
        -100.0
    ], 
    "MAGMOM": [
        0.6, 
        0.6, 
        0.6, 
        0.6, 
        5.0, 
        5.0
    ], 
    "LSORBIT": false, 
    "NUPDOWN": -1.0, 
    "NELMIN": 3, 
    "LTHOMAS": false, 
    "LSCALAPACK": false, 
    "NBLK": 32, 
    "NFREE": 1, 
    "ENCUT4O": -1.0, 
    "EVENONLY": false, 
    "NELECT": 30.0, 
    "LMAXMP2": -1, 
    "LCORR": true, 
    "EXXOEP": 0, 
    "AMIX": 0.4, 
    "TIME": 0.4, 
    "LORBIT": false, 
    "ICHARG": 1, 
    "ADDGRID": false, 
    "QSPIRAL": [
        0.0, 
        0.0, 
        0.0
    ], 
    "AGGAX": 1.0, 
    "NKREDLFX": 1, 
    "NKREDLFY": 1, 
    "NKREDLFZ": 1, 
    "IALGO": 68, 
    "NELM": 100, 
    "LPARD": false, 
    "PSTRESS": 0.0, 
    "LMODELHF": false, 
    "CSHIFT": -0.1, 
    "NGYF": 84, 
    "DEPER": 0.3, 
    "LWAVE": true, 
    "SELFENERGY": false, 
    "NGZ": 42, 
    "NPACO": 256, 
    "LASPH": false, 
    "LSPECTRAL": false, 
    "ENCUTLF": -1.0, 
    "EMIN": 10.0, 
    "LSCALU": false, 
    "KINTER": 0, 
    "NSIM": 4, 
    "ISIF": 3, 
    "MODEL_EPS0": 11.60110906, 
    "I_CONSTRAINED_M": 0, 
    "GGA": "--", 
    "TEBEG": 0.0001, 
    "NGXF": 84, 
    "LTETE": false, 
    "NBANDSGW": -1, 
    "MREMOVE": 5, 
    "INIMIX": 1, 
    "AMIN": 0.1, 
    "NGZF": 84, 
    "LMETAGGA": false, 
    "NPAR": 1, 
    "LUSEW": false, 
    "LGWLF": false, 
    "MIXPRE": 1, 
    "MAXMEM": 1024, 
    "ALDAC": 1.0, 
    "L2ORDER": false, 
    "OMEGAGRID": 0, 
    "PREC": "Accura", 
    "NWRITE": 2, 
    "ALDAX": 1.0, 
    "POMASS": [
        26.982, 
        174.967
    ], 
    "LHFCALC": false, 
    "SHIFTRED": false, 
    "DIM": 3, 
    "LGAUGE": true, 
    "NKREDX": 1, 
    "NKREDY": 1, 
    "NKREDZ": 1, 
    "VOSKOWN": 0, 
    "LNABLA": false, 
    "SMASS": -3.0, 
    "ENMAX": 520.0, 
    "AMIX_MAG": 1.6, 
    "RWIGS": [
        -1.0, 
        -1.0
    ], 
    "BMIX": 1.0, 
    "ISTART": 0, 
    "AGGAC": 1.0, 
    "SIGMA": 0.2, 
    "LDIAG": true, 
    "LMONO": false, 
    "SAXIS": [
        0.0, 
        0.0, 
        1.0
    ], 
    "LOPTICS": false, 
    "POTIM": 0.5, 
    "LMAXFOCK": 0, 
    "NSW": 200, 
    "ENCUTGW": 346.66666667, 
    "STM": [
        0.0, 
        0.0, 
        0.0, 
        0.0, 
        0.0
    ], 
    "NOMEGA": 0, 
    "SCISSOR": 0.0, 
    "LPLANE": true, 
    "LREAL": true, 
    "KBLOCK": 200, 
    "TELESCOPE": 0, 
    "MAGATOM": 0, 
    "LCHARG": true, 
    "EPSILON": 1.0, 
    "LNONCOLLINEAR": false, 
    "OMEGAMAX": -30.0, 
    "SYSTEM": "Rubyvaspy :: al lu", 
    "IMIX": 4, 
    "ENINI": 520.0, 
    "ANTIRES": 0
}
```

