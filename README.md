# takeAstone
1. torch.load checkpoint = torch.load(pth_file, map_location=torch.device('cpu')) 会先把模型放在第一个gpu上，所以需要设置location到cpu
2. pytorch_lightening wandb
3. LinearWarmupCosineAnnealingLR 会从0开始到warmup step到达最开始设置的学习率
