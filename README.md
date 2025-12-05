# ALIGNN-Alex

Pretrained.py modified to load models from https://github.com/hyllios/utils/tree/main/models/alexandria_v2

## DGL Setup

```bash
pip install dgl -f https://data.dgl.ai/wheels/torch-2.2/cu121/repo.html
# or
conda install -c dglteam/label/th22_cu121 dgl
```

## Usage for Alex. models

```bash
pretrained.py --alex_model e_hull \
	--file_format poscar \
	--file_path alignn/examples/sample_data/POSCAR-JVASP-10.vasp
```

## Properties labels

`band_gap, dos_pa, e_form, e_hull, e_total, mag_per_vol, vol_pa`