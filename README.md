# FCChh-JetTagging

```bash
#source /cvmfs/fcc.cern.ch/sw/latest/setup.sh
source /cvmfs/sw.hsf.org/key4hep/setup.sh -r 2025-01-28
git clone https://github.com/Apranikstar/FCChh-JetTagging.git
cd FCChh-JetTagging/2.Gen2JetsFiles

python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_gg_Q_10000_30000_5f_84TeV --sample mgp8_pp_gg_Q_10000_30000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_thadthad_Q_3000_10000_5f_84TeV --sample mgp8_pp_thadthad_Q_3000_10000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_whadwhad_Q_3000_10000_5f_84TeV --sample mgp8_pp_whadwhad_Q_3000_10000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_gg_Q_30000_84000_5f_84TeV --sample mgp8_pp_gg_Q_30000_84000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_tleptlep_Q_10000_30000_5f_84TeV --sample mgp8_pp_tleptlep_Q_10000_30000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_zhadzhad_Q_10000_30000_5f_84TeV --sample mgp8_pp_zhadzhad_Q_10000_30000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_gg_Q_3000_10000_5f_84TeV --sample mgp8_pp_gg_Q_3000_10000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_tleptlep_Q_30000_84000_5f_84TeV --sample mgp8_pp_tleptlep_Q_30000_84000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_zhadzhad_Q_30000_84000_5f_84TeV --sample mgp8_pp_zhadzhad_Q_30000_84000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_thadthad_Q_10000_30000_5f_84TeV --sample mgp8_pp_thadthad_Q_10000_30000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_tleptlep_Q_3000_10000_5f_84TeV --sample mgp8_pp_tleptlep_Q_3000_10000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_whadwhad_Q_10000_30000_5f_84TeV --sample mgp8_pp_whadwhad_Q_10000_30000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_zhadzhad_Q_3000_10000_5f_84TeV --sample mgp8_pp_zhadzhad_Q_3000_10000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_thadthad_Q_30000_84000_5f_84TeV --sample mgp8_pp_thadthad_Q_30000_84000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_whadwhad_Q_30000_84000_5f_84TeV --sample mgp8_pp_whadwhad_Q_30000_84000_5f_84TeV --ncpus 64

python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_bb_Q_3000_10000_5f_84TeV  --sample mgp8_pp_bb_Q_3000_10000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_bb_Q_10000_30000_5f_84TeV  --sample mgp8_pp_bb_Q_10000_30000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_bb_Q_30000_84000_5f_84TeV  --sample mgp8_pp_bb_Q_30000_84000_5f_84TeV --ncpus 64

python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_cc_Q_3000_10000_5f_84TeV  --sample mgp8_pp_cc_Q_3000_10000_5f_84TeV --ncpus 16
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_cc_Q_10000_30000_5f_84TeV  --sample mgp8_pp_cc_Q_10000_30000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_cc_Q_30000_84000_5f_84TeV  --sample mgp8_pp_cc_Q_30000_84000_5f_84TeV --ncpus 64


python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_uuddss_Q_3000_10000_5f_84TeV  --sample mgp8_pp_uuddss_Q_3000_10000_5f_84TeV --ncpus 16
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_uuddss_Q_10000_30000_5f_84TeV  --sample mgp8_pp_uuddss_Q_10000_30000_5f_84TeV --ncpus 64
python stage_all.py --indir /eos/experiment/fcc/hh/generation/DelphesEvents/fcc_v07/II_trackCov --outdir /eos/user/h/hfatehi/mgp8_pp_uuddss_Q_30000_84000_5f_84TeV  --sample mgp8_pp_uuddss_Q_30000_84000_5f_84TeV --ncpus 64


```
