# Pix2Pix


# Pix2Pix Training

```bash
# Step 1: Install dependencies
pip install -r requirements.txt

# Step 2: Start training
python train.py \
    --data_root data/ \
    --epochs 200 \
    --batch_size 32 \
    --lr 0.0002 \
    --metric_freq 2 \
    --metric_samples 10

# Step 3: Results will be stored in ./outputs
