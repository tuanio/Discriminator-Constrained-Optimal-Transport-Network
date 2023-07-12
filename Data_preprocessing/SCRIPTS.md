# Create Helicopter from TIMIT

```bash
python step1_generate_clean_files.py \
    --timit-path /data/tuanio/data/timit/data \
    --target-root /data/tuanio/data/noise/timit-helicopter
```

```bash
python step2_add_noise.py \
    --target-root /data/tuanio/data/noise/timit-helicopter
```

```bash
python step3_convert_to_pt.py \
    --target-root /data/tuanio/data/noise/timit-helicopter
```