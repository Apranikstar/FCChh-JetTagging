# FCChh-JetTagging

```bash
#source /cvmfs/fcc.cern.ch/sw/latest/setup.sh
source /cvmfs/sw.hsf.org/key4hep/setup.sh -r 2025-01-28
git clone https://github.com/Apranikstar/FCChh-JetTagging.git
cd 2.Gen2JetsFiles

python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II/ --outdir ./output/  --sample mgp8_pp_tt_HT_2000_100000_5f_84TeV --ncpus 16
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II/ --outdir ./output/  --sample mgp8_pp_bb_HT_2000_100000_5f_84TeV --ncpus 16
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II/ --outdir ./output/  --sample mgp8_pp_cc_HT_2000_100000_5f_84TeV --ncpus 16
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II/ --outdir ./output/  --sample mgp8_pp_tautau_HT_2000_100000_5f_84TeV --ncpus 16
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II/ --outdir ./output/  --sample mgp8_pp_uuddssgg_HT_2000_100000_5f_84TeV --ncpus 16



python stage_plots.py --indir ./output --outdir ./plots/
```
