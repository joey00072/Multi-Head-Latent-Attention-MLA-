# Multi-Head Latent Attention (MLA)

![MLA](./assets/MLA.png)



## Quick Start
install ohara
```bash
pip install ohara
```

To train MLA:
```bash
python train_mla.py --attn_type=mla
```

For baseline, use MHA:
```bash
python train_mla.py --attn_type=mha 
```
