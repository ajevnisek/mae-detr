To run an aerial images training run:
```shell
/workspace/deit/mae
python main_pretrain.py      --batch_size 16     --model mae_vit_large_patch16     --norm_pix_loss     --mask_ratio 0.75     --epochs 800     --warmup_epochs 40     --blr 1.5e-4 --weight_decay 0.05     --data_path /mnt/data/aerial_images/DOTAV2_1024x1024/ --output_dir /mnt/data/mae_on_aerial_data/1024x1024_docker --log_dir /mnt/data/mae_on_aerial_data/1024x1024_docker
```